<h1 align="center">EASY POLL</h1>

<p align="center"><b>A fast, smooth file mover for the Pterodactyl panel.</b><br>Select. Cut. Pick a folder. Paste. Done.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pterodactyl-Panel-0e1117?style=for-the-badge&labelColor=1f2430&color=3b82f6" alt="Pterodactyl">
  <img src="https://img.shields.io/badge/Blueprint-Extension-0e1117?style=for-the-badge&labelColor=1f2430&color=8b5cf6" alt="Blueprint">
  <img src="https://img.shields.io/badge/Version-1.1.0-0e1117?style=for-the-badge&labelColor=1f2430&color=22c55e" alt="Version">
  <img src="https://img.shields.io/badge/Author-Pawan-0e1117?style=for-the-badge&labelColor=1f2430&color=f59e0b" alt="Author">
</p>

---

## About

Easy Poll is a Blueprint extension that makes moving files around a Pterodactyl server simple. Instead of typing relative paths and hoping you got them right, you tick your files, press Cut, browse to the folder you want, and press Paste. A confirmation window shows exactly what will move and where, so nothing happens by accident.

It has a modern dark look that matches the panel, works great on phones, and every icon is drawn with CSS, so there are no images or emoji to load.

---

## What it does

| Area | Highlights |
|---|---|
| **Moving files** | Cut and paste across any folders, a "Move to" shortcut, and a confirmation window that lists every item with its From and To locations |
| **Choosing a destination** | Type a path or browse with Back, Root and This folder buttons. Leave it blank to move to the server root. Folders that do not exist yet are created for you |
| **Staying safe** | Name clashes are skipped and listed, a folder can never be moved into itself, and the real server permissions always apply |
| **Navigating** | Breadcrumbs, an Up button, a live filter, and a switch to show or hide dotfiles |
| **Managing** | Create folders, create empty files, and upload several files at once with a progress bar |
| **Built-in Move dialog** | The panel's own Move dialog gets a folder browser with Back and Root buttons too |
| **Look and feel** | Dark cards, rounded corners, subtle borders, smooth animations, loading placeholders, bottom sheets on mobile, and respect for reduced-motion settings |

---

## How to use it

1. Open any server and choose **Easy Poll** from the server menu.
2. Browse to the folder that holds your files and tick the ones you want.
3. Press **Cut**, or press **Move to** if you already know where they should go.
4. Open the destination folder and press **Paste here**.
5. Check the confirmation window, adjust the destination if needed, and press **Move**.

Tip: leaving the destination empty, or typing a single dot, sends the files to the server's main folder.

---

## For admins

Open the extension's page in the admin area to personalise it:

- Accent colour and warning colour
- Corner roundness
- Page title
- Whether hidden dotfiles are shown by default

---

## Safety and permissions

- Easy Poll uses the panel's own file system, so users can only do what their server permissions already allow.
- Moves never overwrite existing files. Anything that would clash is skipped and clearly listed.
- Easy Poll never deletes your files.

---

## Requirements

- A Pterodactyl panel with the Blueprint framework installed
- A modern browser (desktop or mobile)

---

## Installation

Install it the same way as any other Blueprint extension: add the extension package to your panel through the Blueprint installer, then refresh your browser with a hard reload so the new interface loads.

To update, remove the old version, install the new one, and hard reload again.

---

## Credits

Made by **Pawan**.

- Discord: allay_gaming_x
- GitHub: ALLAY-XD-20

If Easy Poll saves you time, consider leaving a star on the repository.

<p align="center"><sub>Easy Poll for Pterodactyl and Blueprint</sub></p>
