# 🎨 Collaborative Drawing Board App

An advanced **real-time collaborative platform** that merges creativity and communication through 
shared drawing spaces and live chats — available on both **web** and **mobile**. Whether you're brainstorming ideas, 
hosting a design jam, or just having fun with friends, this platform ensures a smooth and intuitive experience across devices.

![WhatsApp Image 2025-07-15 at 2 18 07 AM](https://github.com/user-attachments/assets/a5530044-eb44-42cb-97eb-3f9a2a07ee27)



## 🌍 Platform Overview

- 🌐 **Web Application**: Developed using **Next.js** for blazing-fast performance, SSR support, and optimized routing.
- 📱 **Mobile Application**: Built with **React Native + Expo** for smooth, responsive drawing and chatting on the go.

Both platforms are fully integrated with **real-time drawing**, **community-based collaboration**, **chat features**, and 
**live updates** powered by **WebSockets** and **concurrency control** logic.

---

## 🚀 Features at a Glance

### 🎨 Real-time Drawing & Canvas Tools
- Multiple users can draw on the same canvas simultaneously.
- Each drawing action syncs **instantly across all devices**.
- Supports pencil, eraser, color picker, and more.

### 🧩 Drawing Movement
- Users can **select and move** any drawn object anywhere on the canvas.
- All movements are reflected in real-time to others.

### 🧠 Concurrency Control
- Designed to handle multiple users drawing and interacting at once.
- Prevents conflicts and ensures **smooth user coordination** using locking and syncing logic.

### 👥 Community & Board System
- Users can **create and join communities**.
- Each community can host **multiple drawing boards**.
- Ideal for teams, students, designers, and hobbyists.

### 💬 Built-in Real-time Chat
- Instant messaging alongside the drawing canvas.
- Helps users communicate and collaborate during sessions.

### 🔐 Authentication & User Sessions
- Secure login and registration with persistent sessions.
- Role-based access (Admin, Member) support in future scope.

### 🌈 Cross-Platform UI
- Responsive, modern UI design tailored for both desktop and mobile devices.
- Smooth user experience across browsers and mobile phones.

---

## 🛠️ Technology Stack

### 🌐 Web Application
Built using **Next.js** for fast performance and server-side rendering. The UI is styled with **Tailwind CSS**,
drawing functionality is implemented using the native **Canvas API** for a smooth creative experience.

### 📱 Mobile Application
Developed with **React Native** and **Expo** for cross-platform compatibility. **React Navigation** is used to manage screen flows, ensuring a seamless experience on both Android and iOS devices.

### ⚙️ Backend Server
Powered by **Node.js** and **Express.js**, responsible for handling APIs, user authentication, real-time socket communication, and community/board logic.

### 🔄 Real-time Communication
Real-time drawing, movement, and chat are enabled through **Socket.IO**, providing instant updates via WebSockets across all connected users.

### 💾 Database
Supports **Firebase Firestore** for scalable and secure data storage, depending on deployment preference.

### 🔐 Authentication
Handled via **Firebase Authentication** or **JWT (JSON Web Tokens)** to ensure secure login, registration, and session management.

### 🔧 State Management
Uses **Redux**  to efficiently manage application-wide state and real-time data synchronization.

### ☁️ Deployment & Hosting
- **Web**: Hosted on **Vercel**
- **Mobile**: Delivered through **Expo Go** and **EAS Build**
- **Backend**: Deployed on **Render**


## 📬 Contact

If you have any questions, suggestions, or would like to connect — feel free to reach out!

- 📧 Email: [mijlalatif10@gmail.com](mailto:mijlalatif10@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/ijlalatif]([https://www.linkedin.com/in/ijlalatif](https://www.linkedin.com/in/ijlal-atif-8782351b2/))




