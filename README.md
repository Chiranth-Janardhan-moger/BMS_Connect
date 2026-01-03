<div align="center">

# ConnectMe

### Smart College Bus Tracking System

Real-time bus tracking system built with React Native, Node.js, and MongoDB. Track college buses in real-time, get accurate ETAs, and never miss your bus again.

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)](https://socket.io/)
</div>

---

## Project Documentation

<div align="center">

[![View Complete Documentation](https://img.shields.io/badge/📄_Complete_Project_Report-PDF-red?style=for-the-badge&logo=adobeacrobatreader)](./Connect_ME.pdf)

**27-page comprehensive documentation covering system architecture, algorithms, security, performance analysis, and research contributions**

</div>

---

## Overview

ConnectMe is an intelligent real-time student transportation tracking system designed for college campuses. The system provides real-time bus tracking, accurate arrival predictions, and comprehensive analytics to improve the commuting experience for students, drivers, and administrators.

### Core Capabilities

<table>
<tr>
<td align="center" width="20%">
<b>Real-Time Tracking</b><br/>
Live bus location with high accuracy
</td>
<td align="center" width="20%">
<b>Smart Notifications</b><br/>
Bus arrival and emergency alerts
</td>
<td align="center" width="20%">
<b>Secure Communication</b><br/>
End-to-end encrypted chat
</td>
</tr>
</table>

---

## Video Demonstration

<div align="center">

### Watch ConnectMe in Action

<a href="https://youtu.be/YOUR_VIDEO_ID">
  <img src="./docs/images/video-thumbnail.png" alt="ConnectMe Demo Video" width="700">
</a>

[![Watch on YouTube](https://img.shields.io/badge/▶_Watch_Demo-YouTube-red?style=for-the-badge&logo=youtube)](https://youtu.be/YOUR_VIDEO_ID)

**Complete demonstration showing real-time tracking, offline mode, emergency alerts, and admin dashboard**

</div>

---

## Screenshots

<div align="center">

### Student Interface

<table>
<tr>
<td width="25%" align="center">
<img src="./docs/images/login.png" width="200"><br/>
<b>Login Screen</b><br/>
<sub>Secure authentication</sub>
</td>
<td width="25%" align="center">
<img src="./docs/images/map.png" width="200"><br/>
<b>Live Tracking</b><br/>
<sub>Real-time bus location</sub>
</td>
<td width="25%" align="center">
<img src="./docs/images/stops.png" width="200"><br/>
<b>Stop Information</b><br/>
<sub>ETA and schedule details</sub>
</td>
<td width="25%" align="center">
<img src="./docs/images/sos.png" width="200"><br/>
<b>Emergency SOS</b><br/>
<sub>Quick emergency alerts</sub>
</td>
</tr>
</table>

### Driver Interface

<table>
<tr>
<td align="center">
<img src="./docs/images/driver-dashboard.png" width="200"><br/>
<b>Driver Dashboard</b><br/>
<sub>Trip management controls</sub>
</td>
</tr>
</table>

### Admin Dashboard

<table>
<tr>
<td width="33%" align="center">
<img src="./docs/images/admin-fleet.png" width="250"><br/>
<b>Fleet Monitoring</b><br/>
<sub>Real-time bus tracking</sub>
</td>
<td width="33%" align="center">
<img src="./docs/images/admin-analytics.png" width="250"><br/>
<b>Analytics Dashboard</b><br/>
<sub>Performance metrics</sub>
</td>
<td width="33%" align="center">
<img src="./docs/images/admin-reports.png" width="250"><br/>
<b>Custom Reports</b><br/>
<sub>Detailed insights</sub>
</td>
</tr>
</table>

</div>

---

## Key Features

### For Students

<table>
<tr>
<td width="50%">

**Real-Time Tracking**
- Live bus location on interactive map
- Accurate ETA for each stop
- Complete route visualization
</td>
<td width="50%">

**Smart Notifications**
- Bus arrival alerts
- Schedule change updates
- Emergency notifications
- Customizable alert preferences

</td>
</tr>
<tr>
<td width="50%">

**Offline Support**
- View cached bus locations
- Access schedules without internet
- Automatic sync when online
- Predicted locations during network loss

</td>
<td width="50%">

**Safety Features**
- Emergency SOS alerts (Medical, Breakdown, Accident, Security)
- End-to-end encrypted chat with other Students
- Anonymous feedback system
- Real-time location sharing

</td>
</tr>
</table>

### For Drivers

<table>
<tr>
<td width="100%">

**Trip Management**
- One-touch trip start and end
- Automatic location updates
</td>
</tr>
</table>

### For Administrators

<table>
<tr>
<td width="50%">
  
**User Management**
- Add and remove students/drivers
- Role-based access control
</td>
<td width="50%">
  
**Communication**
- Broadcast notifications to all users
- Schedule change announcements
- Maintenance alerts
- Emergency coordination

</td>
</tr>
</table>

---

## Technology Stack

### Frontend
```
React Native 0.81.4
├── Expo Router (Navigation)
├── React Native Maps
├── Socket.IO Client
└── TypeScript
```

### Backend
```
Node.js 18+ / Express 5.1.0
├── Socket.IO Server (Real-time)
├── MongoDB (Database)
├── Redis (Caching)
├── JWT (Authentication)
└── TypeScript
```

### Infrastructure
```
├── Render.com (Backend Hosting)
├── MongoDB Atlas (Database)
├── Upstash Redis (Cache)
└── Cloudflare CDN (Assets)
```

---

## Installation Guide

### System Requirements

<table>
<tr>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/><br/>
<b>Node.js</b><br/>
v18.0.0 or higher
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/><br/>
<b>MongoDB</b><br/>
v5.0.0 or higher
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/><br/>
<b>Expo CLI</b><br/>
Latest version
</td>
<td align="center" width="25%">
<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git"/><br/>
<b>Git</b><br/>
Latest version
</td>
</tr>
</table>

### Backend Setup

**1. Clone the Repository**
```bash
git clone https://github.com/Chiranth-Janardhan-moger/Connect_Me.git
cd Connect_Me/backend
```

**2. Install Dependencies**
```bash
npm install
```

**3. Configure Environment**
```bash
cp .env.example .env
```

Edit `.env` with your configuration:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

**4. Start Development Server**
```bash
npm run dev
```

**5. Build for Production**
```bash
npm run build
npm start
```

## Building Mobile Apps

### Android APK

**1. Generate Android Files**
```bash
npx expo prebuild --platform android --clean
```

**2. Build Debug APK**
```bash
cd android
./gradlew assembleDebug
```

**3. Build Release APK**
```bash
./gradlew assembleRelease
```

The APK will be located at:
```
android/app/build/outputs/apk/release/app-release.apk
```

### iOS App

**1. Generate iOS Files**
```bash
npx expo prebuild --platform ios --clean
```

**2. Open Xcode Project**
```bash
cd ios
open ConnectMe.xcworkspace
```

**3. Build using Xcode**
- Select your development team
- Choose target device
- Product → Archive
- Follow distribution steps

---

## Contributors

### Core Team

<table>
<tr>
<td align="center">
<a href="https://github.com/Chiranth-Janardhan-moger">
<img src="https://github.com/Chiranth-Janardhan-moger.png" width="100px;" alt="Chiranth Janardhan Moger"/>
<br />
<sub><b>Chiranth Janardhan Moger</b></sub>
</a>
<br />
<sub>Project Lead & Full Stack Developer</sub>
</td>
<td align="center">
<a href="https://github.com/DivyashreeG7">
<img src="https://github.com/DivyashreeG7.png" width="100px;" alt="Divyashree"/>
<br />
<sub><b>Divyashree G</b></sub>
</a>
<br />
<sub>UI/UX Developer</sub>
</td>
<td align="center">
<a href="https://github.com/amoghar29">
<img src="https://github.com/amoghar29.png" width="100px;" alt="Amogha"/>
<br />
<sub><b>Amogha R</b></sub>
</a>
<br />
<sub>Backend Developer</sub>
</td>
  </td>
<td align="center">
<a href="https://github.com/rachana">
<img src="https://github.com/rachana.png" width="100px;" alt="Rachana"/>
<br />
<sub><b>Rachana C</b></sub>
</a>
<br />
<sub>Report & Research Paper</sub>
</td>
</tr>
</table>

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Support

For support, email chiranthmoger7@gmail.com or open an issue on GitHub.

---

<div align="center">

Made with ❤️ by the ConnectMe Team


[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/Chiranth-Janardhan-moger/BMS_Connect)

</div>
