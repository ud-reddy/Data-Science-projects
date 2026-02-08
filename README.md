# 🏛️ Athena  
### A Rebooted Digital Experience for University of Leeds Students

Athena is a **modern reboot of the University of Leeds’ Minerva platform**, alongside a reimagined UniLeeds mobile app.  
It enhances usability, security, and engagement while preserving all essential university services students rely on.

> ⚠️ This project is a **conceptual and academic prototype** and is **not** an official University of Leeds product.

---

## ✨ Key Highlights

- 🔐 **Secure, location-verified attendance**
- 📊 **Real-time attendance dashboard**
- 🎮 **Gamified learning experience**
- 🌙 **Modern UI with dark mode**
- 🔄 **Bi-directional web & mobile sync**

---

## 🧠 System Architecture

### High-Level Bi-Directional Data Flow

The Athena ecosystem is built around a **central core database** that synchronizes data between the web platform and the mobile app in real time.

![High-Level Bi-Directional Data Flow Architecture](./assets/architecture.png)

**How it works:**
- Athena Web and the UniLeeds Mobile App both communicate with the core database
- Data such as course content, user profiles, and attendance updates are synced bi-directionally
- Push notifications and offline sync requests are handled efficiently
- The database acts as the single source of truth

---

## 🖥️ Athena Web Platform (Minerva Reboot)

Athena replaces the traditional Minerva website with a modern, student-first design.

### Features
- Access to all university services
- Lecture schedules and module information
- Centralised academic resources
- Attendance analytics dashboard
- Clean, responsive interface
- Dark mode support 🌙

![Athena Web Dashboard](./assets/web-dashboard.png)

---

## 📱 UniLeeds Mobile App (Rebooted)

The mobile application mirrors Athena’s functionality while enhancing mobility and accessibility.

### Features
- QR-based lecture attendance
- Real-time sync with Athena Web
- Notifications for lectures, deadlines, and updates
- Offline data access and syncing
- Improved UI and performance

![UniLeeds Mobile App](./assets/mobile-app.png)

---

## 🔐 Enhanced Attendance System

Athena improves the existing QR code attendance system by adding an **extra security layer**.

### How Attendance Works
1. QR code is scanned in the lecture hall
2. The app captures the student’s real-time location
3. Attendance is recorded **only if the student is physically present**
4. Attendance data syncs instantly with the Athena dashboard

This prevents:
- Remote check-ins
- QR code sharing
- False attendance records

![Secure Attendance Flow](./assets/attendance-flow.png)

---

## 📊 Attendance Dashboard

Students can track their engagement through a dedicated dashboard:

- Attendance per module
- Weekly and overall attendance trends
- Clear visual indicators
- Improved academic accountability

![Attendance Dashboard](./assets/attendance-dashboard.png)

---

## 🎮 Gamified Learning Experience

Athena introduces a learning platform that feels more like a game than a static portal.

- Progress tracking
- Engagement-driven design
- Motivation through visual feedback
- Encourages consistent participation

![Gamified Learning Interface](./assets/gamified-learning.png)

---

## 🎯 Project Goals

- Improve attendance reliability
- Increase student engagement
- Modernize university digital tools
- Preserve familiarity while enhancing usability
- Reduce misuse of attendance systems

---

## 🛠️ Technologies Used

> *(Adjust based on your actual implementation)*

- **Frontend:** HTML, CSS, JavaScript / React
- **Backend:** Node.js, REST APIs
- **Mobile:** Cross-platform framework
- **Database:** Centralised core database
- **Location Services:** GPS-based verification
- **Authentication:** University login integration

---

## 🚀 Future Enhancements

- Lecturer analytics dashboard
- Push notifications for deadlines & attendance warnings
- Advanced gamification (badges, streaks, leaderboards)
- Accessibility improvements
- Offline lecture content access

---

## 🏺 Why “Athena”?

Athena, the Greek goddess of **wisdom and knowledge**, symbolizes intelligence, learning, and strategic thinking — perfectly reflecting the project’s academic mission.

---

## 📄 Disclaimer

This project is a **student-led concept** and is **not affiliated with or endorsed by the University of Leeds**.

---

