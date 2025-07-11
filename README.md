### Senior Switchman

---
Senior Switchman is a Python-based application designed to simulate a 16-switch control system. The system allows users to send structured commands for turning switches ON/OFF, schedule actions based on time, and receive real-time feedback through both visual and auditory interfaces. It includes a smart GUI using Tkinter and sound notifications via `winsound` and `pygame`.

### Features

- **Command Execution Window**: Users can enter commands (e.g., `ON 1`, `OFF 2`, `? 1`, `? ALL`) to control switches.
- **Switch Visualization**: Real-time visualization of switch states in a separate graphical window.
- **Start Window**: Launches the system with a welcome message using text-to-speech.

### Technologies Used

- `tkinter`     – GUI interface  
- `winsound`    – Sound playback (Windows-only)  
- `pygame`      – Audio player for voice messages  
- `gTTS`        – Google Text-to-Speech for startup message  
- `Python 3`    – Programming language used

---

### Command Examples

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




