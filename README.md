# 🛡️ Cyber Security Confessions

<!-- Badges Section -->
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://cyber-confesions.vercel.app/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Uses LocalStorage](https://img.shields.io/badge/Storage-LocalStorage-yellow)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
[![Email Relay](https://img.shields.io/badge/Email-FormSubmit-blueviolet)](https://formsubmit.co/)

## 🌐 Live Demo

Experience the application live: [Cyber Security Confessions](https://cyber-confesions.vercel.app/)

## 📝 Overview

**Cyber Security Confessions** is an anonymous, web-based platform where security professionals can share their most candid stories. From accidental data leaks and configuration blunders to hard-earned lessons, this space allows for uncensored truth-telling without fear of judgment.

Built with a pure frontend stack, the app uses browser `localStorage` for persistence and a simple email relay to deliver submissions. It serves as a realistic, mock-backend environment and a great example of integrating third-party services without a dedicated server.

## ✨ Key Features

*   **Anonymous Submissions:** No tracking, no login, no personal data stored.
*   **Confession Feed:** View a live-updating list of the latest "confessions" from the community.
*   **Role & Tagging:** Submissions can include optional roles and tags for context.
*   **Email Integration:** Each new confession is automatically forwarded via **FormSubmit** to a specified email address (configurable).
*   **Persistent Storage:** All confessions are saved in the browser's `localStorage`, ensuring data persists through page refreshes.
*   **Fully Responsive:** A sleek, mobile-friendly design with a dark theme optimized for readability.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Styling:** Custom CSS with Glassmorphism and modern gradients
*   **Persistence:** Browser `localStorage` API
*   **Email Service:** [FormSubmit](https://formsubmit.co/) (email relay)
*   **Deployment:** [Vercel](https://vercel.com/)

## 🚀 Getting Started

To run this project locally, follow these simple steps:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/bishalde/cyber-confessions.git
    cd cyber-confessions
