# Profile editing guide

You will almost always edit **one file only: `README.md`**. Everything below tells you the exact words to look for.

**How to edit on GitHub:** open your profile repo → click `README.md` → click the pencil icon (✏️) → press **Ctrl+F** and search for the words in quotes → change them → click **Commit changes**.

---

## 0. First-time upload

1. Open the repo `Tanmay-Deore/Tanmay-Deore` on github.com.
2. **Add file → Upload files**. Drag in `README.md`, `PROFILE-EDITING-GUIDE.md`, the whole `assets` folder and the `.github` folder from this kit. Commit.
   * If the `.github` folder does not upload, use **Add file → Create new file**, type `.github/workflows/snake.yml` as the name and paste in the file contents.
3. Optional clean-up of the old beige design (each file: open it → trash can icon → commit). These are no longer used: `HOW_TO_USE.txt`, `assets/header.svg`, `assets/typing.svg`, `assets/stack.svg`, `assets/project-1.svg`, `assets/project-2.svg`, `assets/project-3.svg`, and the seven `assets/h-*.svg` files (`h-about`, `h-stack`, `h-roadmap`, `h-projects`, `h-activity`, `h-mindset`, `h-connect`).
4. Go to the **Actions** tab → **Generate Profile Graphics** → **Run workflow**. This refreshes the snake and activity graph in the new colours.
5. Open your profile page (github.com/Tanmay-Deore) and check it. Click the PanicX live demo link once.

---

## 1. Change HTML, CSS or Python from IN PROGRESS to COMPLETED

1. In `README.md`, search for **`EDIT ZONE 1`**.
2. Below it you will see:
   ```
   <code>HTML — IN PROGRESS</code>
   <code>CSS — IN PROGRESS</code>
   <code>Python — IN PROGRESS</code>
   ```
3. Change only the words after the dash, for example `HTML — IN PROGRESS` → `HTML — COMPLETED`.
4. Do the same for the roadmap: search **`EDIT ZONE 3`**. Use one of `IN PROGRESS`, `UP NEXT`, `PLANNED`, `COMPLETED` (for example `STAGE 01 — COMPLETED`).
5. Optional: add a line at the top of the learning log (search **`LEARNING LOG`**), like ``- `2026-11-20` — Finished HTML``.

The sprint dates are under **`SPRINT DATES`**. Nothing in the `assets` folder needs editing for any of this.

---

## 2. Add a new technology

1. Search **`EDIT ZONE 2`** in `README.md`.
2. Copy any one line that looks like this:
   ```
   <img src="assets/icons/python.svg" width="96" alt="Python">
   ```
3. Paste it into the group you want (CURRENTLY LEARNING, UP NEXT or FUTURE GOALS) and change the file name and the `alt` text, for example `assets/icons/mysql.svg` and `alt="MySQL"`.
4. Ready-made icon files you can use right now: `bootstrap, c, cpp, css, databases, docker, express, fastapi, figma, firebase, flask, git, github, html, java, javascript, linux, mongodb, mysql, netlify, nextjs, nodejs, npm, postgresql, postman, python, react, sqlite, supabase, tailwind, threejs, typescript, vercel, vite`.
5. Need an icon that is not in the list? Ask Claude for it, or just write the technology in plain text for now.

## 3. Move a technology from UP NEXT to CURRENTLY LEARNING

1. Search **`EDIT ZONE 2`**.
2. Cut the whole `<img ... alt="JavaScript">` line from the UP NEXT group (select the line, Ctrl+X).
3. Paste it inside the CURRENTLY LEARNING group (Ctrl+V). Commit.

## 4. Add a new project

**Easiest way (text only):** search **`PROJECT LINKS`** in `README.md`, and add a link line like this next to the others:
```
<a href="https://github.com/Tanmay-Deore/YOUR-REPO-NAME"><b>Project name · Repository</b></a>
```
**Nicer way (a card like Avenza and PanicX):**
1. Open `assets/project-template.svg` in any text editor (even Notepad).
2. Change only these pieces of text: `Project Name`, `tech · tech · tech`, the three description lines, and `TYPE`. Save it as `assets/project-yourname.svg`, and upload it.
3. In `README.md`, search `assets/project-panicx.svg`, copy that whole `<a ...><img ...></a>` line, and change the repo link and the image file name.
4. Keep the featured section to three projects at most.

## 5. Update your LinkedIn link or email

* **LinkedIn:** search `linkedin.com/in/`. It appears **twice** (under the hero and in CONTACT). Replace the link in both.
* **Email:** search `mailto:`. Replace the address after it (one place, in CONTACT).

## 6. Change the tagline

Search **`EDIT ZONE — TAGLINE`**. Change the sentence on the next line, between `<i>` and `</i>`: `Learning, building and improving every day.`

## 7. Update "Currently building"

Search **`EDIT ZONE 4`**. Edit the text in the table: the middle column is the status label (`IN PROGRESS`, `ONGOING`, `COMPLETED`), the right column says what you are doing.

---

## If something looks wrong

* **A broken image icon:** a file name has a typo, or the file is not in the `assets` folder. Names are case-sensitive.
* **Old colours still showing on the snake or graph:** run the workflow again (Actions tab → Run workflow) and refresh after a minute.
* **Stats card missing:** the outside service may be down. It is safe to delete just that `<img>` block (see `EXTERNAL-SERVICES.md`).
* **Never edit** the files in `assets` unless this guide tells you to.
