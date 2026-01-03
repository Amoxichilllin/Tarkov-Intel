# Tarkov Intel - Stash Auditor & Quest Tracker

A lightweight, browser-based tool to help track Escape from Tarkov quests, hideout upgrades, and stash inventory.

## How to Use (No Download Required)
**[Click Here to Open the Tool](https://amoxichilllin.github.io/Tarkov-Intel/)** *(Note: If the link doesn't work, ensure GitHub Pages is enabled in Settings)*

## Setup Guide (First Time Only)
To sync your personal progression, you need a **Read-Only API Token** from TarkovTracker. This ensures the tool loads **your** quests, not mine.

1. Go to [TarkovTracker.io Settings](https://tarkovtracker.io/settings/).
2. Under "API Tokens", click **Create Token**.
3. **Important:** Ensure **"Get progression"** is checked.
4. Copy the long token string.
5. Open **Tarkov Intel**, click **Sync**, and paste your token.

## Privacy & Security
* **Client-Side Only:** This tool runs entirely in your browser.
* **No Data Collection:** Your API token and progress are saved to your browser's Local Storage. Nothing is sent to my server (because I don't have one).
* **Safe to Use:** The code is open source and visible in this repository.

## Features
* **Stash Auditor:** Type an item name (e.g., "D Size Battery") to instantly see if you need it for *any* active quest or hideout upgrade.
* **Quest Tracker:** Filter by Kappa or Lightkeeper requirements.
* **Smart Filtering:** Hides useless weapon parts unless they are specifically needed for a Gunsmith task.
