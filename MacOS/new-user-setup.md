# Lab 02 – macOS New User Setup & Hardening

**Goal:** Simulate setting up a new employee’s MacBook and applying basic security and usability settings.  
**Skills:** Device provisioning, macOS configuration, security hardening, user-focused setup, documentation.

---

## Scenario

A new employee has just joined the company and received a MacBook.  
IT needs to:

- Create or configure their user account.
- Apply basic security settings.
- Install essential apps.
- Make the Mac comfortable and productive for daily work.

For this lab, the “new employee” MacBook is my own device, but I treat it as if I am preparing it for someone else.

**Environment**

- Device: MacBook (Apple silicon)
- OS: macOS (version: insert your version here)
- Network: Home Wi‑Fi
- Account Type: Standard user (recommended for normal employees)

---

## Objectives

- Set up or review a standard user account appropriate for daily work.
- Configure basic security: password, screen lock, FileVault, firewall.
- Install and organize essential productivity tools.
- Make sure the system is easy to use for a non-technical employee.
- Document the process as if handing it off to another IT teammate.

---

## Step 1 – User Account Setup

1. Open **System Settings → Users & Groups**.
2. Confirm there is an account for the user:
   - If needed, create a **standard** (non-admin) account for the employee.
   - Choose a clear username and full name.
3. Set a strong password and password hint (if appropriate).

**Result:** User has a dedicated, non-admin account ready for daily use.

---

## Step 2 – Basic Security Configuration

### 2.1 Screen Lock & Password

1. Go to **System Settings → Lock Screen**.
2. Set screen to require a password **immediately** or after a short delay (e.g., 1 minute) when the Mac sleeps or the screen saver begins.
3. Enable automatic lock when the display is off.

**Reasoning:** Prevents unauthorized access if the employee walks away from their desk.

---

### 2.2 FileVault Disk Encryption

1. Go to **System Settings → Privacy & Security → FileVault**.
2. Turn **FileVault** on if it is not already enabled.
3. Save the recovery key in a safe place (document the policy—e.g., stored in company password manager).

**Reasoning:** Protects data at rest if the laptop is lost or stolen.

---

### 2.3 Firewall

1. Go to **System Settings → Network → Firewall** or **Privacy & Security → Firewall** (depending on macOS version).
2. Turn the **Firewall** on.
3. Review any allowed apps; keep defaults or remove unnecessary allowances.

**Reasoning:** Adds a basic layer of protection against unwanted incoming connections.

---

## Step 3 – System Updates

1. Open **System Settings → General → Software Update**.
2. Check for macOS updates and apply any available security or OS updates.
3. Enable **automatic updates** if appropriate.

**Result:** System is up to date with the latest patches.

---

## Step 4 – Install Essential Applications

Install a small, realistic toolset for a new employee (adjust based on your interests):

- Browser: Chrome or Firefox (if different from default).
- Communication: Slack / Teams / Zoom.
- Productivity / Office: Microsoft 365 or Google Workspace tools (web), note-taking app (Notion, Obsidian, Apple Notes).
- Developer / IT Tools (optional): VS Code, Homebrew, basic CLI tools.

For each app:

1. Download from the official site or App Store.
2. Install for the user.
3. Sign in if needed and confirm basic functionality (e.g., test a call in Zoom, sign into Slack).

**Result:** The Mac is ready for common communication and productivity tasks.

---

## Step 5 – Usability & Quality-of-Life Settings

Make the device more comfortable for daily use without compromising security.

Examples:

- **Dock & Desktop**
  - Clean up the Dock (remove unused default apps, keep essentials).
  - Turn on “Automatically hide and show the Dock” if preferred.

- **Trackpad & Keyboard**
  - **System Settings → Trackpad**: adjust click, tracking speed, gestures.
  - **Keyboard**: enable key repeat, adjust shortcuts (e.g., Spotlight, screenshots).

- **Display**
  - Adjust display brightness, Night Shift, and appearance (light/dark mode) based on comfort.

Document what you changed and why.

---

## Step 6 – Basic Backup or Recovery Planning (Optional)

If you want to go a bit further:

- Set up **Time Machine** with an external drive (if available), or
- Document a simple backup approach the user should follow (cloud storage folder for important documents, etc.).

---

## Final Checklist

Before marking the lab complete, verify:

- [ ] User account created/confirmed (standard user, strong password).
- [ ] Screen lock and password required on wake.
- [ ] FileVault enabled.
- [ ] Firewall enabled.
- [ ] macOS up to date.
- [ ] Essential applications installed and opened at least once.
- [ ] Basic settings tuned for usability.
- [ ] Notes taken for what was configured.

---

## Tools Used

- macOS **System Settings**
  - Users & Groups
  - Lock Screen
  - Privacy & Security
  - Software Update
- App Store and official app websites
- Time Machine or cloud storage (optional)

---

## What I Learned

- How to set up a MacBook as if onboarding a new employee.
- How to balance security (encryption, screen lock, firewall) with daily usability.
- How to standardize a simple checklist so other IT teammates can repeat the setup consistently.
- How to document setup steps clearly so they can be turned into an internal knowledge base article later.
