# Logistics & Technical Infrastructure Checklist

> **Purpose:** Ensure all hardware, network, and venue requirements are validated 48 hours and 30 minutes prior to workshop commencement.

---

## 1. Presenter & AV Equipment

- [ ] **Display Output:** HDMI / USB-C to HDMI adapter tested with venue projector.
- [ ] **Resolution & Aspect Ratio:** Verified at 1920×1080 (16:9). Projector text must be legible from the rear row (minimum 18pt font in code editors).
- [ ] **Audio & Microphones:** Collar/lapel or handheld wireless mic tested with speaker system (crucial for halls >40 seats).
- [ ] **Presentation Clicker / Remote:** Tested with spare AAA batteries.
- [ ] **Presenter Machine:** Chrome / Firefox updated; ad-blockers disabled on Overleaf/AI Studio; dark mode / high-contrast editor font enabled.

---

## 2. Venue & Power Infrastructure

- [ ] **Power Distribution:** Minimum 4–6 heavy-duty multi-plug surge strips distributed across student desk rows.
- [ ] **Room Layout:** Clear central and side aisles allowing roaming TAs to reach any seated student within 5 seconds.
- [ ] **Lighting Control:** Dimmer controls tested so screen projection is crisp without plunging the room into darkness.

---

## 3. Network & Connectivity Verification

- [ ] **Bandwidth Capacity:** Campus Wi-Fi verified to handle 50–100 concurrent HTTPS and WebSocket connections.
- [ ] **Firewall Whitelist:** Verify the institutional firewall does not block:
  - `https://www.overleaf.com` (and compilation WebSockets)
  - `https://aistudio.google.com` (and Google authentication endpoints)
  - `https://ai.google.dev`
- [ ] **Mobile Hotspot Fallback:** Lead facilitator has a dedicated phone hotspot tested as an emergency backup in case campus Wi-Fi drops out.

---

## 4. Offline Emergency Fallback Pack

In the event of complete campus internet collapse during the event:
- [ ] Offline slide deck (PDF format) stored on local USB flash drive.
- [ ] Local copy of `John_Doe_Resume.pdf` and weak flaws answer key on local desktop.
- [ ] Text files containing the Overleaf LaTeX template source code and master prompts available for local distribution via USB / local network.
