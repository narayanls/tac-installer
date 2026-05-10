# Tac Writer Installer

<p align="center">
  <img src="Screenshots/Screenshot.png" alt="TAC Writer Installer Screenshot" width="600">
</p>

[![Go Version](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)](https://go.dev/)
[![Platform](https://img.shields.io/badge/Platform-Linux-orange?style=flat&logo=linux)](https://www.kernel.org/)
[![Language](https://img.shields.io/badge/Language-PT--BR-green)](https://en.wikipedia.org/wiki/Portuguese_language)
[![License](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
![Downloads](https://img.shields.io/github/downloads/narayanls/tac-installer/total?style=flat-square)

A modern, lightweight graphical installer for [Tac Writer](https://github.com/narayanls/tac-writer), built with **Go** and **Zenity**. This tool simplifies the installation process for Linux users, automatically fetching the latest version of the software directly from the source.
Tac Installer was originally created by Jibreel al-Yahya under GPL 2 license. Now it is mentioned only by Narayan Silva.

---

## 🚀 Features

* **GUI Interface:** Friendly graphical dialogs powered by Zenity.
* **Version Control:** Automatically checks for new versions and downloads the latest release from the [official Tac Writer repository](https://github.com/narayanls/tac-writer).
* **Universal Compatibility:** Supports virtually all Linux distributions (Ubuntu, Fedora, Arch, Debian, openSUSE, Solus, etc.).
* **Streamlined Process:** No need for complex terminal commands; just follow the visual prompts.

> [!IMPORTANT]
> **Language Support:** Currently, both the installer and TAC Writer are available exclusively in **Portuguese (Brazil)**.

---

## 🛠️ Prerequisites

Before building and running the installer, you must install **Go** and **Zenity**. Use the command corresponding to your distribution:

* **Ubuntu / Debian:**
    ```bash
    sudo apt install golang zenity
    ```
* **Fedora / RHEL:**
    ```bash
    sudo dnf install golang zenity
    ```
* **Arch Linux:**
    ```bash
    sudo pacman -S go zenity
    ```
* **openSUSE (Leap or Tumbleweed):**
    ```bash
    sudo zypper install go zenity
    ```
* **Solus:**
    ```bash
    sudo eopkg install golang zenity
    ```

---

## 📥 How to Install & Run

    ### Via File Manager (GUI)
    1. Right-click the file `tac-installer`.
    2. Go to **Properties** > **Permissions**.
    3. Check the box **"Allow executing file as program"** (or similar).
    4. **Double-click** the file to launch.

---

## 📄 License

This project is licensed under the **GPL v2 License**. See the `LICENSE` file for more details.

---

## 🤝 Contributing

Contributions are welcome! If you encounter any bugs or have suggestions for new features, feel free to open an **Issue** or submit a **Pull Request**. 

*Note: Since the software targets the Brazilian community, feel free to open issues in Portuguese.*
