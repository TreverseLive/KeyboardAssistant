# Keyboard Assistant

> **Important Note:**  
> This README is best viewed on **GitHub**, where it will be fully formatted with headings, bullet points, links, and images.  
> If you view this README locally on your computer (e.g., in a plain text editor), it may not display properly, some areas may be outdated, and images may be missing.

**Keyboard Assistant** is a powerful, user-friendly tool designed to simplify repetitive tasks and transform any point-and-click game into a fully customizable, keyboard-controlled experience! It allows you to bind mouse movements and keyboard clicks to any key you choose, enabling smooth, customizable automation at the press of a button.

This software is intended for personal, educational, and/or commercial use (within license limits), and is distributed under the terms outlined in the included `LICENSE` file.

**Bonus**:  
Also included is the **Keyboard Assistant Editor (KAE)** — a companion program that makes it quick and easy to create and edit your commands and configurations through a simple, guided interface!

## Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Features](#2-features)
3. [Installation](#3-installation)
4. [Keyboard Assistant Editor (KAE) Instructions](#4-keyboard-assistant-editor-kae-instructions)
5. [Keyboard Assistant Instructions](#5-keyboard-assistant-instructions)
6. [Twitch/YouTube/TikTok Plays Instructions](#6-twitchyoutubetiktok-plays-instructions)
7. [License](#7-license)
8. [Contact](#8-contact)

## 1. Prerequisites

Before using Keyboard Assistant, make sure you have the following:

- **A command-line tool** such as Windows Command Prompt or PowerShell (or any similar terminal).
- **A working keyboard** — for obvious reasons!

## 2. Features

- **Fully customizable keyboard shortcuts** — bind any supported key to custom actions.
- **Cross-platform support** — works on Windows, Mac, and Linux.
- **Extensive key compatibility** — supports all ASCII characters, numbers, arrow keys, and special keys.
- **Unlimited keybinds** — limited only by the number of keys on your keyboard!
- **Multi-monitor support** — seamlessly move actions across multiple screens.
- **Infinite coordinate support** — create commands with as many coordinates as needed.
- **Configurable hotkeys** — easily set up pause, exit, and refresh hotkeys.
- **Infinite command file compatibility** — load and swap between as many command files as you want.
- **User-friendly editor** — included Keyboard Assistant Editor (KAE) for easy creation and editing of commands/configs.
- **Built-in bug report form** — quickly report any issues to the developer.

## 3. Installation

Installing **Keyboard Assistant** is quick and easy:

**Step 1:**  
[Download the latest version](https://github.com/TreverseLive/KeyboardAssistant/releases) from GitHub — it's completely free!  
_(Bonus: It comes pre-configured for FNAF 1 command inputs, so if that's your goal, setup is even easier.)_

**Step 2:**  
Extract the downloaded `.zip` file to a location of your choice.  
> **Important:** Keep all extracted files **together** in the same folder!

**Step 3:**  
- Run `Keyboard Assistant.exe` to start the main program.
- Use `Keyboard Assistant Editor.exe` to easily edit your commands and configuration.

> **Security Notice:**  
> **Keyboard Assistant** is electronically signed, for your safety.  
> However, because Windows requires a minimum of **1,000 downloads and runs** to fully recognize new software, you may see a **SmartScreen warning** when you first launch the program.  
> This is completely normal for new, independent applications — simply choose **"Run Anyway"** if you trust the source (and you downloaded it directly from the official GitHub page).
> Do **NOT** run the program if the publisher is listed as "Unknown".

## 4. Keyboard Assistant Editor (KAE) Instructions

The **Keyboard Assistant Editor (KAE)** is your all-in-one tool for editing your command and config files — no coding experience needed!  It walks you through every step, ensuring your commands are precise, correctly formatted, and ready for action.

Upon launching KAE, you'll be presented with four options:
- **Command Editor**
- **Config Editor**
- **Report a Bug**
- **Close**

![image](https://github.com/user-attachments/assets/7be76dcb-9899-4727-97dc-52f2bb30125c)

---

### Command Editor

The **Command Editor** helps you create and manage commands that will be run by Keyboard Assistant.  
All actions and parameters are carefully guided, with unavailable options automatically grayed out based on the command type.

**Main parameters you'll use:**

- **Select File** — Choose (or create) a `.txt` file where your commands will be stored.
- **Select Command** — Choose an existing command to edit, or create a new one.
- **Name** — A unique name identifier for each command.
- **Keybind** — Bind any ASCII character, arrow key (up, down, left, right), or special key (e.g., Ctrl, Enter, PageUp) to the action.
- **Type** — Choose the type of action to perform:
  - **Click** — Move to coordinates, wait, and click.
  - **Double** — Move to coordinates, wait, and DOUBLE-click.
  - **Move** — Smoothly move through multiple coordinates.
  - **Delayed** — Click and drag from one coordinate to another.
  - **Drag** — Move across coordinates, then click and hold.
  - **KeyPress** — Press a key multiple times.
  - **KeyHold** — Press and hold a key for a specified duration.

---

**Coordinate Management Parameters:**

- **Select Coordinate** — Edit or delete an existing coordinate (leave blank if none).
- **Coord Details** — View and edit the details of the selected coordinate.
- **Add Coordinate** — Add new coordinates to your command. (Use the **Start Capturing** button to grab a coordinate directly.)
  - **Add Below Option** — Check this box if you want to insert the new coordinate *after* a specific existing one. Leave it unchecked to add it to the end of the list.
  - **Infinite Coordinates** — All command types can use as many coordinates as you need!

---

**Additional Parameters:**

- **Wait** — Set wait time (in milliseconds) before execution and between steps.
- **Hold** — Set the duration (in milliseconds) to hold down a key or mouse button.
- **Mouse** — Choose the mouse button (Left or Right).
- **Glide** — Define how long (in milliseconds) the mouse should take to move between coordinates.
- **Press** — Set how many times to press a key (for KeyPress commands).

![image](https://github.com/user-attachments/assets/037b38e9-e720-410b-8e2e-b17b98f27c6e)

---

### Config Editor

The **Config Editor** lets you easily adjust the main settings for Keyboard Assistant.  
You can tweak:

- **Command File Name** — The `.txt` file Keyboard Assistant reads commands from.
- **Debug Mode** — Enable or disable detailed logging of program activity.
- **Sleep Mode** — Control program CPU usage:
  - **0** = No sleep (maximum responsiveness)
  - **1** = Sleep after each command
  - **2** = Periodic sleep/wake cycle while idle
- **Sleep Time** — How long the program sleeps (in seconds).
- **Sleep Warning** — Toggle notifications when the program sleeps or wakes.
- **Pause Hotkey** — Key or key combo to pause/resume Keyboard Assistant.
- **Exit Hotkey** — Key or key combo to instantly close the program.
- **Refresh Hotkey** — Key or key combo to reload the command file while running.

![image](https://github.com/user-attachments/assets/7d401efc-a75e-48d6-a5f4-c7ec104c0a9d)

---

### Report a Bug

Selecting **Report a Bug** will open a Google Form where you can quickly describe any issues you encounter.  
Your feedback helps improve Keyboard Assistant!

---

### Close

Select **Close** to exit KAE once you're done.  
_(Pretty straightforward!)_

## 5. Keyboard Assistant Instructions

Once you've set up your command and config files using the **Keyboard Assistant Editor (KAE)**, you're ready to roll! Running `Keyboard Assistant.exe` will take it from there — handling everything automatically.

Keyboard Assistant is pre-programmed to:
- Check for updates.
- Verify all keybinds.
- Attempt to auto-correct minor errors.

Outputs are **color-coded** for easy reading:
- **Green** — Successful validation or execution.
- **Yellow** — Warning; something worth reviewing but not critical.
- **Red** — Urgent error; a command may not function correctly.

---

### Pause, Exit, & Refresh Controls

At any time, you can:
- **Pause** the program
- **Exit** the program
- **Refresh** the command file

These actions are triggered using the customizable hotkeys defined in your `config.txt` file.  
(You can easily edit these settings through the Keyboard Assistant Editor!)

---

### Included Files

Your installation includes several important files:

- **config.txt** — Stores your program settings (editable via KAE).
- **log.txt** — Stores all important outputs, to diagnose any issues.
- **Command Files** — You can create as many `.txt` command files as you like!
- **FNAF.txt** — A sample file already set up to control Five Nights at Freddy's.

**Pro Tip:**  
To create your own custom command file:
1. Create a new `.txt` file anywhere on your computer.
2. Use the **Keyboard Assistant Editor** to add and manage commands.

---

### How It Works (Behind the Scenes)

Once you run **Keyboard Assistant**:
1. It reads and verifies your selected command file.
2. It checks each command for proper formatting, readability, and executability.
3. If any issues are found, detailed warnings will explain exactly what went wrong.
4. All valid commands will become active — and Keyboard Assistant will listen for your key inputs!

At that point, your automation is live and ready to go!


## 6. Twitch/YouTube/TikTok Plays Instructions

**Twitch Plays** is a niche genre of livestream on Twitch where **the audience collectively controls a game by sending commands through the chat**. Instead of the streamer playing, viewers type inputs (like “up”, “down”, “A”, “start”) into the chat, and a chatbot reads these messages and translates them into game controls.
The genre started back in 2014 with **“Twitch Plays Pokémon,”** where thousands of viewers attempted to beat Pokémon Red together — leading to chaotic, unpredictable, but often hilarious and surprisingly successful progress!

Setting up your own **Twitch/YouTube/TikTok Plays** stream has never been easier using Keyboard Assistant!  Some setups (especially TikTok) may require additional tools or subscriptions, but this detailed guide will walk you through everything.

You have two main options, depending on where you’re streaming:

---

## Option 1: Twitch/YouTube Plays

_(Skip this section if you are only streaming to TikTok.)_

### Step 1: Download a Chatbot

You'll need a chatbot that can:
- Read your Twitch or YouTube chat
- Virtually press keys on your keyboard

I highly recommend **[MixItUp](https://mixitupapp.com/)** because:
- It's completely free
- It supports both Twitch and YouTube simultaneously
- It offers nearly *infinite* customization (audio, GIFs, on-stream alerts, chat commands, timers, moderation, giveaways, and so much more!)

---

### Step 2: Set Up Chat Commands in MixItUp

You'll want to create **one command per action** you want chat to trigger.

**To create a command:**
1. Open **MixItUp** and click the **hamburger icon** at the top-left corner.
2. Click the **Commands** tab.
3. At the bottom of the page, click **New Command**.
4. In the resulting popup window:
   - Name the command after the action (e.g., `LeftDoor`).
   - In the **Chat Triggers** field, enter the chat word(s) that should activate the command (e.g., `LeftDoor`).
     > **Important:**  
     > - If you want to **require an exclamation mark** (e.g., `!LeftDoor`), turn **ON** the "Auto-Include '!'" toggle.  
     > - **Do not** manually type the exclamation mark into the trigger field — MixItUp adds it automatically.
     > - If you prefer chatters to just type the word alone (`LeftDoor`), leave Auto-Include **OFF**.

---

### Step 3: Configure Virtual Key Presses

Inside **each** MixItUp command:
1. At the bottom of the popup window, select the **Action** dropdown.
   - Scroll and find **Input (Keyboard & Mouse)**.
   - Click the **"+"** button to import it into the command.
4. Configure the action:
   - Set **Type** to **Keyboard**.
   - Select the specific key you want MixItUp to **virtually press** when this command is triggered.
     - Example: When a chatter says `LeftDoor`, MixItUp will virtually press the `Q` key.

✅ **Repeat Steps 2–3** for every keybind you want chat to control!

![image](https://github.com/user-attachments/assets/cc6a1c77-5883-4c47-b7b7-38bb5c616426)

---

## Option 2: TikTok Plays

_(Skip this section if you are only streaming to Twitch/YouTube.)_

> **⚠️ WARNING:**  You may need to purchase **TikFinity Pro** ($19/month) if you want to create more than 5 actions.

### Step 1: Download TikFinity

- Download **[TikFinity](https://tikfinity.zerody.one/)** — a powerful, free desktop app that reads TikTok chat.

> **Note:**  TikFinity has lots of cool features, but we mainly need it to **detect chat messages and trigger virtual key presses**.

---

### Step 2: Set Up Events and Actions in TikFinity

In TikFinity:
1. Go to the **Actions & Events** tab.
   > This is where you create **Events** that trigger **Actions**.
2. Create a **New Action**:
   - Toggle **ON** **Simulate Keystrokes**.
   - Select the key(s) you want TikFinity to virtually press.
   - (Optional) Adjust cooldowns, durations, and other settings as desired.
3. Create a **New Event**:
   - Set it to be triggered by **Commenting a Command**.
   - Example: When someone sends `/LeftDoor`.
     > _(TikTok commands typically start with `/` or `!`)_
   - Link the appropriate **Action** to the **Event** at the bottom of the Event setup window.

✅ **Repeat Step 2** for every keybind you want chat to control!

![image](https://github.com/user-attachments/assets/809f42d7-5c68-4079-84db-2dd496a7c6e6)


![image](https://github.com/user-attachments/assets/dae1bedc-ee3c-4142-aa5f-88561d86f7d2)

---

## Next Steps (After Chatbot Setup)

After setting up MixItUp (Twitch/YouTube) or TikFinity (TikTok):

1. **Use the Keyboard Assistant Editor (KAE)** to create a **command** matching each virtual key press.
   - Example: If `/LeftDoor` triggers a virtual `Q` keypress, create a `Q` command in KAE.
2. **Assign coordinates/actions** to each command according to what you want that key to do.

Refer to [Section 5: Keyboard Assistant Instructions](#5-keyboard-assistant-instructions) for help creating commands!

---

## Final Setup & Activation

You're almost there! Here's how to launch everything:

**Step 1:**  
- Open your game.
- Open **MixItUp** or **TikFinity** — whichever one you configured.  
(Just having the app open will automatically make it start listening to chat.)

**Step 2:**  
Run `Keyboard Assistant.exe` — it will automatically start intercepting key presses!

**Step 3:**  
That's it!  
Now when someone sends a chat message (like `!LeftDoor` or `/LeftDoor`):
- Your chatbot (MixItUp or TikFinity) will virtually press a key.
- **Keyboard Assistant** will detect that keypress and execute the correct action!

---

## Wrapping Up

- Play along with your viewers on another device, or just sit back and watch!
- You can **pause** or **exit** Keyboard Assistant at any time using your configured hotkeys.
- When you're ready to end the stream, simply close Keyboard Assistant and your chatbot app.

---

## 7. License

This project is licensed under the terms outlined in the `LICENSE` file. You are permitted to use this software for personal, educational, and limited commercial purposes, provided that the software itself is not the primary focus of any commercial offering. Redistribution or modification of the core code is prohibited. For full details, please refer to the `LICENSE` file.


## 8. Contact

For any questions, concerns, or support, feel free to reach out:

**Treverse**
- **Email:** [Treverse.Biz@gmail.com](mailto:Treverse.Biz@gmail.com)
- **GitHub:** [https://github.com/TreverseLive](https://github.com/TreverseLive)
- **Website:** [https://Treverse.Live](https://Treverse.Live)

---

If you find **Keyboard Assistant** helpful and would like to support its continued development, you're welcome (but not obligated) to contribute here:

- [Support Treverse via StreamElements](https://streamelements.com/treverselive/tip)

Your support is always appreciated — thank you for using **Keyboard Assistant**!
