<h1 align="center">EXPO ANNOUNCEMENT</h1>

<p align="center"><b>Smooth, modern announcements and email for your Pterodactyl panel.</b><br>Tell your users what matters, the moment it matters.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pterodactyl-Panel-0e1117?style=for-the-badge&labelColor=1f2430&color=3b82f6" alt="Pterodactyl">
  <img src="https://img.shields.io/badge/Blueprint-Extension-0e1117?style=for-the-badge&labelColor=1f2430&color=8b5cf6" alt="Blueprint">
  <img src="https://img.shields.io/badge/Version-1.0.0-0e1117?style=for-the-badge&labelColor=1f2430&color=22c55e" alt="Version">
  <img src="https://img.shields.io/badge/Author-Pawan-0e1117?style=for-the-badge&labelColor=1f2430&color=f59e0b" alt="Author">
</p>

---

## About

Expo Announcement lets panel admins show eye-catching announcement banners to every user, and send emails to all users or just the ones they choose, without leaving the panel.

Banners slide in with smooth animations, come in six styles for different situations, and can be scheduled, linked, and dismissed. Emails go out through the SMTP settings your panel already uses. The whole interface is dark, modern, mobile-friendly, and every icon is drawn with CSS, so there are no images or emoji to load.

---

## Announcement styles

| Style | Best for | Look |
|---|---|---|
| **Info** | General notices | Calm blue |
| **Success** | Good news, an issue fixed | Fresh green |
| **Warning** | Upcoming maintenance, things that need attention | Amber with a gentle attention wiggle |
| **Danger** | Outages and critical problems | Red with a pulsing glow |
| **Quick** | Short heads-ups | Compact, hides itself after a few seconds with a countdown bar |
| **Volt** | Big news, events, launches | Purple gradient with a moving shine |

---

## Features

**Announcements**
- Title, message, and an optional link button
- Schedule when an announcement starts showing and when it disappears
- Turn announcements on or off without deleting them
- Choose whether users can dismiss each one
- Most urgent styles are shown first, and extra banners tuck behind a "more" button
- Live preview while you write
- Shown on every panel page for logged-in users

**Email**
- Send to all users, admins only, or a hand-picked list with search
- Write a title, a plain text version, and an HTML version
- Personalise messages with each user's name, email, and the panel name
- Optional dark email template, a preview window, and a test email to yourself
- A confirmation step before anything is sent
- Uses the mail settings already configured in your panel

**Customisation**
- Pick the colour of every style
- Set how many banners can show at once
- Set how long Quick banners stay
- Switch animations on or off

---

## How to use it

**Posting an announcement**
1. Open the extension in the admin area and stay on the Announcements tab.
2. Pick a style, write your title and message, and add a link or schedule if you want.
3. Check the live preview and press Publish.

**Sending an email**
1. Open the Send email tab.
2. Choose who receives it.
3. Write the title and the content, then preview it.
4. Send a test to yourself, and when you are happy, press Send email.

---

## Good to know

- Announcement text is always shown as plain text, so it cannot inject anything into your panel.
- When a user dismisses a banner, it is remembered in their own browser. Editing an announcement shows it again.
- Emails need working mail settings in your panel. If they are missing, the extension tells you instead of pretending to send.
- Very large user lists are best emailed in groups using the hand-picked option.

---

## Requirements

- A Pterodactyl panel with the Blueprint framework installed
- Working mail settings in the panel, only if you want to send emails

---

## Installation

Install it the same way as any other Blueprint extension: add the extension package to your panel through the Blueprint installer, then refresh your browser with a hard reload so the new interface loads.

To update, remove the old version, install the new one, and hard reload again.

---

## Credits

Made by **Pawan**.

- Discord: allay_gaming_x
- GitHub: ALLAY-XD-20

If Expo Announcement helps your community, consider leaving a star on the repository.

<p align="center"><sub>Expo Announcement for Pterodactyl and Blueprint</sub></p>
