<div align="center">
  <img src="https://docs.bridgefy.me/sdk/~gitbook/image?url=https%3A%2F%2F2522171645-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F5XKIMMP6VF2l9XuPV80l%252Flogo%252Fd78nQFIysoU2bbM5fYNP%252FGroup%25203367.png%3Falt%3Dmedia%26token%3Df83a642d-8a9a-411f-9ef4-d7189a4c5f0a&width=260&dpr=2&quality=100&sign=ba508359511330d6f95de32c3e596d18&sv=3" alt="Bridgefy Logo" width="200" style="margin-bottom: 20px;"/>
<p></p>
  <img src="https://docs.bridgefy.me/sdk/~gitbook/image?url=https%3A%2F%2F2522171645-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F5XKIMMP6VF2l9XuPV80l%252Fuploads%252FD0HSf0lWC4pWB4U7inIw%252Fharegit.jpg%3Falt%3Dmedia%26token%3Da400cf7d-3254-4afc-bed0-48f7d98205b0&width=768&dpr=2&quality=100&sign=a9c173a8dd88371bc2aba4a7cd4c1421&sv=3" alt="Bridgefy Logo" width="200" style="margin-bottom: 20px;"/>
    
  <h1>Bridgefy App: Community Network Research</h1>
  <p><b>Offline Communication • BLE Mesh Routing • Telemetry Project</b></p>

  [![Status: Community Beta](https://img.shields.io/badge/Status-Community_Beta-success?style=for-the-badge)](https://github.com/bridgefy/bridgefy-app/releases)
  [![Platform: Android](https://img.shields.io/badge/Platform-Android_APK-E23828?style=for-the-badge&logo=android)](https://github.com/bridgefy/bridgefy-app/releases)
  [![Privacy: Strict](https://img.shields.io/badge/Privacy-Strict-blue?style=for-the-badge&logo=shield)](PRIVATE)
  
  <br>
  <a href="https://bridgefy.me">🌐 Official Website</a> • 
  <a href="https://github.com/bridgefy">💻 GitHub Repository</a>
</div>

---

## 🌍 Global Impact & Purpose

This repository hosts the Android application for our **community-driven network research initiative**. Bridgefy's core technology has a proven track record of helping people stay connected when traditional networks fail.

> **Trusted by over 3 million users globally**, Bridgefy's offline messaging technology has been utilized during natural disasters, large-scale music festivals, and humanitarian crises. Our technology is recognized by global organizations for facilitating critical communication when Wi-Fi and cellular networks are down.

By using this application, you are directly contributing to network research. We collect essential telemetry (crash logs and routing metrics) to optimize decentralized communication algorithms for future crisis response.

---

## 📡 Technology: Multi-Hop BLE Mesh

The application relies on a decentralized, multi-hop network architecture. Instead of connecting to a cell tower, devices connect directly to one another using **Bluetooth Low Energy (BLE)**.

```mermaid
graph LR
    A((Sender)) -.->|Packet| B((Node 1))
    A -.-> C((Node 2))
    B -.-> D((Node 3))
    B -.-> F((Node 4))
    C -.-> D
    F -.-> E
    D -.->|Packet| E((Recipient))
    
    style A fill:#E23828,stroke:#B71C1C,stroke-width:2px,color:#fff
    style E fill:#E23828,stroke:#B71C1C,stroke-width:2px,color:#fff
    style B fill:#1e293b,stroke:#64748b,stroke-dasharray: 5 5,color:#fff
    style C fill:#1e293b,stroke:#64748b,stroke-dasharray: 5 5,color:#fff
    style D fill:#1e293b,stroke:#64748b,stroke-dasharray: 5 5,color:#fff
    style F fill:#1e293b,stroke:#64748b,stroke-dasharray: 5 5,color:#fff
```

### Routing Modes
1. **Peer-to-Peer (P2P):** Direct connection up to 100 meters (330 ft).
2. **Mesh Network:** Data securely jumps across intermediate devices.
3. **Broadcast:** Untargeted transmission to all surrounding users.
4. **Store & Forward:** Packets are held securely in memory until you walk within range of another node.

---

## ❓ Frequently Asked Questions (FAQ)

*(Click on a question to reveal the answer)*

<details>
  <summary><b>How do I connect to the network using Bluetooth?</b></summary>
  <p>Simply enable Bluetooth on your device settings and open the Bridgefy application. The app handles discovery and mesh connection automatically in the background. You do not need to manually pair with other devices in your OS settings.</p>
</details>

<details>
  <summary><b>What if I don't see anyone nearby?</b></summary>
  <p>If no one is immediately around you, your message is not lost. The app uses a <b>Store & Forward</b> feature. It will securely hold your message in memory and automatically deliver it as soon as you, or another user carrying your packet, walks into range of the recipient or the broader mesh.</p>
</details>

<details>
  <summary><b>Why does the app explicitly require "Location" permissions?</b></summary>
  <p>This is a strict system requirement imposed by the Android OS. To scan for nearby Bluetooth Low Energy (BLE) devices and advertise your presence to the mesh, Android mandates that Location Services be enabled and permitted. <b>We do not track, collect, store, or transmit your GPS coordinates.</b> This permission is used exclusively for Bluetooth functionality.</p>
</details>

<details>
  <summary><b>Do I need Wi-Fi or Cellular Data at any point?</b></summary>
  <p>You only need an internet connection to download the app initially. Once installed, the app runs entirely offline via Bluetooth.</p>
</details>

---

## ⚖️ Legal & Compliance Disclaimer

> ⚠️ **IMPORTANT NOTICE FOR ALL USERS**

* **User Responsibility for Content:** Bridgefy acts solely as a decentralized transport layer (a digital courier). All content, messages, and data transmitted through the application are generated entirely by users. We have no access to, nor do we monitor, moderate, or control user-generated content.
* **Local Laws and Regulations:** The use of decentralized communication networks, mesh routing, or encrypted messaging may be restricted or illegal in certain jurisdictions. It is your sole responsibility to ensure compliance with all applicable local, state, and national telecommunications laws before using this application.
* **Not for Emergencies:** This software is provided for research and experimental purposes. It is provided "as is" and should **not** be relied upon as a primary or sole means of communication in life-threatening emergencies or critical situations.

---
<p align="center">
  <i>Built for the network research community.</i>
</p>
