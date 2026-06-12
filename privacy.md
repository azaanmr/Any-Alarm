# Privacy Policy for Any Alarm
**Effective Date:** June 12, 2026

## 1. Introduction
Welcome to Any Alarm. This Privacy Policy outlines how your information is handled when you use our mobile application ("the App"). We are committed to protecting your privacy and ensuring that your data is secure.

## 2. Data We Collect and How We Use It
Any Alarm is designed to operate primarily locally on your device. Except for the non-personally identifiable data required for our referral system (detailed below), we do not collect, transmit, or store your personal data on external servers.

* **Location Data (Foreground & Background):** The App requests access to your device's location (including `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`, and `ACCESS_BACKGROUND_LOCATION`) to power the "Commute Alarm" and "Geo To-Do" features. This allows the App to monitor when you enter or exit your designated alarm zones. All location data is processed strictly in real-time on your local device (using Google Play Services Geofencing). We **do not** transmit, store, or share your location coordinates to any external servers or third parties.
* **Referral System Identifiers:** To enable our optional referral unlock feature, the App generates a unique, non-personally identifiable token by cryptographically hashing your device's `ANDROID_ID` (SHA-256). This hashed token, your generated 6-character referral code, and your referral progress count are stored securely in Google Cloud Firestore. This is used solely to prevent fraud (such as self-referrals) and track milestones to unlock the "Notify" tab. No personal information (e.g., name, email, contacts) is ever collected or linked to this token.
* **Camera Access:** The App requests access to your device's camera strictly for the "QR Code Alarm" feature. The camera is used solely to scan barcodes or QR codes in real-time to dismiss an active alarm. No images, video, or scan data are ever recorded, saved, or transmitted off your device.
* **Physical Activity / Step Counter:** The App requests access to your physical activity data (ACTIVITY_RECOGNITION) exclusively for the "Step Counter" alarm challenge. This data is used in real-time solely to verify movement and dismiss an active alarm. All step processing happens locally on your device.
* **Wake-Up Statistics:** To provide the "Wake Up Score" and performance charts, the App saves a local record of your alarm dismissal history (e.g., how long you took to dismiss an alarm). This history is stored strictly on your device.
* **Local Storage:** Your alarm configurations (times, intervals, math quiz settings, and registered QR codes) are saved securely in your device's local database.

## 3. Third-Party Services and Advertising
While we do not collect your personal data on our own servers, the App utilizes third-party services that may collect information used to identify you or your device to provide essential app functionality and advertising.

* **Google Play Services:** Used for system security, geofencing, in-app updates, and the In-App Review API.
* **Google Cloud Firestore (Firebase):** Used to store and synchronize non-personally identifiable referral codes and device counts for our unlock system.
* **Google AdMob:** We use Google AdMob to display advertisements within the App. AdMob may collect and use information such as your device's Advertising ID, IP address, and coarse location to serve relevant ads and perform fraud prevention. You can manage your ad preferences via your Android device's "Ads" settings.

## 4. Alarms and Notifications
To ensure alarms fire reliably, the App utilizes Android's exact alarm scheduling and background/foreground services. This requires the app to wake your device and display full-screen notifications. This process is technical in nature and does not collect personal information for transmission.

## 5. Data Retention and Deletion
* **Local Data:** All local app data—including your saved alarms, wake-up history, and settings—is tied directly to your local device installation. You can permanently delete all local data by clearing the App's data in your Android settings or by uninstalling Any Alarm.
* **Referral Data:** Since referral records are stored securely in Firestore, if you wish to have your hashed identifier deleted from our referral system, please contact us at the email address below.

## 6. Children's Privacy
Any Alarm does not knowingly collect personally identifiable information from children. The App's features do not transmit personal data to our servers, keeping children's privacy protected.

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top.

## 8. Contact Us
If you have any questions, concerns, or suggestions regarding this Privacy Policy or the Any Alarm app, please contact:
**Email:** muhammadazaanmr@gmail.com
