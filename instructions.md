Tips for syntax (signs, paths, image vs video etc)

# 🛠️ Markdown Syntax Tips for Your Portfolio

Use these formatting rules when writing your docs:
| Content Type        | Syntax Example                                   | Description                      |      |        |     |     |               |                       |
| ------------------- | ------------------------------------------------ | -------------------------------- | ---- | ------ | --- | --- | ------------- | --------------------- |
| 📸 Screenshot       | `![Alt Text](folder/image.png)`                  | Shows image inline               |      |        |     |     |               |                       |
| 📹 Loom Video Link  | `- [Video Title](https://loom.com/share/abc123)` | Opens Loom video in new tab      |      |        |     |     |               |                       |
| 🧷 Internal MD Link | `[Link Text](../folder/filename.md)`             | Links to another .md in repo     |      |        |     |     |               |                       |
| 📝 Checklist        | `- [ ] Item` and `- [x] Item`                    | Unchecked / Checked boxes        |      |        |     |     |               |                       |
| 🗂️ Table           | Use \`                                           | Col1                             | Col2 | `plus` | --- | --- | \` rows below | Markdown table format |
| 🔠 Headers          | `# H1` to `###### H6`                            | Section titles (use emojis too!) |      |        |     |     |               |                       |

---

## ✅ Screenshots

Paste like this:  
```md
![Alt text](screenshots/image-name.png)
✔️ Shows the image inline
⚠️ Do NOT add - [Link]() — that opens the image in a new tab only.

✅ Loom Video Links
Paste like this:- [Video Title](https://www.loom.com/share/your-link)
✔️ Renders a clean clickable title
⚠️ Do NOT use ![]() or it will show a broken icon.


✅ Internal Links
To link to other .md files inside your repo:
[Team Roles](project-docs/team-roles.md)

✅ Section Headers
Use ## or ### to organize your docs into sections:
## 📹 Video Walkthroughs  
### 🟢 User Story 1


✅ Checklist
Great for tasks:
- [x] Create Jira Epic  
- [ ] Add User Story


✅ Tables
Use pipes (|) to format tables:
| Name | Role         |
|------|--------------|
| Alex | Admin        |
That’s it! Keep this file handy in all your repos so you never forget the right signs.

---

template-repo/
│
├── readme-template.md
├── docs-template.md
├── instructions.md
└── assets/ (optional images or placeholder examples)

