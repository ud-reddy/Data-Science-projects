
# Athena & UniLeeds Project Hub

[![System Status](https://img.shields.io/badge/System-Active-success?style=for-the-badge)](https://github.com/)
[![Web App](https://img.shields.io/badge/Platform-Athena_Web-blue?style=for-the-badge)](https://athena.leeds.ac.uk)
[![Mobile App](https://img.shields.io/badge/Platform-UniLeeds_Mobile-orange?style=for-the-badge)](https://mobile.leeds.ac.uk)

A synchronized ecosystem for University of Leeds students, integrating comprehensive academic management with rapid mobile access.

---

## 🏛️ Project Overview

This repository contains the source code and architecture for the dual-interface student management system. **Athena** serves as the central hub for long-form academic tasks, while the **UniLeeds Mobile App** provides on-the-go utility for daily campus life.

### 🌐 Athena Web Portal
Athena is the desktop-first website that students use for "everything university." 
- **Academic Records:** View grades, transcripts, and official documents.
- **Module Management:** Enroll in modules and access learning materials (VLE integration).
- **Finances:** Pay tuition fees and manage student accounts.
- **Personal Information:** Update contact details and student status.

### 📱 UniLeeds Mobile App
The mobile companion designed for quick, high-frequency university activities.
- **Attendance Scanner:** Built-in QR scanner to register for lectures instantly.
- **Smart Timetable:** Real-time synchronized schedule with push notifications.
- **Campus Maps:** Integrated navigation for lecture theaters and labs.
- **Digital ID:** Mobile-first student identification for library access.

---

## 🏗️ System Architecture

The most critical component of this ecosystem is the **Shared Central Database**, which ensures a seamless flow of data. When a student scans their attendance on the UniLeeds App, the record is immediately visible on the Athena portal for staff and students to verify.

![Architecture Diagram Placeholder](https://picsum.photos/800/400?grayscale)

> *Figure 1: High-level data flow showing the bi-directional connectivity between the Core Database, Athena Web, and UniLeeds Mobile.*

---

## 🛠️ Tech Stack

- **Frontend (Web):** React 18, TypeScript, Tailwind CSS
- **Frontend (Mobile):** React Native, Expo
- **Backend:** Node.js, Express, Prisma ORM
- **Database:** PostgreSQL (Centralized instance)
- **Infrastructure:** AWS (RDS, S3 for student documents)

---

## 🖼️ User Interface Preview

| Athena (Web Portal) | UniLeeds (Mobile App) |
| :---: | :---: |
| ![Athena Placeholder](https://picsum.photos/400/250) | ![Mobile Placeholder](https://picsum.photos/200/350) |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- PostgreSQL instance
- Expo CLI (for mobile development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/uni-leeds/athena-unileeds.git
   cd athena-unileeds
   ```

2. Install dependencies for all workspace packages:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   # Update DATABASE_URL and API_KEYS
   ```

4. Run the development environment:
   ```bash
   # Start Web
   npm run dev:web

   # Start Mobile
   npm run dev:mobile
   ```

---

## 🔗 Useful Links
- [University of Leeds Official](https://leeds.ac.uk)
- [Athena Support Portal](https://athena.leeds.ac.uk/help)
- [API Documentation](https://api.leeds.ac.uk/docs)

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
  
