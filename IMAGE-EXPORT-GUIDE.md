# WordPress Image Export Guide

## Images needed for the static site

| File to create         | Source on WordPress site                                                |
|------------------------|-------------------------------------------------------------------------|
| public/images/hero.jpg | https://cazenoviaclub.org/wp-content/uploads/2023/05/cropped-Screenshot-2023-05-08-at-10.05.06-AM.png |
| public/images/logo-white.png | https://cazenoviaclub.org/wp-content/uploads/2023/05/cropped-Caz-CLub-logo_white.png |
| public/images/staff-tina.png | https://cazenoviaclub.org/wp-content/uploads/2025/05/TinaMac-855x1024.png |
| public/images/staff-brandon.jpg | https://cazenoviaclub.org/wp-content/uploads/2025/05/BrandonQuilty-1-855x1024.jpg |
| public/images/staff-dave.jpg | https://cazenoviaclub.org/wp-content/uploads/2024/05/IMG_2904-769x1024.jpg |

## How to download them

### Option A – Direct download (quickest)
Right-click each URL above, open in a browser, right-click the image → Save Image As…
Save to the `public/images/` folder using the filename shown in the table.

### Option B – WordPress Media Library export
1. Log into your WordPress dashboard
2. Go to **Media → Library**
3. Switch to List view
4. Select all images → Bulk Actions → Download (if your theme supports it)
   — OR use the **Export Media Library** plugin (free on WordPress.org)

### Option C – FTP / cPanel
If you have FTP or cPanel access to your hosting:
1. Connect to your server
2. Navigate to `wp-content/uploads/`
3. Download the entire folder to `public/images/`

## After downloading
- Place all files in `public/images/`
- The site is pre-wired to look for the filenames in the table above
- Any future images uploaded via Decap CMS will automatically go into `public/images/`
