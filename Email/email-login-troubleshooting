# Lab 01 – Email Login Troubleshooting (MacBook)

**Goal:** Practice diagnosing and resolving a common issue where a user cannot sign into their email on a MacBook.  
**Skills:** User interviewing, basic account troubleshooting, browser troubleshooting, documentation.

---

## Scenario

A user is working from home and cannot sign into their work email on their MacBook.

> “I’m trying to sign into my work email on my laptop, but it keeps saying my password is wrong. It works on my phone, just not here.”

**Environment**

- Device: MacBook (macOS)
- Location: Home network
- Email type: Web email in browser (e.g., Outlook Web / Gmail)
- Network: Home Wi‑Fi, other websites loading normally

---

## Initial Questions

I started by asking basic clarifying questions:

1. Can you sign into the same email on any other device (phone, tablet, another laptop)?
2. Did you change your email password recently?
3. Are you going to the correct sign‑in page (work email portal vs personal email)?
4. Are you seeing any specific error message? If so, what exactly does it say?

These questions help separate account problems (locked/incorrect password) from device or browser problems.

---

## Troubleshooting Steps

### 1. Verify internet connectivity

- Confirmed the user could open other websites like google.com and news sites.
- Since other sites worked, the issue was not a general network outage.

**Result:** Internet connection is working.

---

### 2. Confirm correct account and login page

- Asked the user to read the email address they were entering and checked spelling and domain.
- Verified they were on the correct sign‑in page for their work email (not a personal Gmail/Outlook page).

**Result:** Email address and login page were correct.

---

### 3. Rule out browser autofill issues

- Asked the user to open a **private/incognito window** in their browser.
- Had them type the email and password manually (no saved credentials / autofill).

**Result:** Login still failed with “incorrect password”.

This suggested either:
- The password was actually wrong, or
- The account might be locked/changed.

---

### 4. Check for recent password changes

- Asked if they had recently changed their email password on another device.
- User confirmed they updated their password on their phone a few days earlier.

**Result:** High chance the MacBook was still trying an **old password**.

---

### 5. Use account recovery / password reset

- Guided the user to click the provider’s **“Forgot password?”** or **“Can’t access your account?”** link.
- Walked through the password reset flow:
  - Verified their identity using recovery options (phone/email).
  - Set a new strong password.
- Had the user try signing in again in a private browser window with the new password.

**Result:** Login succeeded in private mode with the new password.

---

### 6. Update saved credentials

- Asked the user to close the private window and try again in a normal browser window.
- When prompted, had them:
  - Enter the new password.
  - Choose to update the saved password in the browser’s password manager.

**Result:** User could now sign in normally in their usual browser session.

---

## Root Cause

The user had previously changed their email password on another device (phone), but the MacBook’s browser was still using an **old saved password**. This caused repeated “incorrect password” errors even though the account itself was valid.

---

## Resolution

- Verified network connectivity and that other sites were working.
- Confirmed the correct account and login page were being used.
- Tested sign‑in in a private browser window to bypass saved credentials.
- Used the email provider’s password recovery flow to reset the password.
- Updated saved credentials in the browser so future logins use the new password.
- Confirmed successful sign‑in on the MacBook.

---

## Tools Used

- Web browser (Safari/Chrome)
  - Private/incognito mode
  - Password manager / saved passwords
- Email provider’s account recovery / “Forgot password” page

---

## What I Learned

- How to separate **account issues** from **device/browser issues** by testing login on multiple devices and in a private window.
- How older saved passwords in the browser can cause login failures even when the account works elsewhere.
- How to guide a user through an email password reset and then update saved credentials.
- How to document a help‑desk style ticket with scenario, steps, root cause, and resolution so another technician could follow the same process.
