# IPTV Malaysia Auto Update

This repository hosts an automatically updating IPTV M3U file for various Malaysian TV channels. The M3U file is updated daily using a GitHub Action workflow.

## Features

- **Auto-update IPTV list:** The IPTV channel list is automatically generated using a Python script and updated daily using GitHub Actions.
- **Wide range of channels:** Includes popular Malaysian TV channels like TV1, TV2, TV3, and more.
- **Easy to integrate:** You can use the generated M3U URL directly in IPTV apps or players like VLC, Kodi, or TiviMate.

## Structure

The repository includes the following files:

- **`iptv_update.py`**: A Python script that generates the M3U file with the latest IPTV links.
- **`IPTV_Malaysia.m3u`**: The generated M3U file with all the channels.
- **`.github/workflows/update_iptv.yml`**: A GitHub Actions workflow that runs the update process daily.
  
## How to use

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/iptv-malaysia.git
   ```

2. **Run the script manually (optional):**
   To generate the M3U file locally, run the Python script:
   ```bash
   python iptv_update.py
   ```

3. **GitHub Actions:**
   The M3U file will automatically be updated daily at 3:00 AM UTC. You can trigger it manually by going to the **Actions** tab in GitHub and running the `Update IPTV M3U` workflow.

4. **Use the M3U link:**
   - Once the file is updated, you can use the generated `IPTV_Malaysia.m3u` file in your IPTV player.
   - Alternatively, you can set up GitHub Pages to serve the M3U file as a URL.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

