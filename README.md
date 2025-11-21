# GLauncher Web

This repository contains the **marketing and download page** for **GLauncher**, a Windows app by [Pine Street Technology](https://github.com/PineStreetTechnology) that lets you group applications together and launch them all at once.

GLauncher is ideal for:

- Gamers
- Sim racers and sim flyers
- Developers and admins
- Office and knowledge workers

Anyone who regularly opens the same set of apps can save time by launching them as a group instead of starting each one individually.


## Downloading GLauncher

The **Download for Windows** buttons on the site point to the latest installer hosted as a **GitHub Release asset** in the main app repository:

- Repo: [`PineStreetTechnology/GLauncher`](https://github.com/PineStreetTechnology/GLauncher)
- Latest installer URL (used by the site):

  ```text
  https://github.com/PineStreetTechnology/GLauncher/releases/latest/download/GLauncher-Setup.exe
  ```

GitHub Releases provides **download counts** for the installer asset.



## Installing GLauncher (for users)

1. Go to the GLauncher website (GitHub Pages URL for this repo).
2. Click **Download for Windows**.
3. When the download finishes, run `GLauncher-Setup.exe`.
4. Follow the standard Windows installer steps.
5. After installation, you can launch **GLauncher** from the Start menu or a desktop shortcut (if created by the installer).

Once running, you can:

- Create groups for common workflows (e.g., *Sim racing*, *Coding session*, *Morning office*).
- Add apps to a group from the curated list or by browsing to executables.
- Control launch order, command-line flags, and whether each app should run as administrator.
- Optionally start GLauncher with Windows and keep it available from the system tray.

For more details about the app itself, see the main project repository:

- <https://github.com/PineStreetTechnology/GLauncher>

---

## GitHub Pages setup

To (re)enable GitHub Pages for this repository:

1. Push this repo to GitHub (if you’re working locally).
2. In the GitHub UI, open **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select the branch that contains `index.html` (typically `main`) and use the **root** (`/`) folder.
5. Save.

GitHub will build and host the site. After a few minutes it will show the public URL, which you can share as the official GLauncher download page.

