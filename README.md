# ⏰ Java Alarm Clock

A simple yet effective **Console-Based Alarm Clock** built with Java. This application allows users to set an alarm using a specific time, continuously displays the current time, and plays an alarm sound when the target time is reached.

---

## 🚀 Features

* Set an alarm using the `HH:mm:ss` format
* Real-time clock display in the console
* Multi-threaded implementation using Java Threads
* Plays a custom alarm sound when the alarm triggers
* Press **Enter** to stop the alarm
* Input validation for incorrect time formats
* Clean and beginner-friendly code structure

---

## 📂 Project Structure

```text
├── Main.java
├── AlarmClock.java
└── alarm sound.wav
```

### Main.java

Responsible for:

* Accepting user input
* Validating alarm time format
* Creating and starting the alarm thread

### AlarmClock.java

Responsible for:

* Monitoring the current system time
* Displaying a live clock in the console
* Triggering the alarm when the specified time is reached
* Playing and stopping the alarm sound

---

## 🛠 Technologies Used

* Java
* Java Threads (`Runnable`)
* Java Time API (`LocalTime`)
* Java Sound API (`javax.sound.sampled`)

---

## ⚙️ Requirements

* Java JDK 8 or later
* A valid `.wav` audio file for the alarm sound

### Important

The Java Sound API used in this project supports **WAV audio files**.

✅ Supported:

```text
alarm sound.wav
```

❌ Not Recommended:

```text
alarm sound.mp3
alarm sound.m4a
alarm sound.aac
```

Ensure your alarm sound file is named:

```text
alarm sound.wav
```

and placed in the project's root directory.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Compile the Project

```bash
javac Main.java AlarmClock.java
```

### 3. Run the Application

```bash
java Main
```

---

## 💻 Example Usage

```text
Enter alarm time (HH:mm:ss): 14:30:00
Alarm set for 14:30

14:29:55
14:29:56
14:29:57
14:29:58
14:29:59

**Alarm Noise**
Press *Enter* to stop the alarm:
```

---

## 🔍 Error Handling

The application gracefully handles:

* Invalid time formats
* Unsupported audio file formats
* Missing audio files
* Audio device availability issues
* Thread interruptions

Example:

```text
Invalid format. Please enter HH:mm:ss
```

---

## 🧠 Concepts Demonstrated

This project showcases several important Java concepts:

* Object-Oriented Programming (OOP)
* Multithreading
* Exception Handling
* File Handling
* Java Time API
* Java Sound API
* User Input Validation

---

## 🎯 Future Improvements

Possible enhancements include:

* Multiple alarms support
* Snooze functionality
* GUI version using JavaFX or Swing
* Alarm repeat schedules
* Volume control
* Custom alarm sound selection
* Date-based alarms

---

## 📸 Preview

```text
Enter alarm time (HH:mm:ss): 07:00:00
Alarm set for 07:00

06:59:58
06:59:59
07:00:00

**Alarm Noise**
Press *Enter* to stop the alarm:
```

---

## 📜 License

This project is open-source and available for learning, modification, and personal use.

---

### Author

Developed by **Ramith Perera**

If you found this project useful, consider giving it a ⭐ on GitHub!
