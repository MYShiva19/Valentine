# How to Share Your Valentine Page as a Link

You have two easy options. Pick the one you prefer.

---

## Option 1: Netlify Drop (fastest – about 2 minutes)

**No account required** for a temporary link; sign up for a **permanent** link.

1. **Go to:** [https://app.netlify.com/drop](https://app.netlify.com/drop)

2. **Drag and drop** your entire `valentine` folder onto the page.
   - On Mac: open Finder, go to your home folder, find the `valentine` folder.
   - Drag the **folder** (the one that contains `index.html`) onto the Netlify Drop page.

3. Netlify will upload it and give you a **random URL** like:
   - `https://random-name-12345.netlify.app`

4. **Copy that URL** and send it to your wife (text, WhatsApp, email, etc.). When she opens it, she’ll see your Valentine page.

5. **Optional – permanent link and custom name:**
   - Sign up for a free Netlify account.
   - After dropping, you can change the site name in Site settings → Domain management → Options → Edit site name.
   - You can get something like: `https://your-valentine-2025.netlify.app`

---

## Option 2: GitHub Pages (free and permanent)

Good if you already use GitHub or want the project in a repo.

### One-time setup

1. **Create a GitHub account** (if you don’t have one): [https://github.com/join](https://github.com/join)

2. **Create a new repository:**
   - Go to [https://github.com/new](https://github.com/new)
   - Repository name: `valentine` (or e.g. `be-my-valentine`)
   - Set to **Public**
   - Do **not** add a README (we’re uploading your folder)
   - Click **Create repository**

3. **Upload your Valentine page:**

   **Option A – Using GitHub’s web interface (no Git needed):**
   - On the new repo page, click **“uploading an existing file”**.
   - Drag and drop the **contents** of your `valentine` folder (the `index.html` file and `HOSTING.md` if you want) into the browser.
   - Commit with a message like “Add Valentine page” and click **Commit changes**.

   **Option B – Using Git in Terminal:**

   ```bash
   cd /Users/yogashivamathivanan/valentine
   git init
   git add index.html
   git commit -m "Valentine page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/valentine.git
   git push -u origin main
   ```
   (Replace `YOUR_USERNAME` with your GitHub username.)

4. **Turn on GitHub Pages:**
   - In the repo, go to **Settings** → **Pages** (left sidebar).
   - Under **Source**, choose **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)**.
   - Save.

5. **Get your link:**
   - After a minute or two, the site will be at:
   - **https://YOUR_USERNAME.github.io/valentine/**
   - Example: if your username is `john`, the link is `https://john.github.io/valentine/`

6. **Send that link** to your wife.

---

## After you have the link

- Send it via **iMessage, WhatsApp, email**, or any app.
- She just taps or clicks the link and the Valentine page opens in her browser.
- No install or login needed for her.

---

## Quick comparison

|                | Netlify Drop      | GitHub Pages        |
|----------------|-------------------|---------------------|
| Speed          | Very fast         | A few minutes       |
| Account        | Optional          | GitHub account      |
| Link           | random or custom  | username.github.io/valentine |
| Best for       | “Just get a link” | Keeping code in Git |

For the quickest result, use **Option 1 (Netlify Drop)** and drag your `valentine` folder onto the page.
