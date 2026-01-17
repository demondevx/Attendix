# Privacy Policy

**Last Updated: January 17, 2026**

This Privacy Policy describes how Attendix ("the Bot", "we", "us", or "our") collects, uses, stores, and protects your information when you use our Discord bot service.

---

## 1. Introduction

Your privacy is important to us. This Privacy Policy explains:
- What data we collect
- Why we collect it
- How we use and store it
- Your rights regarding your data
- How we protect your information

By using Attendix, you consent to the data collection and usage practices described in this policy.

---

## 2. Data We Collect

### 2.1 Automatically Collected Data

When you use Attendix, we automatically collect:

#### Server Information
- **Guild ID** - Unique identifier for your Discord server
- **Channel IDs** - Identifiers for channels where the bot operates
- **Channel Names** - Names of text and voice channels (for reporting purposes)

#### User Information
- **User ID** - Your unique Discord user identifier
- **Username** - For display in reports and logs (not stored permanently)

### 2.2 Attendance Session Data

During active attendance sessions, we collect:

#### Session Metadata
- **Start Time** - When attendance session began
- **End Time** - When attendance session ended
- **Status** - Active, completed, or early_end

#### Activity Metrics
- **Message Count** - Number of messages sent during the session
- **Channel Breakdown** - Messages per text channel
- **First/Last Message Timestamps** - Activity time range

#### Voice Channel Data
- **VC Session Segments** - Join/leave times for voice channels
- **Channel IDs and Names** - Which voice channels were used
- **Total VC Time** - Cumulative time in voice channels
- **Current VC Status** - Active voice channel session (if any)

#### Voice State Data
- **Mute Segments** - Start/end times when user was muted
- **Mute Type** - Self-mute or server-mute
- **Total Muted Time** - Cumulative muted duration
- **Deafen Segments** - Start/end times when user was deafened
- **Total Deafened Time** - Cumulative deafened duration
- **Mic Toggles** - Count of mute/unmute actions
- **Channel Switches** - Count of voice channel changes

### 2.3 Leave Request Data

When you submit a leave request, we collect:
- **Start Date** - Requested leave start date
- **End Date** - Requested leave end date
- **Reason** - Your explanation for the leave request
- **Status** - Pending, approved, or rejected
- **Admin Remarks** - Comments from administrators (if provided)
- **Timestamps** - Request submission and decision times

### 2.4 Configuration Data

For server administrators, we store:
- **Allowed Role ID** - Role permitted to use staff commands
- **Report Channel ID** - Channel for attendance reports
- **Leave Logs Channel ID** - Channel for leave requests
- **Blacklisted Channel IDs** - Channels excluded from tracking

---

## 3. Data We Do NOT Collect

We explicitly **do not** collect:
- ❌ Message content or text
- ❌ Voice recordings or audio data
- ❌ Direct messages (DMs)
- ❌ Personal information (email, phone number, address)
- ❌ Data from channels where attendance is not active
- ❌ Payment or financial information
- ❌ IP addresses or device information
- ❌ Browser history or cookies

---

## 4. How We Use Your Data

We use collected data solely for:

### 4.1 Core Functionality
- **Attendance Tracking** - Recording and calculating work shifts
- **Report Generation** - Creating detailed attendance reports
- **Statistics** - Providing personal and server-wide analytics
- **Leave Management** - Processing and tracking leave requests

### 4.2 Service Improvement
- **Performance Monitoring** - Ensuring the bot operates correctly
- **Bug Fixes** - Identifying and resolving issues
- **Feature Development** - Improving existing features

### 4.3 Communication
- **Notifications** - Sending DMs for leave request decisions
- **Reminders** - Alerting users before leave ends
- **Reports** - Posting attendance reports to configured channels

---

## 5. Data Storage and Security

### 5.1 Where Data is Stored
- Data is stored in secure **MongoDB databases**
- Databases are hosted on secure cloud infrastructure
- Access is restricted to authorized personnel only

### 5.2 How Long We Store Data

| Data Type | Retention Period |
|-----------|------------------|
| Active Attendance Sessions | Until session ends |
| Completed Attendance Records | Indefinitely (or until server deletion) |
| Leave Requests | Indefinitely (or until server deletion) |
| Configuration Settings | Until bot is removed from server |

### 5.3 Security Measures
We implement industry-standard security measures:
- **Encrypted Connections** - All data transmission is encrypted
- **Access Controls** - Limited database access
- **Regular Backups** - Data backup and recovery procedures
- **Monitoring** - Continuous monitoring for security threats

### 5.4 No Guarantee
While we take reasonable precautions, no method of transmission or storage is 100% secure. We cannot guarantee absolute security.

---

## 6. Data Sharing

### 6.1 We Do Not Sell Your Data
We **never** sell, rent, or trade your data to third parties for marketing purposes.

### 6.2 Limited Sharing
Data may be shared only in the following circumstances:

#### Within Your Server
- **Server Administrators** - Can view attendance reports and session details
- **Staff Members** - Can view their own personal statistics
- **Public Reports** - Reports posted in configured channels are visible to server members

#### Third-Party Services
- **Discord API** - Necessary for bot functionality
- **Database Hosting** - MongoDB database providers (under strict data protection agreements)

#### Legal Requirements
- **Legal Compliance** - If required by law or valid legal process
- **Safety** - To protect our rights, property, or safety, or that of users
- **Enforcement** - To enforce our Terms of Service

---

## 7. Your Rights and Choices

### 7.1 Access Your Data
- View your attendance statistics anytime using `/attendance my-report`
- Request detailed session information through server administrators

### 7.2 Data Deletion

#### Individual Users
- Contact your server administrator to request deletion of your attendance records
- Leave the server (note: data may remain for server record-keeping)

#### Server Administrators
- Remove the bot from your server to stop all data collection
- Contact us to request complete deletion of server data

### 7.3 Opt-Out
- Staff members can choose not to start attendance sessions (no tracking occurs)
- Administrators can blacklist channels to exclude them from tracking

---

## 8. Third-Party Services

### 8.1 Discord
Attendix operates on Discord's platform and is subject to:
- [Discord's Privacy Policy](https://discord.com/privacy)
- [Discord's Terms of Service](https://discord.com/terms)

We are not affiliated with Discord Inc. and are not responsible for Discord's data practices.

### 8.2 Database Providers
We use MongoDB for data storage. Their privacy practices are governed by their own policies.

---

## 9. Children's Privacy

Attendix does not knowingly collect data from children under 13 (or the minimum age required in your jurisdiction). If you believe we have collected data from a child, please contact us immediately.

Discord's Terms of Service require users to be at least 13 years old. By using Attendix, you confirm you meet Discord's age requirements.

---

## 10. International Data Transfers

Your data may be transferred to, stored, or processed in countries outside your own. By using Attendix, you consent to such transfers. We ensure appropriate safeguards are in place to protect your data.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do:
- The "Last Updated" date at the top will change
- Significant changes will be announced (via Discord or GitHub)
- Continued use of the bot constitutes acceptance of changes

We encourage you to review this policy periodically.

---

## 12. Data Breach Notification

In the event of a data breach that affects your data, we will:
- Notify affected users as soon as reasonably possible
- Provide details about what data was compromised
- Explain steps we're taking to address the breach
- Advise you on protective measures you can take

---

## 13. GDPR Compliance (European Users)

If you are located in the European Economic Area (EEA), you have additional rights under GDPR:

### 13.1 Legal Basis for Processing
We process your data based on:
- **Consent** - By using the bot, you consent to data collection
- **Legitimate Interests** - Providing bot functionality and service improvement

### 13.2 Your GDPR Rights
- **Right to Access** - Request a copy of your data
- **Right to Rectification** - Request correction of inaccurate data
- **Right to Erasure** - Request deletion of your data ("Right to be Forgotten")
- **Right to Restriction** - Request limiting processing of your data
- **Right to Portability** - Request transfer of your data
- **Right to Object** - Object to processing of your data
- **Right to Withdraw Consent** - Withdraw consent at any time

To exercise these rights, contact us through GitHub Issues or your server administrator.

---

## 14. CCPA Compliance (California Users)

If you are a California resident, you have rights under the California Consumer Privacy Act (CCPA):
- **Right to Know** - What personal information we collect and how we use it
- **Right to Delete** - Request deletion of your personal information
- **Right to Opt-Out** - Opt-out of the "sale" of your data (we don't sell data)
- **Right to Non-Discrimination** - We won't discriminate against you for exercising your rights

---

## 15. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

- **Developer Contact:** [DemonDev on Discord](https://discord.com/users/555652788592443392)
- **Support Server:** [Join our Support Server](https://discord.gg/s2DGG38cmK)
- **Email:** [support@demondev.org](mailto:support@demondev.org)
- **GitHub Issues:** Open an issue on our repository
- **Server Administrator:** Contact your Discord server administrator for data-related requests

We will respond to your inquiry within a reasonable timeframe.

---

## 16. Acknowledgment

By using Attendix, you acknowledge that:
- You have read and understood this Privacy Policy
- You consent to the collection, use, and storage of data as described
- You have the authority to provide such consent
- You are at least 13 years of age (or the minimum age in your jurisdiction)

---

**Your privacy matters. Thank you for trusting Attendix with your data.**

---

© 2026 Attendix. All rights reserved.
