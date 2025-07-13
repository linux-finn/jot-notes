```markdown
# Jot 📝 - Simple Note-Taking CLI

A streamlined command-line tool for notes, tasks, and documents that syncs seamlessly with Nextcloud.

## ✨ Features

- 📝 **Quick notes** - Capture thoughts instantly
- 📋 **Task management** - Create and track todos with checkboxes
- 📄 **Document creation** - Structured documents with templates
- 🔍 **Powerful search** - Find anything across all your content
- 📱 **Mobile editing** - Perfect sync with QuillPad and Nextcloud Notes
- 🔄 **Cross-device sync** - Access everywhere via Nextcloud
- 📁 **Smart organization** - Automatic categorization and archiving

## 🚀 Quick Start

```bash
# Download and install
git clone https://github.com/linux-finn/jot-notes.git
cd jot-notes
chmod +x jot
sudo cp jot /usr/local/bin/

# Setup and start using
jot setup
jot "My first note"
```

## 📋 Commands

| Command | Description |
|---------|-------------|
| `jot "Note title"` | Create a quick note |
| `jot task "Task name"` | Create a task with checkboxes |
| `jot doc "Doc title"` | Create a structured document |
| `jot find "keyword"` | Search all notes, tasks, and docs |
| `jot list` | Show recent items (all types) |
| `jot list tasks` | Show all tasks |
| `jot list docs` | Show all documents |
| `jot done "task name"` | Mark task complete and archive |
| `jot setup` | Initial setup |
| `jot help` | Show help menu |

## 📱 Mobile Access

Jot works beautifully with mobile apps through Nextcloud sync:

- **QuillPad** (Android) - Full folder navigation and editing
- **Nextcloud Notes** (iOS/Android) - Official app integration
- **Any text editor** that supports Nextcloud

Edit your notes on mobile and they sync automatically!

## 🗂️ File Organization

```
~/Nextcloud/Notes/Jot/
├── notes/              # Quick notes and ideas
├── tasks/              # Todo items with checkboxes
├── docs/               # Structured documents
└── archive/            # Completed tasks
```

## 📝 Note Templates

### Quick Note
```
📝 Meeting with Sarah

Created: Saturday, July 13, 2025 at 22:45

---

[Your content here]
```

### Task
```
📋 Task: Call dentist

Created: Saturday, July 13, 2025 at 22:45
Status: [ ] Pending

---

[ ] Call dentist

Notes:

Priority: 
Due Date: 
Tags: 
```

### Document
```
📄 Project Planning Guide

Created: Saturday, July 13, 2025 at 22:45
Author: linuxfinn

---

# Project Planning Guide

## Overview

## Details

## Notes

---
Last updated: 2025-07-13 22:45
```

## 🔍 Search Examples

```bash
# Find all notes about meetings
jot find "meeting"

# Search for specific tasks
jot find "dentist"

# Look for project-related content
jot find "project"
```

## ✅ Task Management

```bash
# Create tasks
jot task "Finish quarterly report"
jot task "Buy groceries"

# List all tasks
jot list tasks

# Mark tasks complete
jot done "groceries"
jot done "quarterly"
```

## 🛠️ Requirements

- **Bash shell** (Linux, macOS, WSL)
- **Nextcloud account** (for sync - optional but recommended)
- **Text editor** (nano, vim, kate, etc.)

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🌟 Why Jot?

> "Jot it down before you forget"

Jot helps you capture and organize information with:
- **Speed** - Create notes in seconds
- **Simplicity** - Intuitive commands that make sense
- **Flexibility** - Notes, tasks, and docs in one tool
- **Portability** - Plain text files that work everywhere
- **Reliability** - Your data, your files, your control

---

**Start organizing your thoughts with `jot`** 📝
```
