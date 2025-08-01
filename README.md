# 📝 Open Journal

Welcome to my open-source, terminal-based daily journal 
Each day, I log my thoughts, learnings, and reflections in plain-text files. The goal is to document personal growth openly, encourage consistency, and share thoughts with the world — all using the Linux terminal and GitHub.

---

## 📂 Folder Structure

- `YYYY-MM-DD.txt`: Journal entry for the specific date
- `journal.sh`: Bash script to create entries via terminal
- `README.md`: This file

---

## 🚀 How to Use

### 📋 Requirements:
- A Linux terminal (tested on Linux Mint)
- Bash (`journal.sh` is a bash script)
- `git` (for pushing entries to GitHub)

---

### 🛠️ Usage

1. Clone this repo:
   ```bash
   git clone https://github.com/Arnazz10/open-journal.git
   cd open-journal
   ```

2. Make the journal script executable:
   ```bash
   chmod +x journal.sh
   ```

3. Run the script to write a new journal entry:
   ```bash
   ./journal.sh
   ```

4. Your entry will be saved in:
   ```
   ./YYYY-MM-DD.txt
   ```

5. To push it to GitHub:
   ```bash
   git add .
   git commit -m "Journal entry for $(date +%F)"
   git push
   ```

---

## ✨ Features

- Plain-text, readable journal entries
- Terminal-only, no GUI required
- Automatically names entries by date
- Timestamped lines for clarity
- Open-source and version controlled with Git

---

## 💡 Future Ideas

- Markdown formatting
- Auto-tagging entries with keywords
- HTML view of journal with a static site generator
- Daily reminders via `cron`

---

## 📖 License

This journal is open-source under the **Creative Commons CC0 (Public Domain)** license.  
Feel free to read, use, fork, or contribute.  
*(Optional: Add LICENSE file if you'd like)*

---

## 🙌 Author

**Arnab Roy**  
🌐 [github.com/Arnazz10](https://github.com/Arnazz10)



