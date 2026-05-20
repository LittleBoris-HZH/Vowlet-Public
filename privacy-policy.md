# Vowlet Privacy Policy

Effective Date: April 12, 2026  
Last Updated: May 6, 2026

This Vowlet Privacy Policy (hereinafter referred to as "this Policy") is established by LittleBoris (hereinafter referred to as "we" or "us") and applies to the Vowlet iOS application and its related features, pages, synchronization capabilities, notification capabilities, sharing capabilities, and support services.

This Policy is intended to explain: what information we process when you use Vowlet, why we process such information, how such information is stored and shared, and how you may manage your privacy and permissions.

If you do not agree with all or part of this Policy, you should discontinue use of the relevant features; however, please note that certain core functionalities may not operate properly without the necessary permissions or data.

## 1. Scope of Application

This Policy applies to:

- Features within the Vowlet iOS application, including vow creation, editing, check-in, statistics, reminders, team sharing, and profile display;
- iCloud / CloudKit synchronization, HealthKit data reading, MapKit map and location search, photo selection, notifications, and background synchronization implemented through system services provided by Apple;
- Subscription functionality implemented through the in-app purchase mechanism provided by Apple;
- Account and data deletion functionality;
- Information you voluntarily submit when contacting us via email or other support channels.

This Policy does not apply to:

- Independent privacy processing activities of system services provided by Apple itself, including iCloud, CloudKit, HealthKit, MapKit, Photos, Push Notifications, StoreKit, and others;
- Non-Vowlet services you access through third-party websites, third-party applications, or Apple system pages.

For services provided by Apple, Apple may process relevant data independently in accordance with its own privacy policy and terms of service.

## 2. Types of Information We Process

We process information in accordance with the principles of "necessary for feature functionality" and "minimal necessity." Based on the code implementation of the current version as of May 6, 2026, Vowlet may process the following information:

### 2.1 Information You Voluntarily Provide or Create During Use

1. Personal Profile Information
   Including your nickname, avatar Emoji, Memoji/avatar image, and avatar background color that you set or generate using system capabilities, as well as name information that may be synchronized from Apple CloudKit identity information in team sharing scenarios.

2. Vow and Plan Content
   Including vow titles, descriptions, categories, priority levels, goals, start dates, end dates, participant roles, invitation statuses, node tasks, check-in tasks, witness messages, completion notes, archived images, and vow locations.

3. Check-in Content
   Depending on the check-in method you select, this may include:
   - Text check-in content;
   - Images you voluntarily select and submit;
   - Actual check-in coordinates recorded during location-based check-in;
   - Completion records and results for exercise or sleep check-in.

4. Team Sharing and Partner Relationship Information
   Including CloudKit user record identifiers of friends, nicknames, avatar display information, last collaboration time, time added, and invitation and member status information used to establish and maintain sharing relationships.

5. Witness Messages
   In team-shared vows, you may send witness messages to other participants. Witness messages include message text and sending time, and are synchronized among all participants via CloudKit.

6. Contact and Feedback Information
   When you voluntarily send emails to `feedback@littleboris.com` or contact us through other means, we may receive your email address, email content, and any attachments or issue descriptions you voluntarily provide.

### 2.2 Information Obtained Through Device Permissions or System Services

1. Health Data
   With your authorization, Vowlet reads health data related to functionality through Apple HealthKit, including:
   - Active energy burned;
   - Exercise records and activity summaries;
   - Sleep analysis data.

   This information is used solely for exercise/sleep check-in verification, chart display, statistical display, and automatic completion determination. The current version does not upload raw HealthKit data to our own servers for advertising, marketing, or data brokerage purposes.

2. Location Information
   When you use the location-based check-in feature and grant location permissions, Vowlet reads your device's location for that session to verify whether you have arrived at the designated location. If you complete a location-based check-in, the relevant check-in coordinates are saved as part of the check-in record within the application data, and may be synchronized across your devices via Apple's iCloud / CloudKit mechanism.

3. Map and Location Search Information
   When you use features such as location search, location selection, or map display, your search keywords, location results, and map-related requests may be processed through Apple MapKit services.

4. Notification and Reminder Related Information
   Including notification authorization status, reminder preferences, reminder times, do-not-disturb periods, notification type preferences, and minimal necessary parameters used for notification navigation (e.g., vow identifier, notification type, target page).

5. Technical and Synchronization Related Information
   To implement iCloud / CloudKit synchronization, sharing relationship establishment, shared database subscriptions, and background silent refresh, Apple and system frameworks may process necessary technical information, including device and system environment, CloudKit record identifiers, sharing metadata, push event information, and necessary service status information.

6. In-App Purchase Information
   Vowlet processes subscriptions and purchases through the in-app purchase mechanism provided by Apple. When you purchase a subscription or a one-time item:
   - All payment processing is completed by Apple; Vowlet does not collect or store your payment card numbers, bank accounts, or other financial information;
   - Vowlet only receives necessary information returned by Apple, such as transaction identifiers, purchase status, and subscription validity periods;
   - Transaction verification is completed by Apple's systems and does not rely on external servers;
   - Your subscription status is stored only on the local device and Apple's servers.

### 2.3 Information Not Actively Processed in the Current Version

As of May 6, 2026, the current version has not identified the following capabilities being used for core business processing:

- Third-party advertising SDKs;
- Third-party analytics SDKs;
- Advertising identifiers (IDFA) or App Tracking Transparency tracking;
- Contacts reading;
- Microphone permissions;
- Camera permissions;
- Independent account and password systems;
- Self-built payment/subscription backends (the current version processes payments through the in-app purchase mechanism provided by Apple, with all payment information managed by Apple).

Should future versions introduce any of the aforementioned capabilities or other new data processing activities, we will update this Policy and, where required by applicable laws, separately obtain your authorization or provide additional explanations to you.

## 3. How We Collect Information

We primarily collect information through the following methods:

1. Information You Directly Provide
   For example, when you fill in your nickname, create a vow, set tasks, send witness messages, submit text/image check-ins, or send feedback emails.

2. Information Generated When You Voluntarily Trigger System Capabilities
   For example, when you tap location-based check-in, select photos, enable notifications, authorize HealthKit, search for locations, or use team sharing.

3. Information Returned by Apple Systems and Cloud Services
   For example, identifying sharing relationships through CloudKit sharing invitations, refreshing profile information through CloudKit public databases, prompting for shared status changes through silent push notifications, and returning purchase transaction information through Apple's in-app purchase mechanism.

4. Information Automatically Generated on the Local Device
   For example, notification preferences, read status, certain feature toggles, reminder deduplication markers, local cache status, and subscription entitlement information.

## 4. Purposes and Legal/Business Bases for Processing Information

We process your information primarily for the following purposes:

1. Providing Core Functionality
   For creating, editing, displaying, and managing vows, tasks, nodes, statistics, and check-in records.

2. Verifying and Displaying Check-in Results
   For example, generating or displaying check-in status based on the text you enter, images you submit, your current location, and HealthKit reading results.

3. Providing Synchronization, Backup, and Multi-Device Experience
   When Apple iCloud / CloudKit is available, for synchronizing necessary application data across your devices and maintaining profile records required for sharing relationships.

4. Establishing and Maintaining Team Sharing Relationships
   For creating invitations, identifying the identities of both parties to an invitation, maintaining partner lists, synchronizing profile information, and processing shared status changes.

5. Sending Reminders and Messages
   For scheduling local reminders, displaying real-time notifications, and triggering appropriate prompts or page navigation after shared status changes.

6. Providing Support, Troubleshooting Issues, and Maintaining Service Security
   When you report issues or when we perform necessary processing to ensure functionality stability, integrity, and security, we may use the minimum necessary information.

7. Processing In-App Purchases and Subscriptions
   For verifying purchase status, managing subscription entitlements, and providing purchase restoration functionality.

8. Fulfilling Legal Obligations or Responding to Legitimate Requests
   Under applicable laws, regulatory requirements, judicial orders, or legitimate governmental requests, we may process or disclose necessary information.

## 5. iCloud, CloudKit, and Shared Profile Information

### 5.1 Your Application Data May Be Synchronized Through Apple Cloud Services

The current version processes certain persistent data based on Apple's SwiftData and CloudKit mechanisms. This means:

- Some data you save within the application may be stored locally on your device;
- When Apple iCloud / CloudKit is available and the system permits, this data may be synchronized to your Apple cloud environment and remain consistent across your devices;
- Some data (such as notification delivery records) is saved only on the current device and is not synchronized to the cloud;
- This synchronization capability relies on infrastructure provided by Apple, rather than our own general-purpose business servers.

### 5.2 Special Handling of Team Sharing Profile Information

To support partner identification and profile refresh, the current version may write the following profile information to the corresponding records in Apple CloudKit:

- Nickname;
- Avatar Emoji;
- Avatar background color;
- Real name (where applicable).

Some of this information is used for:

- Generating sharing invitation metadata;
- Refreshing the other party's profile display after establishing a partner relationship;
- Displaying organizer or partner identity in team sharing pages.

Please do not set highly sensitive, confidential, or information you do not wish to display in sharing relationships as your nickname or profile information. In particular, the current version may synchronize the real name field in team sharing scenarios; therefore, you should carefully evaluate whether to enable the relevant sharing capabilities.

### 5.3 Current Version Information Regarding Sharing Scope

As of May 6, 2026, in the current code implementation, data directly related to establishing relationships with other users is primarily focused on:

- Sharing invitations;
- Partner identity recognition;
- Profile information synchronization;
- Team shared space management;
- Witness messages;
- Notifications and status maintenance related to sharing relationships.

Shared Data Visibility:
- Your profile information is only visible to users with whom you have established a partner relationship;
- Vow content, check-in records, and witness messages are only visible to participants of the same vow;
- You can control the visibility scope of your data by removing partners or stopping sharing.

Should future versions introduce broader multi-party collaboration, cross-user vow sharing, cross-user check-in, or community interaction capabilities, we will update this Policy separately based on the new functionality.

## 6. Special Provisions Regarding HealthKit Data

After you authorize Vowlet to access HealthKit, we read exercise and sleep information related to functionality for the following purposes:

- Automatic check-in determination for exercise/sleep tasks;
- Exercise summaries, workout details, sleep structure charts, and related statistical display;
- Automatic completion backfill for historical dates.

Regarding HealthKit data, we specifically note:

- We read only the minimum necessary health data related to current functionality;
- All health data is processed solely in device memory for calculating check-in results and generating statistical charts; raw health data is not persistently stored or uploaded to the cloud;
- For automatic check-in, the application saves only the final check-in result and does not store raw health sample data;
- The current version does not sell, lease, or use raw HealthKit data for advertising purposes;
- The current version does not use raw HealthKit data for advertising, marketing, user profiling, or third-party data brokerage;
- The collection, authorization, revocation, and underlying storage of HealthKit data remain subject to Apple Health ecosystem rules.

You may revoke the relevant authorization at any time through the Health app or system settings on your iPhone. Upon revocation, the relevant functionality may be degraded, rendered inoperable, or unable to continue automatic determination.

## 7. Location Information and Map Functionality

When you use location-related features:

1. Location Setting
   You may voluntarily select location names, coordinates, and radius ranges for vows or check-in tasks.

2. Location Verification
   When you initiate a location-based check-in, the application reads your device's actual location for that session and determines whether you are within the target radius.

3. Record Storage
   The current version saves the actual check-in coordinates of location-based check-ins as part of the check-in record. This record may be saved locally along with application data and may be synchronized via Apple's iCloud / CloudKit mechanism.

4. Apple Map Services
   If you use location search, map display, or map feature parsing functionality, the relevant requests may be processed by Apple MapKit.

If you do not agree with our processing of location information as described above, please do not enable the location-based check-in feature or disable location permissions in system settings.

## 8. Images, Avatars, and Media Content

The current version allows you to:

- Select vow archive images;
- Select images as image check-in content;
- Use Emoji or Memoji/avatar images as part of your profile information.

These media contents are voluntarily selected and submitted by you. Except for local display, persistence, and Apple cloud synchronization necessary to implement functionality, we do not use them for advertising analytics or sell them to third parties in the current version.

The images you select are compressed before saving to optimize storage and transfer efficiency. Compressed images may be synchronized across your devices via Apple cloud services. Images in your original photo album are not directly accessed or uploaded by the application.

Please do not upload images containing other individuals' private information, sensitive documents, financial information, medical records, or other content you are not authorized to share.

## 9. Notifications, Background Refresh, and Silent Push

Vowlet uses notification capabilities to provide:

- Check-in reminders;
- Node reminders;
- Vow activation or expiration reminders;
- Team sharing related reminders;
- Real-time prompts such as all-completed notifications.

The current version simultaneously uses:

- Local notifications;
- CloudKit silent push notifications within Apple Push Notification service, used to detect shared status changes and complete data refresh or prompts locally.

Notification Related Data:
- Notification preference settings (such as reminder times, do-not-disturb periods, toggle states, etc.) are stored only on the local device and are not synchronized to the cloud;
- Notification delivery records are saved only on the current device for preventing duplicate notifications and are not synchronized to the cloud;
- CloudKit silent push notifications are used solely to trigger local data refresh and do not contain sensitive content.

Notification content may include vow titles or functional text and may be displayed on the lock screen, notification center, or banners in accordance with your system settings. You may disable notification permissions at any time in system settings, or adjust reminder preferences and do-not-disturb periods within the application.

## 10. How We Share, Disclose, or Entrust the Processing of Information

Except in the following circumstances, we do not sell your personal information to third parties, nor do we use your personal information for third-party advertising targeting:

1. Disclosure to Apple-Provided Infrastructure
   To implement Apple platform capabilities such as iCloud / CloudKit, HealthKit, MapKit, photo selection, and push notifications, necessary information may be processed by Apple as an independent service provider.

2. Disclosure to Other Users When You Voluntarily Use Sharing Features
   When you use team sharing or partner invitation features, certain profile information and sharing relationship information may be visible to other users who have established a relationship with you.

3. Reporting and Security Protection
   Vowlet provides a reporting feature that allows users to report inappropriate content or behavior. When you submit a report, the relevant information is used solely by the developer for security review and processing.

4. Legal Requirements or Rights Protection
   When we have reasonable grounds to believe that disclosure is necessary to comply with legal obligations, enforce agreements, protect user safety, investigate fraud, or respond to legitimate requests, we may disclose necessary information as required by law.

5. Business Reorganization or Asset Transfer
   In the event of a future merger, acquisition, reorganization, asset transfer, or similar transaction, relevant information may be transferred as part of the transaction. In such cases, we will take reasonable notification measures as required by applicable laws.

## 11. Data Storage, Retention, and Deletion

### 11.1 Storage Locations

Data in the current version may primarily be stored in:

- Your local device (where some data may be synchronized through Apple cloud services, and some is saved only on the current device);
- Apple iCloud / CloudKit environment;
- Email systems or support channels to which you have voluntarily sent communications.

### 11.2 Retention Periods

We generally retain information for the minimum period necessary to fulfill the purposes of processing, unless a longer retention period is:

- Required by laws or regulations;
- Necessary for resolving disputes, handling complaints, or enforcing agreements;
- Reasonably necessary for ensuring system security, auditing, or preventing abuse.

In the current version, vows, check-ins, profiles, partner relationships, and notification preferences are generally retained until:

- You voluntarily delete the relevant content;
- You stop sharing and remove the relevant relationships;
- You delete application data, exit the relevant Apple cloud environment, or remove the corresponding cloud data through methods provided by Apple;
- Applicable backups, caches, or disaster recovery copies are naturally overwritten within a reasonable cycle.

Account Change Protection:
When Vowlet detects that your iCloud account has changed, it automatically clears all locally stored application data, including vows, profiles, friend relationships, and more. This mechanism ensures that your data is not inadvertently disclosed or confused following an account change.

### 11.3 Deletion and Correction

Based on the capabilities of the current version, you may generally:

- Edit or delete vow content;
- Edit profile information;
- Remove partners or stop sharing;
- Revoke permissions for notifications, location, health data, and others;
- Control system permissions for iCloud, notifications, photos, location, health, and others through Apple device settings.

### 11.4 Account and Data Deletion

To comply with Apple Guideline 5.1.1(v), Vowlet provides a complete account and data deletion feature. As Vowlet does not use an independent account system, the deletion process will clear all application data associated with you.

The deletion process includes the following steps:

1. Cancel all local notifications and reminders;
2. Stop subscriptions and synchronization related to Apple cloud services;
3. Terminate all sharing relationships and remove shared data;
4. Delete profile information published to the cloud;
5. Clear all application data (including vows, check-in records, witness messages, spaces, friends, categories, personal profiles, etc.);
6. Clear local notification records;
7. Clear application preferences;
8. Reset in-memory state.

Important Notice:
- The deletion operation is irreversible; once data is deleted, it cannot be recovered;
- The deletion process employs an independent fault-tolerant design; failure of a single step will not interrupt the overall deletion process;
- If you have an active subscription, you need to cancel it separately in system settings, as subscription status is managed by Apple;
- Upon completion of deletion, the application will be restored to its initial state.

If you wish to exercise deletion, correction, or other requests regarding data within the scope of application support, you may contact us through the contact information provided at the end of this Policy. For data independently controlled by the Apple platform, you may also need to process it through Apple's settings or service pages.

## 12. Security Measures

We implement reasonable security measures appropriate to the current product form, including but not limited to:

- Minimizing unnecessary data processing;
- Relying on permission controls, container isolation, CloudKit, and system security capabilities provided by Apple;
- Limiting the scope of unrelated permissions in feature design;
- Automatically clearing old data upon account changes to prevent data leakage.

However, you understand that no application, device, local storage, network transmission, or cloud environment can be made absolutely secure. Please safeguard your own device, Apple account, and system access permissions.

## 13. Your Rights and Choices

Depending on applicable law, you may have the following rights:

- Right to be informed;
- Right of access;
- Right to rectification;
- Right to erasure;
- Right to withdraw consent or revoke authorization;
- Right to restrict or object to processing;
- Right to request a copy of data to the extent permitted by law.

You may manage your privacy through the following methods:

- Modifying profiles, deleting content, and adjusting notification preferences within Vowlet;
- Using Vowlet's built-in "Account and Data Deletion" feature to clear all application data with one tap;
- Disabling permissions for location, notifications, photos, health data, and others in iOS system settings;
- Managing cloud synchronization capabilities in Apple account or iCloud settings;
- Contacting us via email to process reasonable requests.

In certain circumstances, due to identity verification, technical limitations, legal obligations, or the protection of others' rights, we may not be able to fully accommodate your request, but we will provide explanations within a reasonable scope.

## 14. Protection of Minors

Vowlet is not specifically designed for children. If applicable law requires you to obtain guardian consent before use, you should use the relevant services only after obtaining appropriate authorization. If we discover that information of minors has been collected in violation of applicable law, we will take reasonable measures to address the situation as promptly as possible.

## 15. Cross-Border Processing

As the current version relies on services provided by Apple, including iCloud / CloudKit, MapKit, HealthKit, and others, relevant data may be processed in data centers or service nodes operated by Apple in different regions, depending on Apple's service architecture, your account settings, and applicable law.

The core functionality of our current version is not centered on self-built general-purpose business backends; however, this does not mean that cross-regional data processing does not exist. Processing activities involving Apple platform services may still be subject to Apple's cross-border rules and related terms.

## 16. Reserved Provisions for Future Features

To ensure compliance with future product expansion, should future versions introduce the following capabilities, we may process corresponding information within the necessary scope and will notify you through updates to this Policy, pop-up explanations, permission request pages, or separate agreements:

- Account login and identity verification;
- Crash diagnostics, performance analysis, and analytics;
- Customer service tickets and online support;
- Community content, public profiles, or public interactions;
- AI-generated content, intelligent summaries, or intelligent recommendations;
- Web, desktop, or cross-platform synchronization;
- Other third-party service integrations not yet enabled in the current version.

The current version has already implemented subscription functionality through Apple's in-app purchase mechanism, including monthly, annual, and lifetime subscriptions for individual and family plans. All payment processing is completed by Apple; Vowlet does not collect or store your payment information. Subscription status is used solely to control feature access and is not used for advertising targeting or user profiling.

Before the aforementioned capabilities are actually enabled, the relevant reserved provisions in this Policy do not constitute an indication that we have commenced corresponding processing activities.

## 17. Updates to This Policy

We may update this Policy based on changes in law, regulatory requirements, product feature iterations, or changes in processing activities. Updated versions will be published through in-app pages, official website pages, release notes, or other reasonable methods.

If an update would have a material impact on your rights, we will provide you with more prominent notice to the extent required by applicable law.

## 18. Contact Us

If you have questions about this Policy, your personal information, how permissions are used, or data processing requests, you may contact us through the following methods:

- Email: `feedback@littleboris.com`

When contacting us, please try to include:

- That you are using Vowlet;
- The type of issue;
- The feature page involved;
- The specific matter you would like us to assist with.

## 19. Implementation Notes for the Current Version

To avoid inconsistencies between the Policy and implementation, as of May 6, 2026, the current version specifically notes the following:

- Data processing that has been implemented and may be triggered: local persistence, iCloud / CloudKit synchronization, CloudKit sharing invitations and shared profile refresh, HealthKit read-only access, MapKit map and location search, photo selection, local notifications, CloudKit silent push, email feedback entry, in-app purchases, account and data deletion, reporting feature;
- Processing not currently identified: third-party advertising, third-party analytics, ATT tracking, Contacts, microphone, camera, independent account and password systems;
- If application page copy, settings page descriptions, or future version features are inconsistent with this Policy, the version that is stricter, more transparent, and more compliant with applicable legal requirements in the actually effective version shall prevail; in the event of obvious conflicts, we recommend that developers promptly synchronize and revise product copy and permission descriptions.
