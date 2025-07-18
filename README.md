# Java Internet Download Manager (IDM)

A simple yet powerful Internet Download Manager built using **JavaFX** for GUI and **multi-threaded downloading** logic in Java. This project demonstrates how to build a basic download manager with real-time progress tracking and thread-based downloads.

## 🚀 Features

- ✅ JavaFX GUI
- ✅ Multi-threaded download support
- ✅ Real-time UI update with download percentage
- ✅ Auto-filename from URL
- ✅ Easy configuration of download path
- ✅ MVC-style code separation

---

## 🛠 Tech Stack

- **Java 11+**
- **JavaFX**
- **Maven** (optional)
- **FXML** for UI design

---
📁 Project Structure
org.example/
├── App.java # JavaFX launcher
├── DownloadManager.java # Main controller class
├── DownloadThread.java # Handles downloading in a separate thread
├── models/
│ └── FileInfo.java # Model class to represent download metadata
├── config/
│ └── AppConfig.java # Centralized configuration (e.g., download path)
├── resources/
│ └── downloadManager.fxml # JavaFX UI layout


How It Works
User enters a valid URL.

File name is extracted automatically from the URL.

Download is initiated in a separate thread (DownloadThread).

Download status and progress are updated in real-time on the JavaFX TableView.
