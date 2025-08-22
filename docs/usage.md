# Usage Guide

## Installing the Script
1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Add the script from this repo.
3. Reload CircleFTP.

## Using the Playlist Maker
- Navigate to a **series/season page**.
- If media files are detected, a **UI box** appears (bottom-right).
- Select the desired season from the dropdown.
- Click **Download** to save the `.xspf` playlist.

## Opening Playlist
- Use **VLC Media Player**, **Kodi**, or any player supporting XSPF.
- The playlist will contain all episode links.

## Notes
- Limited to **1000 links** max.
- Titles are auto-sanitized for safe filenames.
- Script only injects if **media links are detected**.
