# SENDER – Internal Team Messenger (MVP)

SENDER is a lightweight internal messenger designed for secure communication between colleagues inside a company.  
This repository contains an MVP front‑end prototype that demonstrates the core user flows for chats and file sharing.

> ⚠️ **MVP status:** this is a client‑side demo. All data is stored in browser memory and is reset on page reload.

---

## Features

- **Internal team chat**
  - One shared room that imitates a typical team channel
  - Support for short text messages
  - Basic message metadata (author, timestamp)

- **User management (demo)**
  - Sign‑in screen with corporate‑style login
  - Ability to add new users to the contact list in the sidebar
  - Visual indication of the current user

- **File sharing (Word, PDF, Excel, etc.)**
  - Attaching files to messages via file input
  - Displaying attached file name inside the message bubble
  - Simulated flow for document exchange (no real upload to a server in MVP)

- **Simple, clean UI**
  - Minimalistic layout focused on core workflows
  - Classic fonts, neutral color palette suitable for business use
  - Responsive layout for desktop and tablets

---

## Tech Stack

- **HTML5** – single‑page prototype
- **CSS3** – basic layout, typography and theming
- **Vanilla JavaScript** – simple state handling for:
  - login simulation
  - user list management
  - in‑memory chat and attachments

No external frameworks or build tools are required.

---

## Project Structure

(Adjust this section to match your actual files.)

```text
ISENDER/
├─ index.html        # Main SENDER MVP page (landing + login + chat demo)
├─ /assets           # (Optional) images, icons, etc.
└─ README.md         # Project documentation
