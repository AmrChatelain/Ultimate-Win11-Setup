<h1 align="center">⚠️ UNDER CONSTRUCTION ⚠️</h1>
<h3 align="center">✨ My Windows 11 Setup ✨</h3>

<p align="center">
A complete guide to my Windows 11 customization – from the YASB bar to all the little tweaks that make it clean, aesthetic, and productive.
</p>

---

## 🖼️ Screenshot
![My Desktop Screenshot](screenshot.png)

---

## 📑 Table of Contents

| 📚 Entry | ✨ App |
|---------------------|------------|
| Status Bar          | [YASB](#yasb) |
| Window Manager      | [GlazeWM](#glazewm) |
| App Launcher        | [Flow Launcher](#flowlauncher) |
| Taskbar             | [Windhawk](#windhawk) |
| Text Editor         | [VSCode](#vscode) |
| Terminal            | [Windows Terminal](#windows-terminal) |
| Browser             | [Brave](#brave) |
| System Fetch        | [Fastfetch](#Fastfetch) |   
| Shell Prompt        | [Oh My Posh](#ohmyposh) |
| Audio Visualizer    | [Cava](#cava) |
| Music Player        | [Spotify](#spotify) | 
| Note Taking         | [Notesnook](#notesnook) |
| Screen Recording    | [OBS Studio](#obsstudio) |
| File Explorer Mod   | [ExplorerBlurMica](#ExplorerBlurMica) |
| Other Tools         | [Extras](#extras) |

Other

| 📚 Entry | ✨ App |
|---------------------|------------|
| Colorscheme         | [Catppuccin Mocha](#catppuccinmocha) |
| Font                | [JetBrainsMono Nerd Font](#jetbrainsmononerdfont) |


---

# ⚡ Details

## 📏 YASB
> [!NOTE] 
> Some stuff in my config might not work if you just copy and paste it. Be sure to app your api for the weather widget to work and your wallpaper folder location for the wallpapers widget

A highly configurable Windows status bar written in Python. 

**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://www.youtube.com/watch?v=your-video-id).
- Install [**YASB**]([(https://github.com/amnweb/yasb)])   
- Copy the config files from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/YASB).
- Remove the codes from **your** YASB config and paste the one you just copied.
- Restart **YASB** for the changes to take effect.

---

## 🪟 GlazeWM + YASB
> [!NOTE] 
> If your using my config then Zebar won't work as I use GlazeWM with YASB. I recommend adding those 2 lines of code back which I had deleted if you wanna use Zebar

GlazeWM lets you easily organize windows and adjust their layout on the fly by using keyboard-driven commands.  

**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://youtu.be/b57zFm3nVxA).
- Install [**GlazeWM**](https://github.com/glzr-io/glazewm)   
- Copy the config file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/GlazeWM).
- Remove the codes from **your** GlazeWM config and paste the one you just copied.
- Restart **GlazeWM** for the changes to take effect.

---

## 🦅 Windhawk
> [!NOTE] 
> Right now I have just listed the advance section codes for the mods I use. If your using the taskbar config of mine then it would remove the start menu and network icon. To add them back follow [**this**](https://github.com/ramensoftware/windows-11-taskbar-styling-guide)

Windhawk aims to make it easier to customize Windows programs.

**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://youtu.be/b57zFm3nVxA) if you wanna know more about the taskbar.
- Install [**Windhawk**](https://windhawk.net/)   
- Copy the config file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Windhawk).
- Remove the codes from the advance section in **your** Windhawk mod and paste the one you just copied.
- Click **Save settings** for the changes to take effect.

---

## 🔍 Flow Launcher

Quick File Search & App Launcher for Windows

**⚙️ Installation:**  
You can follow the steps below,
- Install [**Flow Launcher**](https://www.flowlauncher.com/).
- Download the theme file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Flow%20Launcher).
- Open Flow Launcher's Settings window, select **Appearance** on the sidebar, and click the "Open Theme Folder" button at the bottom.
- Move your theme file downloaded in Step 1 to this directory, and restart Flow Launcher.
- Again in Flow Launcher's Settings window, select **Appearance** on the sidebar, and select your Catppuccin flavor from the list of themes.
Installation guide was taken from [**here**](https://github.com/catppuccin/flow-launcher). Thanks :)

---

## 📁 ExplorerBlurMica
> [!NOTE] 
> A few people had said that they are getting bugs and crashes by using this, so I recommend to now use it and follow the windhawk method **here** (video will be added soon)

Add background Blur effect or Acrylic or Mica effect to explorer for win10 and win11

**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://youtu.be/gpGeCZXXsbs).
- Install [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica/releases)   
- Copy the config file from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/File%20Explorer).
- For the next part, I'm using the default stuff so just follow the installation from [**here**](https://github.com/Maplespe/ExplorerBlurMica?tab=readme-ov-file#install) 

---

## 👾 Terminal + Fastfetch
> [!NOTE] 
> If you just wanna fully use it just like I'm using then I recommend watchng the video. If you just want the config for Fastfetch then just paste the config where **your** Fastfetch config is located. If you have a PowerShell profile then just add your location and other stuff in your profile yourself as idk what you got.
>
> If you see **"execution of scripts is disabled on this system"**, don’t panic! Just open PowerShell as Administrator and run: 
> `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force`
 
Fastfetch is a neofetch-like tool for fetching system information and displaying it in a visually appealing way. It is written mainly in C, with a focus on performance and customizability.

**⚙️ Installation:**  
You can follow the steps below, or jump to the [**setup video**](https://youtu.be/z3NpVq-y6jU) if you want your terminal to look 1:1 to mine.
- Install [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases) and I believe you already got the **Windows terminal** installed.
- Copy the config file for your Terminal [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Terminal), PowerShell profile from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/PowerShell) and Fastfetch config from [**here**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Fastfetch)
- Remove the codes from the settings.json file in **your terminal** and paste the one you just copied from above. Do the same thing for your PowerShell profile.
- Create a **.config** *hidden* file in your C:\Users\%USERPROFILE% and create a folder called **fastfetch** inside. Copy the config and ascii code you just downloaded and paste it in that folder.
- Change the %USERPROFILE% from the config file in the fastfetch folder and the PowerShell profile with **your username**..
- Restart your terminal and your done. If this feel complicated just watch the [**setup video**](https://youtu.be/z3NpVq-y6jU).

---

## 🪟 AC
> [!NOTE] 
> if you got an error and didn't work just run this
> PS C:\Users\(you username)> Get-ExecutionPolicy -List
> and it will give Undefined
> then you can run  Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
> and you're good to go and to check you can run Test-Path $PROFILE


**⚙️ Discord
Use BetterDiscord

Go to the official BetterDiscord website: https://betterdiscord.app/

Download and install BetterDiscord for your platform.

After installation, open Discord.

Go to User Settings → Themes (you’ll see this new section under “BetterDiscord”).

Click “Open Themes Folder”.

Create a new file (e.g., catppuccin.theme.css) and paste this line in:

@import url("https://catppuccin.github.io/discord/dist/catppuccin-mocha.theme.css");


Save the file and enable it in the Themes menu.
