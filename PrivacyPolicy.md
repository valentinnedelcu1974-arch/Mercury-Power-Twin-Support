# Mercury Power Twin — Privacy Policy




Effective date: 16 November 2026. Applies to iOS version 1.0, including the StoreKit subscription update.




Mercury Power Twin is a local CAD and conceptual 3D modeling application. The developer does not collect personal data through this version of the app. Standard subscription access does not require an app account. The optional owner administrator access uses Sign in with Apple as described below. There is no advertising network, analytics SDK, developer-operated cloud upload, or tracking.




## Projects and imported documents




Drawings, dimensions, equipment parameters, imported files, previews, and saved projects are processed on the device. Selecting a file from Files may involve a storage provider you choose, such as iCloud Drive. That provider's own privacy policy applies. The app does not send project content to the developer for AI training or automatic cloud conversion.




## Sharing and external links




Exports are shared only through the destination you choose in the iOS share sheet. If you send a drawing to another application or service, that recipient controls its subsequent use. Links to external engineering resources open services with their own policies.




## Retention and deletion




Projects stay in local app storage until deleted. Removing the app removes its local container, subject to any backup managed by iOS. Copies exported to Files, iCloud, another app, or another recipient must be removed separately. The developer cannot remotely access or delete your drawings.




## Subscriptions


In builds with subscriptions, Apple handles purchases, payment details, renewals, refunds, and subscription management. StoreKit supplies signed transaction and entitlement information to the app so it can verify access on the device. Restore Purchases explicitly synchronizes with Apple. The app does not send transaction data or project documents to a developer-operated server. The developer does not receive payment-card details through the app. Removing the app or a project does not cancel a subscription; use Apple subscription settings. Earlier beta build 9 does not include in-app purchases.


## Owner administrator authentication

The optional administrator route authenticates the owner through Apple AuthenticationServices. Apple provides an app-scoped user identifier and, on first authorization, a verified email address. The app checks this native credential against the owner authorization rule. It stores the authorized identifier, email and signed-in state in Apple Keychain; this protected binding may synchronize through iCloud Keychain when enabled. Passwords, identity tokens and authorization codes are not stored by the app or transmitted to a developer-operated server. No developer-operated user database is created.

The saved Keychain identity may survive reinstallation. Sign out or use Administrator → Eliminate saved identity to remove the app's remembered authorization. Apple authorization can also be revoked in the Apple Account settings for Sign in with Apple. Subscription cancellation and deletion of project files are separate actions.

## Apple services




Apple may process App Store transactions, TestFlight information, diagnostics, and device backups under Apple's settings and privacy policies. These services are not an application account operated by the developer.




## Contact and changes




Use the Issues section of the Mercury Power Twin support repository for support and privacy questions. Do not include confidential engineering documents or personal information in a public issue. Changes to data practices will be reflected in an updated policy and App Store privacy declaration.



