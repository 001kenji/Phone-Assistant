# 🎙️ Kenji Assistant - AI Voice Assistant for Android

[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)

Your intelligent voice assistant that transforms how you interact with your Android device. Control everything with simple voice commands - no touching required!

> **Note**: This repository contains project documentation and information. Source code is proprietary and not publicly available.

---

## ✨ Key Features

### 🗣️ Smart Messaging
- **Send SMS** to contacts by name
- **WhatsApp messaging** - message contacts directly
- **Email composition** with voice commands
- **Read notifications** aloud

### 🔔 Smart Notification System
- **Notification reading** - Hear your alerts without looking at your phone
- **App-specific filtering** - WhatsApp, Messenger, SMS, Email, and more
- **Intelligent prioritization** - Important messages get read first
- **Sender identification** - Know who's messaging you immediately
- **Auto-announcement** - Incoming messages read aloud when appropriate
- **Privacy controls** - Choose which apps can read notifications

**Try saying:** *"Read my notifications"* or *"What are my latest messages?"* or *"Read messages from WhatsApp"*

**Supported Apps:**
- 📱 **WhatsApp** - Message previews with sender names
- 💬 **Messenger** - Facebook message announcements  
- 📨 **SMS** - Text message reading
- 📧 **Email** - Gmail and email client notifications
- 🔔 **All Apps** - General notification access

**Privacy Features:**
- Notification access requires explicit user permission
- You control which apps can be read
- Sensitive content can be filtered
- Announcement cooldown prevents spam

**Try saying:** *"Send SMS to John: I'm on my way"* or *"WhatsApp Sarah: Meeting at 3 PM"*

### 🔍 Intelligent App Search
- **Search within apps** - Kilimall, Jumia, YouTube, Maps
- **Voice-controlled browsing** 
- **Automatic fallback** to web when apps aren't installed
- **Direct app opening** with search queries

**Try saying:** *"Search for laptops in Kilimall"* or *"Find restaurants near me on Maps"*

### 🗺️ Distance & Navigation
- **Calculate distances** to any location
- **Navigation commands** with different travel modes
- **Real-time distance** calculations
- **Location-based services**

**Try saying:** *"How far is Nairobi city center?"* or *"Navigate to the nearest supermarket"*

### 📸 Text Scanner
- **Camera text recognition** from documents and signs
- **Real-time OCR** processing
- **Multi-language support** with translation
- **Text-to-speech** for scanned content

**Try saying:** *"Hey Joe, scan this document"* or *"Read text from this sign"*

### ⚡ Quick Actions
- **Open any app** by name
- **Play music** and media
- **Make phone calls** to contacts
- **Set alarms and reminders**
- **Control device functions**

**Try saying:** *"Play song Starboy"* or *"Call mom"* or *"Open YouTube"*

### 🎛️ System Control
- **Camera control** with different modes
- **Music playback** management
- **Contact browsing** and management
- **Calendar access** and event creation
- **Notes and reminders**

---

## 🛠️ Technical Features

### Voice Recognition
- **Wake word detection** ("Hey Joe")
- **Continuous conversation** mode
- **Background listening** with privacy controls
- **Multi-language support**

### Privacy & Security
- **Local processing** whenever possible
- **Android Keystore** for secure data storage
- **Permission-based access** control
- **Transparent privacy** indicators

### User Interface
- **Modern Material Design** with Jetpack Compose
- **Dark/Light theme** support
- **Floating assistant bubble** for quick access
- **Intuitive settings** and customization

---

## ⚙️ Settings & Customization

### Personalization
- **Custom wake words** - Train your own trigger phrases
- **Voice selection** - Choose from multiple TTS voices
- **Theme preferences** - Light/Dark mode toggle
- **Bubble styling** - Customize the assistant appearance

### Permissions Management
- **Microphone access** for voice commands
- **Overlay permission** for the assistant bubble
- **Contacts access** for messaging and calls
- **Storage access** for media playback

### Advanced Controls
- **Service management** - Start/stop assistant
- **Notification controls** - Manage what gets read aloud
- **App-specific settings** - Configure search preferences
- **Voice feedback** customization

---

## 🚀 Getting Started

### Prerequisites
- Android 8.0+ (API 26+)
- Microphone permission
- Internet access (for advanced features)

### Installation
1. Download the APK from [Releases](#) section
2. Enable "Install from unknown sources"
3. Install and grant necessary permissions
4. Say "Hey Joe" to activate!

### Basic Usage
1. **Wake the assistant**: Say "Hey Joe" or your custom wake word
2. **Give commands**: Speak naturally - "Send message to Sarah"
3. **Use conversation mode**: Continue speaking for follow-up commands
4. **Access bubble**: Tap the floating icon for quick access

---

## 🔧 Supported Commands

| Category | Examples |
|----------|----------|
| **Messaging** | "Send SMS to Mom", "WhatsApp John hello", "Read my messages" |
| **Calls** | "Call Dad", "Phone emergency services" |
| **Navigation** | "How far to airport?", "Navigate to city center", "Where am I?" |
| **Media** | "Play music", "Pause song", "Play Starboy by The Weeknd" |
| **Apps** | "Open YouTube", "Search for games in Play Store", "Open camera" |
| **Information** | "What's the time?", "Search for machine learning", "Calculate 25% of 80" |
| **Research** | "What are theories of AI", "How are cars made" |
| **System** | "Set alarm for 7 AM", "Take a note buy milk", "Open settings" |

---

## 📱 Screenshots
| Main Interface | Settings & Customization | Assistant Bubble |
|:--------------:|:------------------------:|:----------------:|
| <img src="screenshots/main-interface.png" width="200"> | <img src="screenshots/settings-page.png" width="200"> | <img src="screenshots/assistant-bubble.png" width="200"> |
| *Feature-rich main screen* | *Personalize your experience* | *Always-available voice control* |

| Text Scanner | 
|:----------:|
| <img src="screenshots/text-scanner.png" width="200"> |
| *OCR from camera* |
- Main interface with feature carousel
- Settings page with customization options
- Assistant bubble in action
- Text scanning interface

---

## 🛡️ Privacy & Terms

Your privacy is our priority. Kenji Assistant:
- Processes voice data locally when possible
- Stores sensitive information securely using Android Keystore
- Requests permissions only when needed
- Provides transparent privacy controls

**Terms of Use**: This software is proprietary. Commercial use, redistribution, or modification requires explicit permission.

---

## 📞 Support & Contact

For support, feature requests, or licensing inquiries:
- **Email**: briannjuguna694@gmail.com
- **Documentation**: [Full User Guide](#)
- **Issue Reporting**: [GitHub Issues](#)

---

## 📄 License

© 2024 Brian Njuguna. All Rights Reserved.

This project is proprietary software. All rights reserved. No part of this software may be reproduced, distributed, or transmitted in any form without prior written permission.

---

**Ready to transform your Android experience? Download Kenji Assistant today and start controlling your device with just your voice!** 🎉

<div align="center">

*"The most intuitive way to interact with your phone - just speak naturally"*

</div>
