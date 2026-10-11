<div align="center">

# 🌌 Nebula Navigator: Galaxy Star Record System
### **Terminal-Based Astronomical Database & Unix POSIX Shell Scripting**

[![Platform](https://img.shields.io/badge/Platform-Linux_%7C_WSL_%7C_macOS-brightgreen?style=for-the-badge&logo=linux&logoColor=white)](https://kernel.org)
[![Language](https://img.shields.io/badge/Language-Bash_Script-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)](https://gnu.org/software/bash/)
[![Course](https://img.shields.io/badge/Course-Operating_Systems-8E75FF?style=for-the-badge)](https://green.edu.bd)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Empowering astronomers with a robust, POSIX terminal-based celestial object tracking ecosystem.**

---

[Explore Features](#-features) • [Tech Stack](#-tech-stack) • [Project Structure](#-project-structure) • [Usage](#-getting-started)

</div>

---

## 🌌 Overview
**Nebula Navigator** is a comprehensive Galaxy Star Record System developed as part of the Operating Systems course curriculum at **Green University of Bangladesh**. Built purely in **Bash**, it leverages standard Unix stream processors (`awk`, `sed`, `grep`, `sort`, `column`) and inter-process signals to deliver a lightweight, high-performance console database for celestial cataloging.

---

## ✨ Features

- 🔐 **Multi-User Authentication:** Role-based administrative login system verifying credentials stored in `users.txt`.
- ➕ **Stellar Record Indexing:** Automated sequential ID generation tracking celestial coordinates, spectral types, and light-year distances.
- 📋 **Formatted Pipe-Delimited Table:** Colorized, dynamic column alignment rendered on-the-fly with `column -t`.
- 🔍 **Regex Pattern Searching:** Case-insensitive astronomical entity search filtering by star catalog name.
- 🗑️ **Atomic Record Management:** Protected record deletion with administrative confirmation preventing accidental data loss.
- 📏 **Proximity Calculation:** High-speed sorting calculating star proximity from Earth using numerical Unix sort keys.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Scripting Language** | GNU Bash (Bourne-Again Shell) | Command interpreter & control flow |
| **Stream Processors** | `awk`, `grep`, `sed`, `cut` | In-memory text manipulation & field splitting |
| **Formatting** | `column`, `tput`, ANSI Codes | Terminal table formatting and screen buffering |
| **Storage Engine** | Flat Pipe-Separated Files (`.txt`) | Lightweight POSIX file persistence |

---

## 📂 Project Structure

```text
Oprating-System/
├── LICENSE                         # MIT License
├── README.md                       # Project documentation
└── Nebula Navigator/
    ├── code.sh                     # Main executable application shell script
    ├── data.txt                    # Stellar database table (pipe-separated)
    └── users.txt                   # User credentials database
```

---

## 🚀 Getting Started

### 1. Prerequisites
- Linux, macOS, or Windows WSL with GNU Bash.

### 2. Permissions & Launch
```bash
cd "Nebula Navigator"
chmod +x code.sh
./code.sh
```

**Default Admin Credentials:**
- **Username:** `admin`
- **Password:** `admin123`

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed with ❤️ by Fuad**  
*Developed by Softece*  
*Operating System | Green University of Bangladesh*

</div>
