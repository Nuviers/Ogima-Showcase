# Ogima - Native Android Social Network (Java)

> 🇧🇷 **Leia este arquivo em Português [clicando aqui](./README.pt-br.md).**

**Ogima** is a native social media application developed in Java. As my first major project, it represents 3 years of deep study and practical application of Android development, Firebase integration, and complex programming logic.

> **Status:** Portfolio Project / Updated for Android SDK 31+

---

## 📺 Demonstration

Watch the system in operation (Chat, Feed, and Profile dynamics):

[**Full App Demonstration (YouTube)**](https://youtu.be/ARD69cdaoqw)

---

## 📱 Core Features & Engineering

The focus was on building a fully functional social ecosystem with real-world technical solutions.

### 1. Algorithmic Personalized Feed
Implemented retrieval logic to avoid simple random sorting:
- **Interest Mapping:** Fetches user-defined interests from the database.
- **Multithreaded Queries:** Executes independent Firebase searches for each interest.
- **Data Merging:** Aggregates and shuffles results for a dynamic and varied UX.

### 2. Real-Time Chat Infrastructure
Low-latency messaging system built for data integrity.
- **Time Synchronization:** Implemented **NTP (Network Time Protocol)** verification to prevent sequencing errors caused by incorrect local device clocks.
- **Database Optimization:** Decoupled "Messages" from "Conversation Metadata" for faster loading states.

### 3. Maintenance & Modernization
Critical system updates performed in 2025:
- **Dependency Migration:** Replaced deprecated JCenter libraries with local binary targets (`.aar`) to restore system compilability.
- **Sync Debugging:** Resolved race conditions between database listeners and UI threads for a consistent cold-start experience.

### 4. In-App Economy & Gamification
Integrated a monetization loop:
- **Reward System:** Users earn virtual currency by watching ads (AdMob).
- **Premium Features:** Implementation of a "Blurred Profile" feature accessible only through the in-app economy.

---

## 🛠 Tech Stack

- **Primary Language:** Java
- **Real-time Backend:** Firebase Realtime Database
- **Authentication:** Firebase Auth (Email/Pass & Google)
- **Core Libraries:** 
  - `Glide` (Image Processing)
  - `Retrofit` (HTTP Requests)
  - `ExoPlayer` (Video Engine)
  - `MediaRecorder` (Native Audio Capture)

---

## 📸 Project Gallery

### Onboarding & Authentication
| Welcome Screen | Secure Login | Registration |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/d31c02c9-87be-4874-b263-d345a96b9f19" width="200"> | <img src="https://github.com/user-attachments/assets/8eb689c6-8b67-4f7a-a83a-6a4c74dd9f73" width="200"> | <img src="https://github.com/user-attachments/assets/7a2a8da4-21b1-4d7f-8239-9654431d10a6" width="200"> |

### Profile & Identity
| User Profile | UI Customization | Interests Mapping |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/0da16701-7bfe-496f-9435-1162e95e4b27" width="200"> | <img src="https://github.com/user-attachments/assets/b156673d-2a22-41ec-bef6-78d0e6f6602b" width="200"> | <img src="https://github.com/user-attachments/assets/a2542100-3484-474e-b066-6814f380c9c7" width="200"> |

### Social Dynamics
| Main Feed | Post Architecture | Image Processing |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/9d1d4e02-4a0f-485e-b9b0-1aa5afb17c98" width="200"> | <img src="https://github.com/user-attachments/assets/3b59f7f7-f1b5-475c-beba-22b5a590e009" width="200"> | <img src="https://github.com/user-attachments/assets/e452c70c-d87c-4819-9ca6-10fd191e12ad" width="200"> |

### Communication & Groups
| Conversation List | Media-Rich Chat | Community Hub |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/ceabf74c-e87c-48fc-b54e-c9599eccf00d" width="200"> | <img src="https://github.com/user-attachments/assets/bbbbd03a-6939-4c52-885b-b958dbea0bd1" width="200"> | <img src="https://github.com/user-attachments/assets/0c4d9829-bc28-436f-b46c-9f84829fefd1" width="200"> |

### Advanced Components
| Profile Blur Logic | Native QR Engine | GIF Engine Support |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/8aa86380-adbd-4b5d-94f0-4b27d03eff93" width="200"> | <img src="https://github.com/user-attachments/assets/032743f9-8411-44f5-9212-54ac7694d97e" width="200"> | <img src="https://github.com/user-attachments/assets/5881dd0f-04fc-4e1f-b389-38bea49413e0" width="200"> |

---

Developed by Rafael Benedet Fernandes
