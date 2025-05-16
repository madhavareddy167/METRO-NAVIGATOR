<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0e5e6f&height=200&section=header&text=Metro%20Navigator&fontColor=ffffff&fontSize=32&fontAlignY=40&desc=Real-Time%20Metro%20Route%20Planner%20using%20Dijkstra's%20Algorithm&descSize=16&descAlign=50" />
</p>

<p align="center">
  <a href="#"><img alt="Built with Django" src="https://img.shields.io/badge/Built%20with-Django-0e5e6f?style=for-the-badge&logo=django"></a>
  <a href="#"><img alt="Dockerized" src="https://img.shields.io/badge/Dockerized-Yes-2496ED?style=for-the-badge&logo=docker"></a>
  <a href="#"><img alt="MIT License" src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"></a>
</p>

---

# 🚇 Metro Navigator – Real-Time Metro Route Planner

MetroNavigator-WebApp is a **Django-based full-stack application** designed to visualize metro routes and optimize journey planning using **Dijkstra’s algorithm**. It enables users to find the shortest route, nearest stations, expected departure times, and interchanges through a rich and responsive UI.

---

## 📸 UI Snapshots

<p align="center">
  <img src="images/main.jpg" width="220" />
  <img src="images/main2.jpg" width="220" />
  <img src="images/pop.jpg" width="220" />
</p>
<p align="center">
  <img src="images/ui1.jpg" width="220" />
  <img src="images/ui2.jpg" width="220" />
  <img src="images/ui3.jpg" width="220" />
</p>

---

## 📚 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Running the Application](#running-the-application)
- [Manual Execution (Without Docker)](#manual-execution-without-docker)
- [Why Docker?](#why-docker)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- 🔄 Real-time metro route & schedule information
- 🧭 Dijkstra’s algorithm for optimal route calculation
- 📍 Locate the nearest metro station from your location
- 🧠 Smart interchange recommendations with travel summary
- 🎨 Material Design UI for smooth, intuitive interaction
- 📱 Responsive design compatible across devices
- 🔐 HTTPS enabled via self-signed SSL certificates

---

## 🛠️ Technologies Used

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, JavaScript
- **Algorithm & Graphs:** Dijkstra's Algorithm, NetworkX, Matplotlib
- **Deployment:** Docker, Docker Compose
- **Security:** OpenSSL for certificate generation

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.x
- Docker
- Docker Compose

### 📥 Clone the Repository

```bash
git clone https://github.com/your-username/MetroNavigator-WebApp.git
cd MetroNavigator-WebApp
