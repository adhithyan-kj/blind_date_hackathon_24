# VitaFlow - AI-Powered Blood Donation Assistant

**VitaFlow** is a modern, all-in-one web application designed to streamline the process of blood donation and requests. It leverages AI to create a smart, responsive, and user-friendly platform that connects donors with recipients efficiently. Built with a clean, Google-inspired UI, it offers a seamless experience for users in need and those willing to help.

This project is built as a single-page application, containing all necessary HTML, CSS, and JavaScript in one file for easy deployment and portability.

---

## ✨ Key Features

- **Smart Donor Matching:** Users can request blood by type and location. The system intelligently finds the best-matched, eligible donors from the local database.
- **AI Health Assistant:** A built-in chatbot powered by the Google Gemini API assists users with eligibility questions, health tips, and guides them through the app.
- **Interactive Donor Map:** A real-time map, built with LeafletJS, visualizes the approximate locations of registered donors, making it easy to see nearby help.
- **Email Notifications:** When a blood request is made, an automated email is sent to a designated administrator using EmailJS.
- **User Registration & Dashboard:** Users can register as donors, creating a profile that tracks their donation history, calculates lives saved, and shows their next eligibility date.
- **Gamification & Badges:** To encourage donations, the user dashboard includes a badge system that rewards donors for milestones (e.g., "First Drop," "Life Saver").
- **Emergency Alert Mode:** A high-visibility emergency button for urgent requests, designed to quickly broadcast the need.
- **Predictive Demand Heatmap:** A visual representation of blood demand in different cities to raise awareness about potential shortages.
- **Voice-Enabled Chat:** Users can interact with the AI assistant using their voice for hands-free and accessible communication.
- **Multi-Language Support:** The AI assistant can understand and respond in multiple languages based on user selection.
- **Fully Responsive:** The UI is designed to work flawlessly on desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack

**Frontend:** HTML5, Tailwind CSS, JavaScript (ES Modules)  

**APIs & Libraries:**
- **Google Gemini API:** For the intelligent AI chatbot.
- **EmailJS:** To handle client-side email notifications without a backend.

**Storage:** Browser Local Storage is used for session persistence and storing user/donor data.

---

## 🚀 Getting Started

This application is designed to run directly in any modern web browser without needing a complex setup or a backend server.

### Prerequisites
You will need API keys and credentials for the following services:

- **Google Gemini API:** To power the AI chat assistant.
- **EmailJS:** To enable email notifications. You'll need a Public Key, Service ID, and Template ID.

### Configuration

1. Clone the repository or download the files.
2. Open `index.html` in your code editor.

