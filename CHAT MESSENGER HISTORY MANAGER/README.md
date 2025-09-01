# 💬 Chat Message History Manager

A lightweight **Chat Message History Manager** built in **Python**.  
It uses classic data structures to handle chat-like operations:  

- **Queue** → Store and process incoming messages in order (FIFO).  
- **Stack** → Undo/Redo sent messages (LIFO).  
- **Timestamp Tracking** → Every message is timestamped for audit and history.  

---

## 🚀 Features
- 📥 **Incoming Message Queue** – Messages arrive and are processed in order.  
- 📤 **Sent Message History** – Track all sent messages.  
- ⏪ **Undo/Redo** – Retract and restore the last sent message with ease.  
- 🕒 **Timestamps** – Every message includes a precise UTC timestamp.  
- 🖥️ **Console-based Demo** – Clear, easy to follow output.  

---

## 🛠️ Tech Stack
- **Language**: Python 3  
- **Data Structures Used**:  
  - Queue → Incoming messages  
  - Stacks → Undo/Redo actions  
  - Dataclass → Message model with timestamps  

---

## 📂 Project Structure
- 📁 chat-message-history-manager
     ┣ 📜 chat_manager.py # Main source code
     ┣ 📜 README.md # Project documentation


---

## ⚡ How to Run
- 1. Clone the repository:
      -git clone https://github.com/your-username/chat-message-history-manager.git
      cd chat-message-history-manager
- 2. Run the program:
     python chat_manager.py

##  🎯 Future Enhancements

 - Add a menu-driven CLI for interactive use.

 - Persist chat logs to a file or database.

 - Add multiple user support and chat rooms.

 - GUI version with Tkinter or PyQt.

## 🤝 Contributing

  - Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## 🖼️ Screenshots

Here’s how the program looks when running in the terminal:

![Chat Demo](screenshots/demo.png)

> Place your screenshots inside a folder named **`screenshots/`** in the project directory.  
> You can add more screenshots and reference them like this:

![Undo Example](screenshots/undo.png)  
![Redo Example](screenshots/redo.png)
