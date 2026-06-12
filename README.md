# Nebula Navigator: A Galaxy Star Record System

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows%20(WSL)-brightgreen.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Bash-orange.svg" alt="Language">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
</p>

<p align="center">
  <b>Empowering astronomers with a robust, terminal-based star tracking ecosystem.</b>
</p>

---

## 🌌 Overview

**Nebula Navigator** is a comprehensive Galaxy Star Record System designed to manage and track stellar data efficiently through a terminal interface. Built with Bash, it provides a lightweight yet powerful solution for recording star positions, types, distances, and descriptions.

## ✨ Features

- 🔐 **Secure Access**: Multi-user login system with encrypted-style password verification.
- ➕ **Stellar Entry**: Easily add new stars with auto-incrementing IDs.
- 📋 **Comprehensive View**: List all recorded stars in a beautifully formatted table.
- 🔍 **Advanced Search**: Find specific stars by their exact names (case-insensitive).
- 📝 **Dynamic Editing**: Update star information on the fly.
- 🗑️ **Secure Deletion**: Remove records with administrative password confirmation.
- 📏 **Distance Tracking**: Check star distances and view a sorted list of all stars by proximity to Earth.

## 🛠️ Tech Stack

- **Scripting Language**: Bash
- **Data Storage**: Plain text files (`data.txt`, `users.txt`)
- **Tools**: `awk`, `grep`, `sed`, `column`, `sort`

## 🚀 Getting Started

### Prerequisites

- A Unix-like environment (Linux, macOS, or WSL on Windows).
- Bash shell installed.

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Oprating-System.git
    cd Oprating-System
    ```

2.  **Navigate to the project directory**:
    ```bash
    cd "Nebula Navigator"
    ```

3.  **Ensure permissions**:
    ```bash
    chmod +x code.sh
    ```

### Usage

Run the main script to start the application:

```bash
./code.sh
```

**Default Admin Credentials:**
- **Username**: `admin`
- **Password**: `admin123`

## 📂 Project Structure

```text
.
├── LICENSE                 # MIT License file
├── README.md               # Project documentation
└── Nebula Navigator/
    ├── code.sh             # Main application script
    ├── data.txt            # Stellar database (pipe-separated)
    └── users.txt           # User credentials database
```

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Operating System | Green University of Bangladesh</i>
</p>
