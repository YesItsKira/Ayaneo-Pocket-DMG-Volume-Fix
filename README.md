# Ayaneo Pocket DMG Volume Root Scripts

A small, fix for smoother speaker volume steps on the Ayaneo Pocket DMG.

This repo provides:
- a tuned "default_volume_tables_SMOOTH.xml"
- AyaSettings Root Scripts
  - `Aya_ON.sh` (applies the fix)
  - `Aya_OFF.sh` (reverts to stock)
  - `Aya_STATUS.sh` (displays if the fix is on or off)

It works by binding a modified volume table over the system table so the audio service can actually see it without us needing to edit the stock file.

---

Persistence:
- This is a **temporary runtime mount**. **A reboot clears it.**
- After reboot, run `Aya_ON.sh` again.

## Installation

1. Download the release ZIP from this repo.
2. Extract the files to the location below:
3. 
   -> Internal Storage -> Download -> KirasPocketDMGVolumeFix (.sh and .xml files should be in here)

   You should end up with:
   `/sdcard/Download/KirasPocketDMGVolumeFix/`
   - `default_volume_tables_SMOOTH.xml`
   - `Aya_ON.sh`
   - `Aya_OFF.sh`
   - `Aya_STATUS.sh`

---

## Usage (AyaSettings)

Open:

AyaSettings → Device → Root Script 

### Apply fix
- Run: `Aya_ON.sh`

### Check status
- Run: `Aya_STATUS.sh`
Should show:
- `STATUS: ON` or `STATUS: OFF`

### Revert to stock
- Run: `Aya_OFF.sh`

---

I dont charge for any of my projects and make them free for the community. 
If you like my work, I would really appreciate a donation!
https://ko-fi.com/yesitskira

Thank you :)
