# Attendix - Professional Attendance Management Bot 📊

![Discord](https://img.shields.io/badge/Discord-Bot-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

**Attendix** is a comprehensive Discord bot designed to streamline attendance tracking, activity monitoring, and leave management for your community. Perfect for student organizations, teams, moderation staff, and professional Discord servers.

---

## 🌟 Features

### 📊 **Comprehensive Attendance Tracking**
- **Start/End Attendance Sessions** - Track staff work shifts with precise timestamps
- **Automated Activity Monitoring** - Records messages, voice channel time, and more
- **Detailed Reports** - Auto-generated attendance reports with complete activity breakdown
- **Personal Statistics** - View your total shifts, hours worked, and averages

### 🎤 **Voice Channel Monitoring**
- **Time Tracking** - Precise tracking of time spent in voice channels
- **Channel Breakdown** - Per-channel VC time statistics
- **Mute/Unmute Detection** - Track muted time (self-mute vs server-mute)
- **Deafen Tracking** - Monitor deafened duration
- **Activity Metrics** - Mic toggle counts and channel switches

### 💬 **Message Activity Tracking**
- **Message Counting** - Count messages sent during attendance sessions
- **Channel Breakdown** - See message distribution across channels
- **Blacklist Support** - Exclude specific channels from tracking

### 🏖️ **Leave Management System**
- **Easy Leave Requests** - Staff can submit leave requests via interactive forms
- **Approval Workflow** - Admins can approve or reject requests with remarks
- **DM Notifications** - Instant updates on request status
- **Automatic Reminders** - Get notified 3 hours before leave ends

### 🎯 **Interactive Portals**
- **Custom Attendance Portals** - Create beautiful embeds with Start/End buttons
- **Button Integration** - Staff can manage attendance with one click
- **Compatible with Commands** - Works seamlessly alongside slash commands

---

## 🚀 Getting Started

### **For Server Administrators**

#### Initial Setup
1. **Invite Attendix** to your Discord server
2. **Set the Staff Role**
   ```
   /allowed-role @YourStaffRole
   ```
3. **Configure Report Channel**
   ```
   /attendance report-channel #attendance-reports
   ```
4. **Configure Leave Logs Channel**
   ```
   /leave logs #leave-requests
   ```

#### Optional: Create Attendance Portal
```
/attendance portal
```
Fill in the title and description to create an interactive attendance portal with buttons!

---

### **For Staff Members**

#### Starting Attendance
**Using Commands:**
```
/attendance start
```

**Using Portal:**
Click the **"Start Attendance"** button on your server's attendance portal.

#### Ending Attendance
**Using Commands:**
```
/attendance end
```

**Using Portal:**
Click the **"End Attendance"** button on the portal.

#### Checking Status
```
/attendance status
```
Shows if you have an active shift and current duration.

#### Viewing Your Statistics
```
/attendance my-report
```
See your total shifts, hours worked, VC time, and message counts.

#### Requesting Leave
```
/leave request
```
Fill in:
- Start Date (YYYY-MM-DD)
- End Date (YYYY-MM-DD)
- Reason for leave

Your request will be sent to admins for approval. You'll receive a DM with their decision!

---

## 📋 Command Reference

### **Staff Commands**
| Command | Description |
|---------|-------------|
| `/attendance start` | Begin your attendance shift |
| `/attendance end` | End your current shift and generate report |
| `/attendance status` | Check your current attendance status |
| `/attendance my-report` | View your personal statistics |
| `/leave request` | Submit a leave request |

### **Admin Commands**
| Command | Description |
|---------|-------------|
| `/allowed-role <role>` | Set the staff role |
| `/attendance report-channel <channel>` | Set where reports are sent |
| `/attendance portal` | Create interactive attendance portal |
| `/attendance session-details <id>` | View detailed session audit |
| `/leave logs <channel>` | Set leave request channel |
| `/blacklist add <channel>` | Exclude channel from tracking |
| `/blacklist remove <channel>` | Remove channel from blacklist |
| `/blacklist list` | View all blacklisted channels |

---

## 📊 What Gets Tracked?

During an active attendance session, Attendix monitors:

- ✅ **Total Duration** - Exact shift length
- ✅ **Messages Sent** - Per-channel message counts
- ✅ **Voice Channel Time** - Time spent in each VC
- ✅ **Muted Time** - Self-mute vs server-mute breakdown
- ✅ **Deafened Time** - Total time deafened
- ✅ **Mic Toggles** - Number of mute/unmute actions
- ✅ **Channel Switches** - VC channel changes

---

## 🔒 Privacy & Security

Attendix is designed with privacy in mind:
- **Only tracks during active sessions** - No monitoring when attendance is off
- **Server-specific data** - Your data stays within your server
- **Transparency** - Staff can view their own reports anytime
- **Admin controls** - Administrators control channel tracking settings

For full details, see our [Privacy Policy](https://github.com/demondevx/Attendix/blob/main/Privacy_Policy.md).

---

## 🏖️ Leave Request Workflow

1. **Staff Submits Request** → Uses `/leave request` command
2. **Posted to Admin Channel** → Request appears with Approve/Reject buttons
3. **Admin Reviews** → Approves or rejects with optional remarks
4. **Staff Notified** → Receives DM with decision
5. **Reminder Sent** → If approved, reminder sent 3 hours before leave ends

---

## 💡 Use Cases

### Perfect For:
- 📚 **Student Organizations** - Track officer hours and attendance
- 🎮 **Gaming Communities** - Monitor moderation team activity
- 💼 **Professional Servers** - Staff accountability and reporting
- 🛡️ **Moderation Teams** - Track moderator work sessions
- 👥 **Any Community** - Requiring attendance accountability

---

## 🛠️ Support

### Need Help?
We're here to help! Reach out through any of these channels:

- **Developer Contact:** [DemonDev on Discord](https://discord.com/users/555652788592443392)
- **Support Server:** [Join our Support Server](https://discord.gg/s2DGG38cmK)
- **Email:** [support@demondev.org](mailto:support@demondev.org)
- **Bug Reports:** Open an issue on GitHub
- **Feature Requests:** We'd love to hear your ideas!

---

## 📜 Legal

- [Privacy Policy](https://github.com/demondevx/Attendix/blob/main/Privacy_Policy.md)
- [Terms of Service](https://github.com/demondevx/Attendix/blob/main/TERMS_OF_SERVICE.md)

---

## 🎉 Quick Tips

- **Use Portals** - Interactive buttons make attendance easier for staff
- **Blacklist Spam Channels** - Exclude bot channels to keep reports clean
- **Check Statistics** - Use `/attendance my-report` to track your progress
- **Set Reminders** - Leave reminders help staff remember their return dates

## 🛡️ Strike & Discipline System (New)

The bot includes a fully automated strike management system to handle staff discipline fairly and consistently.

### Strike Commands

| Command | Description | Permissions |
| :--- | :--- | :--- |
| `/strike setup` | Interactive 5-step setup for channels, roles, and penalties. | Admin Only |
| `/strike issue` | Issue strikes to a user with a reason and quantity. | Admin/Staff |
| `/strike status` | View a detailed report of a user's active strikes. | Admin/Staff |
| `/strike remove` | Remove a specific number of strikes from a user. | Admin/Staff |
| `/strike reset` | Clear all strikes and reset a user's status to zero. | Admin/Staff |
| `/strike leaderboard` | View the top 10 members with active strikes. | Admin/Staff |

### Key Features
- **Automated Penalties**: Automatically triggers **Kicks** or **Demotions** (highest staff role removal) when a user reaches the strike threshold.
- **Auto-Reset**: Strikes are automatically cleared to zero once a penalty action is performed.
- **Strike Expiration**: Strikes automatically expire and are purged from the database after a configurable number of days (1, 3, 5, or 7 days).
- **Professional Analytics**: Detailed embeds showing who issued each strike, why, and when they will expire.
- **Hierarchy Awareness**: For demotions, the bot intelligently identifies and removes only the highest-ranking staff role configured in your setup.

---

## 📞 Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

- **Developer Contact:** [DemonDev on Discord](https://discord.com/users/555652788592443392)
- **Support Server:** [Join our Support Server](https://discord.gg/s2DGG38cmK)
- **Email:** [support@demondev.org](mailto:support@demondev.org)
- **GitHub Issues:** Open an issue on our repository
- **Server Administrator:** Contact your Discord server administrator for data-related requests

We will respond to your inquiry within a reasonable timeframe.

---

**Ready to bring professional attendance management to your Discord server? Let's get started! 🚀**
