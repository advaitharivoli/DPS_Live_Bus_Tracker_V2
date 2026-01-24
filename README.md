# 🚌 LIVE BUS TRACKER V2 (Smart Transport Hub)

A modern, high-performance web application designed for real-time school transport management. This system provides a seamless experience for students, parents, and transport coordinators with a focus on aesthetics, speed, and usability.

## ✨ Key Features

### 🖥️ 1. Multi-Mode Interface
The application features three distinct operational modes:
*   **Standard Display Mode (S-Series)**: A public-facing board for regular routes (S01-S35). Features an auto-scrolling terminal view.
*   **Stayback Mode (E-Series)**: A dedicated view for stayback/late buses (E01-E10).
*   **Secure Input Mode**: An admin-only interface for updating live status.

### 📱 2. Mobile-First & Responsive
*   **Smart Detection**: Automatically detects mobile devices and switches to a "Phone-Optimized" layout.
*   **Admin Focused**: On mobile, the public display boards are hidden to focus purely on quick status updates.
*   **colorful Theme**: Mobile view features a vibrant, high-contrast gradient theme for better outdoor visibility.

### 🔔 3. Smart Notification System
*   **Toast Notifications**: Non-intrusive, sleek notifications appear in the top-right corner for 12 seconds when a status changes.
*   **Context-Aware Messages**:
    *   **Location Updates**: "MOVED TO [LOCATION]"
    *   **Departure Alerts**: "TRIP STARTED • ON ROAD" (with Rocket Icon 🚀)
*   **Auto-Debouncing**: If a bus updates twice quickly (e.g. correcting a mistake), the old notification is instantly replaced by the new one to prevent clutter.

### 🎨 4. Premium Aesthetics (Glassmorphism)
*   **Visual Status Indicators**:
    *   🟢 **Bus Bay**: Neon Green Glow
    *   🟡 **In Dock / Waiting**: Amber Pulse Animation
    *   🔵 **Gate 4**: Electric Blue
    *   🟠 **Auditorium**: Vibrant Orange
*   **Dynamic Speed Scrolling**: The display board automatically calculates scrolling speed based on the number of buses, ensuring lists of all sizes flow smoothly.

### 🔒 5. Security & Auth
*   **Inline Feedback**: No annoying pop-up alerts. Errors like "INCORRECT CREDENTIALS" appear as smooth inline animations.
*   **Session Management**: Secure PIN-based access (Default: `1234`) for authorized personnel only.

---

## 🛠️ Technical Stack
*   **Frontend**: HTML5, Vanilla CSS3 (Advanced Animations), ES6 JavaScript.
*   **State Management**: `localStorage` with `Event Listeners` for cross-tab synchronization.
*   **Design System**: Custom "Outfit" & "JetBrains Mono" typography with Glassmorphism UI components.

## 🚀 How to Use / Deploy
1.  **Host**: Can be hosted on GitHub Pages, Vercel, or any static site host.
2.  **Access**:
    *   Open on a large screen for **Display Board**.
    *   Open on a phone for **Controller**.
3.  **Sync**: Updates made on the phone (Controller) instantly reflect on the Display Board (if on the same browser session/local network simulation).

---

> **Note**: This is a frontend-only demonstration. For global internet syncing, a backend service (Firebase/Supabase) is recommended.

**Made by A.Advaith 7P**