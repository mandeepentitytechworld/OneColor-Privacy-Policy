# Privacy Policy

**Last Updated:** April 19, 2026

**OneColor** ("we," "our," or "us") operates the OneColor mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this policy carefully. By using the App, you consent to the practices described herein.

---

## 1. Information We Collect

### 1.1 Information You Provide Directly

When you create an account or use our services, we collect the following:

**Account Information:**
- Username
- Email address
- Password (stored securely in encrypted/hashed form)
- Phone number (with country code)

**Personal Information:**
- First name and last name
- Gender (male/female)
- Age
- Profile photo (optional, limited to 512 KB)
- Bio (optional)

**Location Information (User-Provided):**
- Address (optional)
- City
- State
- Country

**Health & Medical Information:**
- Blood group/type
- Weight (kg)
- Donation eligibility status (permanent deferral, temporary deferral, recent donation history)
- Last blood donation date (month and year)
- Blood donation history (donation type, date, location, notes)

**Posts & Community Content:**
- Text content of posts you create
- Blood request posts (blood group needed, component type, urgency level, hospital/location, units needed)
- Comments on posts
- Messages sent through in-app chat (including shared posts)
- Repost content and accompanying text

**Support Tickets & Communication:**
- Support ticket messages and descriptions
- Conversation messages between you and administrators on support tickets
- Ticket status history (open, resolved, closed, reopened)

**Activity & Integrity Logs:**
- Blood group change history — all attempts, whether successful, blocked, or resulting in account restrictions (tracked for fraud prevention)
- Content violation count — the number of times content was blocked by the automated filter (tracked per account, reset to zero on unlock)
- Account lock reason — a predefined reason explaining why the account was locked (e.g., profanity violations or blood group fraud)
- Account lock and unlock events
- Admin action notes associated with ticket status changes

### 1.2 Information Collected Automatically

When you use the App, we may automatically collect:

- **Device Information:** Device model, operating system and version, platform (iOS/Android)
- **App Version:** The version of the App you are using
- **Timezone:** Your device's timezone (detected via your device settings)
- **IP-Based Geolocation:** Your approximate city, state/region, and country (derived from your IP address using the ipapi.co service)
- **Push Notification Token:** A unique device identifier for delivering push notifications (only if you grant notification permission)
- **Error & Crash Data:** Error messages, stack traces, and diagnostic information to improve App stability
- **Usage Data:** Interactions within the App such as screens viewed and features used

### 1.3 Why We Collect Location, IP Address, and Timezone Data

OneColor is a **life-saving blood donation platform**. Accurate location data is not a convenience — it is a **critical necessity**. Here is why:

**🚨 Emergency Response Accuracy:**
When someone creates an urgent or critical blood request, the App must immediately identify eligible donors **in the same city**. Inaccurate location data could mean notifications reach donors hundreds of kilometres away while nearby donors who could save a life are never alerted. In blood donation emergencies, every minute matters — location precision directly impacts whether a patient receives blood in time.

**🩸 Donor-Recipient Matching:**
Blood donation requires physical presence. A donor in Toronto cannot help a recipient in Vancouver. We use your IP-based location to verify and auto-fill your city, state, and country during registration so that the matching system works accurately from day one — even before you manually enter your address.

**📍 Original Location vs. Current Location:**
We store both your **self-reported location** (city, state, country you enter during signup) and your **IP-detected original location** at the time of registration. This helps us:
- Detect if a user's stated location significantly differs from their actual region, which could indicate data entry errors
- Ensure donors are discoverable in the correct geographic area
- Maintain data integrity for the matching algorithms that people's lives depend on

**🕐 Timezone Detection:**
Your device timezone helps us:
- Display donation history, post timestamps, and eligibility countdowns in your local time
- Calculate accurate donation eligibility windows (e.g., "you can donate again in 12 days") based on your local date
- Send push notifications at appropriate hours rather than disturbing donors in the middle of the night

**🔒 Fraud & Safety:**
IP-based location helps us detect suspicious activity such as multiple accounts created from different regions, which could indicate misuse of the platform. This protects genuine donors and recipients from fraudulent requests.

**Important:** We do **not** use GPS or fine-grained device location services. We only derive approximate city-level location from your IP address, which does not require any device permission. This approach balances the life-saving need for location accuracy with your right to privacy.

### 1.4 Information from Third Parties

We use the following third-party services that may process your data:

| Service | What It Provides | Data It Receives |
|---|---|---|
| **Supabase** | Authentication, database, file storage, real-time messaging | Account data, profile data, medical data, messages, posts |
| **ipapi.co** | IP-based geolocation | Your IP address (returns approximate city/region/country) |
| **Expo Push Notification Service** | Push notification delivery | Device push token, notification content |
| **Expo / React Native** | App framework and build infrastructure | Device info, crash reports |

---

## 2. How We Use Your Information

We use the information we collect for the following purposes:

- **Donor-Recipient Matching:** Connect blood donors with those in need based on blood group, geographic location, and donation eligibility — this is the core life-saving function of the App
- **Blood Request Alerts:** When a user creates an urgent or critical blood request, we use blood group and city data to identify matching donors and send them push notifications and in-app alerts
- **Account Management:** Create and manage your user account, authenticate your identity
- **Community Feed:** Display posts, blood request posts, reposts, and comments to the community
- **Help Offer Tracking:** Record when donors offer help on blood request posts, and display the count of helpers to the community
- **Messaging:** Enable direct messaging between users, including sharing posts in conversations
- **Follow System:** Allow users to follow donors and receive updates. If your profile is set to **Public**, follows are approved instantly. If your profile is set to **Private**, follow requests require your explicit approval before the follower can see your posts
- **Contact Requests:** When email and/or phone number are set to **Private**, other users may send a contact request. Your private contact details are revealed only after you **explicitly accept** that request. Contact fields set to **Public** are visible to everyone regardless of follow or request status
- **Eligibility Tracking:** Calculate and display your blood donation eligibility based on your donation history and medical information, following Canadian Blood Services guidelines
- **Safety & Compliance:** Ensure users meet minimum eligibility criteria (age 18–65, weight ≥45 kg, no permanent deferrals)
- **Content Moderation:** Automatically filter and block abusive, offensive, threatening, discriminatory, sexual, or otherwise inappropriate language across all user-generated text in the App — including posts, comments, messages, profile fields, support tickets, and repost captions. This includes detection of profanity in multiple languages (English, Hindi/Urdu), hate speech, slurs, violent threats, explicit content, offensive emojis, and evasion attempts using character substitution (leetspeak)
- **Account Integrity & Restrictions:** Monitor blood group change attempts to prevent fraud. Accounts may be automatically locked if suspicious activity is detected (e.g., repeated blood group change attempts). Locked accounts have restricted access — users can view the feed in read-only mode and communicate with administrators through the support ticket system
- **Support Ticket Management:** Process, track, and respond to user support tickets. Administrators can view your account information, profile data, medical history, and activity logs to investigate and resolve issues. Ticket conversations (messages between you and administrators) are stored and used for support purposes
- **Blood Group Change Logging:** Log all blood group change attempts — including the previous value, new value, whether the change was successful or blocked, and the timestamp — exclusively for fraud prevention and platform integrity
- **Error Logging & Diagnostics:** Log application errors with associated device info, user context (user ID, email, role), platform, and app version to diagnose and fix issues
- **App Improvement:** Analyze error patterns and usage data to improve the App's reliability, performance, and features
- **Location Verification:** Cross-reference IP-detected location with user-provided location for data accuracy and fraud prevention
- **Legal Compliance:** Comply with applicable laws, regulations, and legal processes

---

## 3. How We Share Your Information

### 3.1 With Other Users

When you register as a blood donor, the following information is always visible to other registered users:

- First name and last name
- Blood group
- City and state
- Donation eligibility status
- Gender
- Profile photo (if uploaded)
- Bio (if provided)
- Your follower count, following count, and post count
- Number of people who offered help on your blood request posts

#### Profile & Post Visibility

Post visibility and follow approval are controlled by the **Public Profile** setting in your Privacy Settings:

| | Public Profile ON | Public Profile OFF |
|---|---|---|
| **Posts** | Visible to everyone | Visible only to mutual followers |
| **Follow requests** | Approved instantly — no action needed | Require your explicit approval |

#### Contact Information Visibility

Email address and phone number visibility are controlled **independently** through your Privacy Settings. Each field has its own toggle:

| Contact Field | Setting | Who Can See It |
|---|---|---|
| **Email** | Public | Everyone — no follow or request needed |
| **Email** | Private | Only mutual followers, or users whose contact request you have accepted |
| **Phone** | Public | Everyone — no follow or request needed |
| **Phone** | Private | Only mutual followers, or users whose contact request you have accepted |

**Important:** A **Public Profile** does **not** automatically expose your email or phone number. Contact field visibility is a completely independent control. You can have a public profile with private contact details, or a private profile with a public phone number — each setting is yours to control.

When one or both contact fields are private, other users will see a **"Request Contact Info"** button on your profile. Sending a request notifies you, and the private details are revealed only after **you explicitly accept** that request.

All contact fields are **private by default**. You must actively enable public visibility for any contact field to be shown to others.

### 3.2 With Service Providers

| Provider | Purpose | Data Shared |
|---|---|---|
| **Supabase** | Authentication, database, real-time messaging, and file storage | Account data, profile data, medical data, posts, messages, notifications |
| **ipapi.co** | IP-based geolocation during registration and location auto-fill | Your IP address (we do not store your IP; only the derived city/region/country) |
| **Expo Push Notification Service** | Delivering push notifications to your device | Device push token, notification title and body |
| **Expo / React Native** | App framework and build services | Device info, crash reports |

### 3.3 For Legal Reasons

We may disclose your information if required to do so by law or in the good faith belief that such action is necessary to:

- Comply with a legal obligation or governmental request
- Protect and defend our rights or property
- Prevent or investigate possible wrongdoing
- Protect the personal safety of users or the public

### 3.4 We Do NOT

- Sell your personal information to third parties — **ever**
- Share your medical/health data with advertisers or marketing companies
- Use your data for targeted advertising or ad profiling
- Share your data with data brokers
- Use your location data for advertising or commercial purposes unrelated to blood donation
- Store your IP address beyond the initial geolocation lookup

---

## 4. Push Notifications

We use **Expo Push Notification Service** to send you important alerts. Notifications may include:

- **🚨 Blood Request Alerts:** When someone in your city creates an urgent or critical blood request matching your blood group, you will receive a push notification so you can respond quickly
- **Contact Request Updates:** When someone requests your contact information or when your request is accepted/declined
- **Follow Notifications:** When someone follows you
- **In-App Notifications:** All notifications are also stored in-app and visible in your Notifications screen

**You are in control:**
- Push notifications require your **explicit permission** — we request notification access and respect your choice if you decline
- You can disable push notifications at any time through your device's Settings
- In-app notifications will continue to work even if push notifications are disabled
- We only send notifications that are directly relevant to blood donation activity — we will **never** send marketing or promotional push notifications

**Push Token:**
When you grant notification permission, your device generates a unique push token. This token is stored in our database and used solely to deliver notifications to your specific device. It cannot be used to identify you personally, track your location, or access any other data on your device.

---

## 5. Data Storage and Security

- All data is stored securely on **Supabase** cloud infrastructure with **encryption at rest and in transit**
- Passwords are **hashed** using industry-standard algorithms and never stored in plain text
- We implement **Row Level Security (RLS)** policies at the database level to ensure users can only access their own data
- Medical and health data is protected by RLS — only you can view your full medical profile; other users see only your blood group and eligibility status
- All API communication uses **HTTPS/TLS encryption**
- Profile photos are stored in a secure storage bucket with access policies — you can only upload/modify your own avatar
- Error logs are stored securely and accessible only to authorized development personnel
- Chat messages are encrypted in transit and stored with row-level access controls — only conversation participants can read messages
- Push notification tokens are stored securely and used only for notification delivery

While we strive to use commercially acceptable means to protect your personal information, no method of electronic storage or transmission is 100% secure, and we cannot guarantee absolute security.

---

## 6. Content Moderation & Filtering

To maintain a safe, respectful, and inclusive community, OneColor employs **automated content filtering** on all user-generated text submitted within the App. This applies to:

- Posts and blood request posts
- Comments on posts
- Direct messages (chat)
- Repost captions
- Profile fields (name, bio, designation, address)
- Support ticket messages and conversation replies

### What is filtered:

| Category | Examples |
|---|---|
| **Profanity & vulgar language** | Common English and Hindi/Urdu profanity, including transliterations |
| **Hate speech & slurs** | Racial, ethnic, religious, homophobic, transphobic, and ableist slurs |
| **Sexual & explicit content** | Sexually explicit language, solicitations, and references |
| **Threats & violence** | Death threats, self-harm encouragement, violent language |
| **Drug references** | References to illegal substances |
| **Offensive emojis** | Emojis commonly used in abusive or sexual contexts (e.g., 🖕, 🔫) |
| **Evasion attempts** | Leetspeak and character substitution (e.g., "f*ck," "sh1t," "@ss") |

### How it works:

- Content is checked **at the point of submission** — before it is stored or visible to others
- If restricted content is detected, the submission is **blocked** and the user is shown a warning message
- The original text is **not stored** when blocked
- Content filtering applies equally to all users, including administrators
- The filter does not read or scan content after it has been successfully submitted

### Violation tracking & automatic account locking:

Each time a user submits content that is blocked by the content filter, it is recorded as a **content violation** against their account. The violation count is stored in the user's account record.

| Violation | What happens |
|---|---|
| **1st violation** | Content blocked. Warning shown with remaining attempts before account lock. |
| **2nd violation** | Content blocked. Final warning shown — 1 more violation will lock the account. |
| **3rd violation** | Content blocked. **Account is automatically locked.** User is signed out immediately. |

- The **predefined lock reason** stored on the account is: *"Account locked: Repeated use of abusive or inappropriate language (3 violations)"*
- Administrators can view the lock reason and violation count when reviewing the user's account through the support ticket system
- When an administrator unlocks an account, the violation count is **reset to zero** and the lock reason is cleared, giving the user a fresh start
- Admin and superadmin accounts are exempt from violation tracking and cannot be auto-locked

### Important notes:

- Automated filtering may occasionally flag content incorrectly (false positives). If you believe your content was blocked in error, you can revise your wording and resubmit. Each blocked submission counts as a violation regardless of intent
- We do not use content filtering data for advertising, profiling, or any purpose other than community safety

---

## 7. Account Restrictions & Locking

OneColor may restrict or lock user accounts to protect the integrity of the platform and the safety of its community.

### When accounts may be locked:

- **Blood group fraud prevention**: If a user attempts to change their blood group beyond the permitted limit, the account is automatically locked. Lock reason: *"Account locked: Blood group change violation — exceeded allowed change limit"*
- **Repeated content violations**: If a user triggers the content filter **3 times**, the account is automatically locked. Lock reason: *"Account locked: Repeated use of abusive or inappropriate language (3 violations)"*
- **Administrator action**: Administrators may manually lock accounts that violate community guidelines or exhibit suspicious behavior

### What happens when an account is locked:

| Feature | Available? |
|---|---|
| Log in to the App | ✅ Yes |
| View the community feed | ✅ Yes (read-only — no posting, commenting, liking, sharing, or visiting other profiles) |
| Create support tickets | ✅ Yes (one open ticket at a time) |
| Communicate with administrators via ticket conversations | ✅ Yes |
| View ticket-related notifications | ✅ Yes |
| Access privacy policy | ✅ Yes |
| Sign out | ✅ Yes |
| Create posts, comments, or messages | ❌ No |
| Visit other user profiles | ❌ No |
| Access search, chat, settings, followers, leaderboard | ❌ No |

### How accounts are unlocked:

- Locked users can communicate with administrators through the support ticket system
- An administrator reviews the case and may unlock the account
- When an account is unlocked:
  - The **content violation count is reset to zero** and the **lock reason is cleared**
  - The App **automatically detects the change** (within approximately 10 seconds) and restores full access without requiring the user to log out or restart the App
  - The associated support ticket is automatically resolved

### One-ticket limit:

Locked users can have **only one open support ticket at a time**. To create a new ticket, the existing ticket must first be resolved or closed. This ensures focused, efficient communication between the user and administrators.

---

## 8. Support Ticket System

OneColor provides an in-app support ticket system for users to communicate with administrators.

### What is collected:

- Your contact information (email, username, phone) submitted with the ticket — verified against your registered account information
- The text of your support ticket message
- All conversation messages exchanged between you and administrators on the ticket
- Ticket status changes (open, resolved, closed, reopened) with timestamps

### What administrators can see:

When reviewing your support ticket, authorized administrators can view:
- Your account information (username, email, phone, role, account status, blood group change count)
- Your profile information (name, gender, date of birth, bio, designation)
- Your location information (address, city, state, country)
- Your medical information (blood group, age, weight, deferral status)
- The full conversation thread on your ticket

This information is used **solely for the purpose of investigating and resolving your support request**.

### Ticket conversations:

- Both users and administrators can send messages on open tickets
- Administrator actions (resolve, close, reopen, lock, unlock) are logged as messages in the conversation thread for transparency
- Action messages are prefixed with the action type (e.g., "[Resolved]", "[Account unlocked]") so you know what action was taken and why
- Messages are limited to 500 characters each
- A reply/action note is **required** from both administrators and users before taking any status action on a ticket

### Ticket statuses:

| Status | Meaning |
|---|---|
| **Open** | Active — conversation enabled, awaiting resolution |
| **Resolved** | The issue has been fixed — no further action needed |
| **Closed** | The ticket has been closed without resolution — the matter is dropped |

---

## 9. Blood Group Change Logging

For **safety and fraud prevention**, OneColor logs all blood group change attempts. Blood group is a critical medical field that directly affects donor-recipient matching, and fraudulent changes could endanger lives.

### What is logged:

| Field | Description |
|---|---|
| Previous blood group | The blood group before the change attempt |
| New blood group | The requested new blood group |
| Change type | `successful` (change applied), `blocked_donated` (rejected — user has donation history), `blocked_limit` (rejected — admin change limit reached), `locked_account` (change triggered account lock) |
| Timestamp | When the attempt occurred |

### How this data is used:

- To detect and prevent fraudulent blood group changes
- To enforce change limits (regular users: limited changes; admins: one change per user)
- To automatically lock accounts that exhibit suspicious change patterns
- This data is accessible **only to administrators** through the Users Log and support ticket investigation tools
- Blood group change logs are **never shared** with other users or third parties

---

## 10. Your Rights and Choices

You have the following rights regarding your personal information:

- **Access:** View all your personal data through your profile in the App
- **Update:** Edit your profile, medical information, location, and avatar at any time
- **Delete:** Request complete deletion of your account and all associated data by contacting us
- **Withdraw Consent:** Stop using the App at any time; decline follow and contact requests
- **Notification Control:** Enable or disable push notifications at any time through your device settings
- **Contact Privacy:** Control your email and phone visibility independently through **Privacy Settings**. Each field can be set to Public (visible to everyone) or Private (visible only to mutual followers or users whose contact request you have accepted). All contact fields are **private by default** — you must actively enable public visibility
- **Data Portability:** Request a copy of your personal data in a structured format
- **Photo Removal:** Delete your profile photo at any time through the App
- **Support:** Contact administrators through the in-app support ticket system for any account-related concerns

To exercise any of these rights, please contact us at the email provided in Section 16.

---

## 11. Data Retention

- We retain your personal information for as long as your account is active
- If you delete your account, we will delete or anonymize your personal data within **30 days**, except where we are required to retain it for legal or regulatory purposes
- Error logs are retained for up to **90 days** for diagnostic purposes, after which they are automatically deleted
- Push notification tokens are deleted immediately when your account is deleted
- Notification records (blood request alerts, follow notifications, ticket notifications) are deleted with your account
- Chat messages in conversations you participated in will be anonymized upon account deletion
- Support ticket messages and conversation threads are deleted with your account
- Blood group change logs are retained for the lifetime of the account for integrity purposes and deleted upon account deletion
- Donation history records may be retained in anonymized form for statistical and public health research purposes
- Blood request posts may remain visible (with author anonymized) if other users interacted with them

---

## 12. Children's Privacy

Our App is **not intended for children under the age of 18**. We do not knowingly collect personal information from anyone under 18 years of age. The App enforces a minimum age of 18 during registration in compliance with blood donation eligibility requirements. If we discover that we have inadvertently collected data from a child under 18, we will promptly delete that information and the associated account.

---

## 13. Health Data (Sensitive Information)

We collect health and medical information (blood group, donation history, eligibility status, weight) solely for the purpose of:

- **Determining your eligibility to donate blood** — based on Canadian Blood Services guidelines including waiting periods between different donation types (whole blood, plasma, platelets, double red cell)
- **Matching you with compatible blood recipients** — when someone needs a specific blood type, we match them with eligible donors in their area
- **Tracking safe donation intervals** — our eligibility engine calculates cross-type waiting periods to protect donor health (e.g., 56 days after whole blood before plasma donation)
- **Sending targeted blood request alerts** — when a critical request matches your blood group and city, we notify you so you can help save a life
- **Preventing unsafe donations** — checking for permanent deferrals, minimum weight (≥45 kg), and age range (18–65)

This health data is:
- Stored securely with restricted access via Row Level Security
- **Never shared** with advertisers, data brokers, or any commercial third party
- Only visible to other users in limited form (blood group and eligibility status — not weight, donation dates, or deferral details)
- Protected by database-level access policies ensuring only the data owner can read their full medical record
- Used exclusively for the life-saving purposes described above

---

## 14. International Data Transfers

Your information may be transferred to and maintained on servers located outside your country of residence. Supabase infrastructure may be hosted in regions that include the United States, European Union, and Asia-Pacific. By using the App, you consent to the transfer of your information to countries that may have different data protection laws than your country.

We ensure that any such transfer is protected by appropriate safeguards including encryption in transit and at rest, and contractual obligations with our service providers.

---

## 15. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting a notice within the App

Your continued use of the App after any changes constitutes your acceptance of the updated Privacy Policy.

---

## 16. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Email:** onecolorhelpcenter@gmail.com

You can also reach us through the **in-app support ticket system** (available under "Contact Support" in the App menu).

---

## 17. Compliance

This Privacy Policy is designed to comply with:
- **Apple App Store Guidelines** (Section 5.1 — Privacy, Section 5.6 — Developer Code of Conduct)
- **Google Play Store Policies** (User Data policy, Inappropriate Content policy)
- **General Data Protection Regulation (GDPR)** — for users in the European Union
- **California Consumer Privacy Act (CCPA)** — for users in California
- **Personal Information Protection and Electronic Documents Act (PIPEDA)** — for users in Canada
- **Information Technology Act, 2000** and **SPDI Rules, 2011** — for users in India

---

## 18. Consent

By creating an account and using the OneColor App, you acknowledge that you have read, understood, and agree to be bound by this Privacy Policy. You explicitly consent to:

- The collection and processing of your health/medical data for blood donation matching and eligibility purposes
- The collection of your IP-based geolocation for accurate donor-recipient matching and location verification
- The collection of your device timezone for accurate time-based calculations
- The delivery of push notifications related to blood donation requests (if you grant notification permission)
- The storage and processing of your data on servers that may be located outside your country of residence
- Automated content moderation and filtering of all user-generated text for community safety
- Tracking of content filter violations per account, with automatic account locking after 3 violations
- Account restrictions (including read-only mode and limited feature access) in response to policy violations or suspicious activity
- The storage of predefined lock reasons on your account record, visible to administrators
- The logging of blood group change attempts for fraud prevention purposes
- Administrator access to your account and profile data (including violation count and lock reason) when investigating support tickets
