```markdown
# Installation Guide 🚀

## Prerequisites
- Linux, macOS, or Windows with WSL
- Bash shell
- Git (for installation)
- Nextcloud account (optional but recommended)

## Method 1: Git Clone (Recommended)
```bash
git clone https://github.com/linux-finn/jot-notes.git
cd jot-notes
chmod +x jot
sudo cp jot /usr/local/bin/
jot setup
```

## Method 2: Direct Download
```bash
curl -O https://raw.githubusercontent.com/linux-finn/jot-notes/main/jot
chmod +x jot
sudo cp jot /usr/local/bin/
jot setup
```

## Nextcloud Setup
1. Install Nextcloud desktop client
2. Run `jot setup` - auto-detects Nextcloud folder
3. Start creating: `jot "My first note"`

## Mobile Setup (QuillPad)
1. Install QuillPad from Play Store
2. Add Nextcloud account
3. Navigate to Notes/Jot/ folder
4. Edit any file created by Jot CLI

## Troubleshooting
- Command not found: Check PATH includes /usr/local/bin
- Permission denied: Run chmod +x on the script
- Nextcloud not found: Edit script to set custom path
```
