# Mercury Power Twin — Privacy Policy

Effective date: 16 November 2026. Applies to iOS version 1.0, including the device-owner access update from build 15 onward.

Mercury Power Twin is a local CAD and conceptual 3D modeling application. Standard subscription access does not require an app account. There is no advertising network, analytics SDK, developer-operated project upload or tracking.

## Projects and imported documents

Drawings, dimensions, equipment parameters, imported files, previews and saved projects are processed on the device. Selecting a file from Files may involve a storage provider you choose, such as iCloud Drive. That provider's policy applies. The app does not send project content to the developer for AI training or automatic cloud conversion.

## Sharing and external links

Exports are shared only through the destination you choose in the iOS share sheet. Recipients control subsequent use. External engineering resources have their own policies.

## Retention and deletion

Projects stay in local app storage until deleted. Removing the app removes its local container, subject to backups managed by iOS. Exported copies must be removed separately. The developer cannot remotely access or delete drawings.

## Subscriptions

Apple handles purchases, payment details, renewals, refunds and subscription management. StoreKit supplies signed transaction and entitlement information so access can be verified on the device. Restore Purchases explicitly synchronizes with Apple. The app does not send transactions or projects to a developer-operated server and does not receive payment-card details. Removing the app or a project does not cancel a subscription; use Apple subscription settings. Beta build 9 does not include in-app purchases.

## Device-owner administrator access

From build 15, Sign in with Apple is replaced by a device-specific local administrator mechanism. The app generates a random app-specific pairing secret in non-synchronizing, device-only Keychain storage. Its derived pairing code is visible under Support and diagnostics. It is not a hardware identifier and is not automatically transmitted. The owner may explicitly copy and share this code with the developer to request association of that device. The copy is local to the device clipboard and expires after five minutes. Administrator fields are hidden on devices not included in the app's authorization policy.

On an associated device, the owner privately configures a username and password. The app retains a random salt and a PBKDF2-HMAC-SHA256 verifier in protected, non-synchronizing, device-only Keychain storage, together with failed-attempt throttling data. It does not retain the cleartext username or password. Credentials are not sent to the developer. There is no developer-operated account database. Authentication is held only in memory; fields are cleared after submission or leaving the screen, and the session locks when the app becomes inactive or closes. Foregrounding the app does not restore administrator authentication.

Resetting the local administrator account requires the device's native authentication, such as Face ID or the device passcode. The app does not receive biometric templates. Resetting the account removes its local verifier and does not delete project files. Keychain records may survive reinstallation on the same device; device-only records do not synchronize through iCloud Keychain or transfer as an administrator credential to another phone.

Earlier beta build 14 used Apple's app-scoped Sign in with Apple identifier and optional email in Keychain. The new mechanism does not use that saved identity or restore its signed-in state. Any earlier Apple authorization can be managed in Apple Account settings. Subscription cancellation and project deletion remain separate actions.

## Apple services

Apple may process App Store transactions, TestFlight information, diagnostics and device backups under Apple's settings and privacy policies. These services are not an application account operated by the developer.

## Contact and changes

Use the Issues section of the Mercury Power Twin support repository for support and privacy questions. Do not put passwords, confidential engineering documents or personal information in a public issue. Changes in data practices will be reflected in this policy and the App Store privacy declaration.
