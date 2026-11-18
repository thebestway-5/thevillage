# COFFEE VILLAGE 2026 — README GUIDE

## 1. Folder Structure

Keep your website files arranged like this:

```text
Market2026/
│
├── index.html
│
├── README.md
│
└── assets/
    │
    ├── photos/
    │   ├── photo1.jpg
    │   ├── photo2.jpg
    │   ├── photo3.jpg
    │   ├── photo4.jpg
    │   ├── photo5.jpg
    │   ├── photo6.jpg
    │   ├── photo7.jpg
    │   ├── photo8.jpg
    │   ├── photo9.jpg
    │   ├── photo10.jpg
    │   └── home.jpg
    │
    └── music/
        ├── song1.mp3
        ├── song2.mp3
        └── song3.mp3
```

**IMPORTANT:** Keep `index.html` directly inside the `Market2026` main folder. Do not put it inside another folder.

---

## 2. How to Name Your Photos

Put all photos inside:

`assets/photos/`

| Filename | Used for |
|---|---|
| photo1.jpg | Coffee Van 1 logo |
| photo2.jpg | Coffee Van 2 logo |
| photo3.jpg | Coffee Van 3 logo |
| photo4.jpg | Coffee Van 4 logo |
| photo5.jpg | Coffee Van 5 logo |
| photo6.jpg | Coffee Van 6 logo |
| photo7.jpg | Coffee Van 7 logo |
| photo8.jpg | Coffee Van 8 logo |
| photo9.jpg | Coffee Van 9 logo |
| photo10.jpg | Coffee Van 10 logo |
| home.jpg | HOME glass coffee house photo |

### Photo naming rules

- Use exactly the filenames shown above.
- You may use `.jpg`, `.png`, or `.webp`; update the matching `logoImage` path in `index.html` if you change the extension.
- Use lowercase letters.
- Do not add spaces or extra numbers.
- Keep the same filenames when replacing photos.

For example, if you want to change Coffee Van 3's logo, simply replace `photo3.jpg` with your new image. Keep the filename `photo3.jpg`.

---

## 3. How to Name Your Music

Put your music files inside:

`assets/music/`

| Filename | Music |
|---|---|
| song1.mp3 | Music track 1 |
| song2.mp3 | Music track 2 |
| song3.mp3 | Music track 3 |

### Music replacement rules

To change the music, replace the existing MP3 file with your new music file.

For example:

- New music for track 1 → `song1.mp3`
- New music for track 2 → `song2.mp3`
- New music for track 3 → `song3.mp3`

Keep the exact filenames so the website can find the music.

---

## 4. How to Replace Photos and Music

You do not need to change the HTML code if you are only replacing existing photos or music.

1. Open your `Market2026` folder.
2. Open `assets`.
3. Open `photos` or `music`.
4. Replace the old file with your new file.
5. Make sure the new file has exactly the same filename.
6. Save your changes.

Example:

```text
Old photo3.jpg → Delete or replace
New photo      → Rename to photo3.jpg
```

The website will use the new photo after you upload the changes.

---

## 5. How to Update Your Website Using Git Bash

Your GitHub website:

https://thebestway-5.github.io/Market2026/

Your GitHub repository:

https://github.com/thebestway-5/Market2026

### A. First time only — Clone your repository

If you have not downloaded the repository to your computer before, open Git Bash and run:

```bash
git clone https://github.com/thebestway-5/Market2026.git
```

Then enter the project folder:

```bash
cd Market2026
```

### B. Next time — Update existing files

If you already have the `Market2026` folder on your computer, do not clone it again.

Open Git Bash inside your existing `Market2026` folder.

Run these commands:

**Step 1 — Check your folder**

```bash
pwd
```

**Step 2 — Get the latest version from GitHub**

```bash
git pull origin main
```

**Step 3 — Add all your changes**

```bash
git add -A
```

**Step 4 — Save your update**

```bash
git commit -m "Update Coffee Village website"
```

**Step 5 — Upload to GitHub**

```bash
git push origin main
```

Your GitHub Pages website will update after GitHub finishes deploying.

---

## 6. Quick Update Commands

For normal future updates, you can copy and paste these four commands:

```bash
git pull origin main
git add -A
git commit -m "Update website"
git push origin main
```

If Git says there is nothing to commit, it means there are no new changes to upload.

---

## 7. Important Reminders

- Never delete `index.html`.
- Do not rename the `assets`, `photos`, or `music` folders.
- Keep photo and music filenames exactly the same.
- Keep your real photos and MP3 files inside the correct folders.
- Upload the entire project, including the `assets` folder.
- Do not upload only `index.html` if you have changed photos or music.
- After uploading, wait for GitHub Pages to finish deploying.
- Refresh your website with `Ctrl + F5` to see the latest version.

**Your website address:**

https://thebestway-5.github.io/Market2026/
