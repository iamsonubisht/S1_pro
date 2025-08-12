# 🏙️ Smart City Platform

[![Live Demo -SOON]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#license)
![Node.js](https://img.shields.io/badge/Node.js-18.x-green?style=for-the-badge&logo=node.js)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react)
![MongoDB](https://img.shields.io/badge/MongoDB-6.x-47A248?style=for-the-badge&logo=mongodb)

---

## 📸 Screenshots

### Citizen Interface
![Citizen Dashboard](docs/screenshots/citizen-dashboard.png)

### Admin Panel
![Admin Dashboard](docs/screenshots/admin-dashboard.png)

---

## 📖 Overview

The **Smart City Platform** is a full-stack application that allows citizens to **report civic issues**, track their **real-time status**, and interact via an **AI-powered chatbot**.  
It includes:
- **Frontend:** React + Vite + Tailwind CSS
- **Backend:** Node.js + Express + MongoDB
- **Admin Panel:** For managing and updating reported issues

---

## ✨ Features

- **📢 Report Issues** – Road damage, water leakage, garbage collection, and more.
- **📊 Track Progress** – Real-time status updates.
- **💬 Feedback System** – Rate and comment on issue resolution.
- **🛠️ Admin Panel** – Manage and update reports.
- **🤖 AI Chatbot** – Integrated OpenAI GPT API for instant assistance.
- **📷 Image Uploads** – Powered by Cloudinary.

---

## 🛠️ Tech Stack

| Layer        | Technologies |
|--------------|-------------|
| **Frontend** | React, Vite, Tailwind CSS, Redux, React Router |
| **Backend**  | Node.js, Express, Mongoose, JWT |
| **Database** | MongoDB |
| **Cloud**    | Cloudinary |
| **AI**       | OpenAI API |
| **HTTP**     | Axios |

---

## 🔄 How It Works

```mermaid
flowchart TD
    A[Citizen Reports Issue] --> B[Backend API - Node.js/Express]
    B --> C[MongoDB Stores Data]
    C --> D[Admin Panel - Manage Issues]
    D --> E[Status Updated in DB]
    E --> F[Citizen Sees Real-Time Update]
    A --> G[Uploads Image to Cloudinary]
    A --> H[Chats with AI Chatbot via OpenAI API]

