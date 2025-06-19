Tips for syntax (signs, paths, image vs video etc)
# 🛠️ Markdown Syntax Tips for Your Portfolio

Use these formatting rules when writing your docs:

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

## 🟨 `docs-template.md` — Example for any `.md` documentation

This is a copyable structure for anything like Epics, Setup, Team Roles, etc.

```markdown
# 📘 [Replace This With Your Document Title]

> Example: Epics & User Stories  
> ✏️ This file contains Epics and their related Stories used in Jira.

---

## 🧩 EPIC: [Replace with Epic Name]

**Goal:** [State the purpose of this Epic clearly]  
**Owner:** [Name or Role]  
**Status:** [To Do / In Progress / Done]

---

### 🟢 User Story 1: [Short summary]
**Summary:** As a [Role], I want to [what they want] so that [reason].  
**Acceptance Criteria:**
- [ ] Point 1
- [ ] Point 2
- [ ] Point 3

**Assignee:** [Name]  
**Due Date:** [Date]  
**Parent Epic:** [Epic Name]

📸 Screenshot:  
```md
![Story Screenshot](../screenshots/your-screenshot.png)
📝 Notes
Add any notes or comments you want future you to remember.

---

### ✅ You’re Ready

You now have:

- A reusable `README.md` with inline instructions
- An `instructions.md` with formatting rules and signs
- A `docs-template.md` to copy for any detailed markdown file

Would you like me to:
- ✅ Package all 3 files into a `.zip` you can upload?
- ✅ Guide you to add them manually into a GitHub repo?

Let me know what works best!
