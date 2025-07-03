# Senior Switchman – Intelligent Switch Control System

Senior Switchman is a Python-based desktop GUI application designed to simulate and control a network of electrical switches. The system allows users to send structured commands for turning switches ON/OFF, schedule actions based on time, and receive real-time feedback through both visual and auditory interfaces. It includes a smart GUI using Tkinter and sound notifications via `winsound` and `pygame`.

---

## Features

### 🖥 GUI Functionalities
- **Command Execution Window**: Users can enter commands (e.g., `ON 1`, `OFF 2`, `? 1`, `? ALL`) to control switches.
- **Switch Visualization**: Real-time visualization of switch states in a separate graphical window.
- **Start Window**: Launches the system with a welcome message using text-to-speech.

### ⚙️ Switch Control Logic
- **Individual Switch ON/OFF**
- **Turn All ON/OFF**
- **Query Current State of Switches**
- **Scheduled ON Commands with `AT <time>`**
- **Birthday-style Audio Feedback using `.wav` sounds**

### 🔊 Audio & Speech
- **Switch Toggle Sound Effects**
- **Welcome Voice Message** using Google Text-to-Speech (`gTTS`)

---

## Technologies Used

- `tkinter` – GUI interface
- `winsound` – Sound playback (Windows)
- `pygame` – Audio player for voice messages
- `gTTS` – Google Text-to-Speech for startup message
- `Python 3`

---

## Command Examples

| Command        | Description                                 |
|----------------|---------------------------------------------|
| `ON 1`         | Turn on Switch 1                            |
| `OFF 2`        | Turn off Switch 2                           |
| `ALL ON`       | Turn on all switches                        |
| `? 3`          | Display state of Switch 3                   |
| `? ALL`        | Display state of all switches               |
| `ON 5 AT 1200` | Schedule Switch 5 to turn on at 12:00       |
| `STOP`         | End simulation                              |

---




