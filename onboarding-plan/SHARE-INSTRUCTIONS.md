# How to Get a Shareable Link for the Onboarding Plan

The onboarding plan is a set of **local HTML files**. To share it with everyone via a link, upload the **entire `onboarding-plan` folder** to one of the options below. After that, the link you share is the URL of your **main page** (see “What link to share” at the bottom).

---

## Option 1: Microsoft SharePoint / OneDrive (good for McKinsey)

1. Open your **SharePoint site** or **OneDrive** (e.g. the same place as your Microsoft Loop).
2. Create a **new folder** (e.g. `Onboarding-Plan`).
3. Upload the **entire contents** of this folder:
   - `index.html`
   - `training-schedule.html`
   - `assets/` (folder with images)
   - `fonts/` (folder with font files, if you use them)
4. **Share the folder** or the main page:
   - Right‑click the folder or `index.html` → **Share**.
   - Choose “Anyone with the link” or “People in [McKinsey] with the link” as needed.
   - Copy the link.

**What link to share:**  
Share the link that opens **index.html** (the main onboarding plan). If SharePoint gives you a folder link, add `/index.html` at the end if needed, or share the file link for `index.html` directly.

---

## Option 2: GitHub Pages (free public site)

1. Create a **GitHub** account (if you don’t have one): [github.com](https://github.com).
2. Create a **new repository** (e.g. `onboarding-plan`).
3. Upload all files from this folder (drag and drop or use Git).
4. Go to **Settings → Pages** → Source: **Deploy from a branch** → branch `main` → Save.
5. After a minute, your site will be at:  
   `https://<your-username>.github.io/onboarding-plan/`

**What link to share:**  
`https://<your-username>.github.io/onboarding-plan/`  
(or the same URL with `/index.html` at the end)

---

## Option 3: Netlify Drop (quick temporary or permanent URL)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. **Drag and drop** the entire `onboarding-plan` folder onto the page.
3. Netlify will give you a URL like `https://random-name-12345.netlify.app`.

**What link to share:**  
The URL Netlify shows (e.g. `https://random-name-12345.netlify.app`).

---

## Option 4: Your company’s internal web host

If McKinsey or your team has an **internal site** or **file share** where HTML can be opened in a browser (e.g. a team drive that serves web pages), upload this folder there and use the URL your IT or host provides.

**What link to share:**  
The URL that opens the main onboarding page (e.g. `https://internal-site.company.com/onboarding-plan/` or the path to `index.html`).

---

## What link to share (summary)

- **Share the URL that opens the main onboarding plan page** (the one with “Your Onboarding Plan”, phases, and the link to the Training Schedule).
- That page is **index.html**, so the link should end with `/index.html` or with `/` so the server shows `index.html` by default.
- Example:  
  `https://your-site.com/onboarding-plan/`  
  or  
  `https://your-site.com/onboarding-plan/index.html`

---

## Checklist before sharing

- [ ] All files uploaded: `index.html`, `training-schedule.html`, `assets/`, `fonts/`
- [ ] Link opens the main page (Welcome, Day 1, First Week, etc.)
- [ ] “Open Reboarding & Technical Training Schedule” opens the schedule page
- [ ] Images (e.g. Training_Photo.png, Training_Team.png) load if you use them

Once that works, you can share that one link with everyone.
