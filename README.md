
# ♟️ Chess Server Client AI

A network-based chess game with a client-server architecture, supporting both **online multiplayer** (player vs player over LAN/internet) and **offline single-player** (player vs AI) modes. Built in Python using sockets, threading, and a simple Minimax-based AI.

---

## 🚀 Features

- ✅ **Client-Server architecture** using TCP sockets
- 👥 **Multiplayer mode** (Player vs Player over network)
- 🧠 **Single-player mode** (Player vs AI)
- 🔄 Real-time game state synchronization
- ⏱️ Turn-based timers (optional)
- ✅ Legal move validation
- 🪟 GUI using `tkinter` (or your GUI framework)
- 🧩 Modular and extensible design

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Networking**: `socket`, `threading`
- **GUI**: `tkinter` (or replace with `pygame`, `PyQt`, etc.)
- **AI**: Minimax algorithm with optional alpha-beta pruning
- **Optional**: `python-chess` for move validation (if used)

---

## 📁 Project Structure
chess-server-client-ai/
├── server/
│ └── server.py # Handles player connections and game state
├── client/
│ └── client_updated_fixed.py # Connects to server and runs player GUI
├── ai/
│ └── chess_ai.py # Basic AI opponent logic
└── README.md


---

## 🧪 How to Run

### 1. Clone the Repository

```bash
git clone [https://github.com/yourusername/chess-server-client-ai.git](https://github.com/Umaimtahir/chess-server-client-ai)
cd chess-server-client-ai

2. Start the Server
python server/server.py

3. Start a Client
In a new terminal or system:
python client_updated_fixed.py

4. Choose Game Mode
🧍 vs 🧍: Connect 2 clients to the same server (PVP)

🧍 vs 🤖: Use AI mode from client-side selection
