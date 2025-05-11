# Custom Pi-hole Blocklists

A personal collection of curated blocklists for Pi-hole, focused on blocking ads, tracking, and gambling domains - but mostly gambling.

## Table of Contents
- [Description](#description)
- [How to Use](#how-to-use)
- [List Format](#list-format)
- [Updates](#updates)
- [Disclaimer](#disclaimer)
- [License](#license)
- [Contact](#contact)

## Description
A purely personal list(s) manually compiled by me and intended only for use by me for adding to my Pi Hole setup.

## How to Use
1. Copy the raw URL of the desired blocklist (e.g., `https://raw.githubusercontent.com/yourusername/yourrepo/main/blocklist.txt`).
2. In Pi-hole, go to **Group Management > Adlists**.
3. Paste the URL and click **Add**.
4. Run `pihole -g` to update gravity.

## List Format
- Plain text, one domain per line.
- Lines starting with `#` are comments and ignored by Pi-hole.
- Blank lines are allowed.

## Updates
Random and unscheduled

## Disclaimer
Use these lists at your own risk. This project is not affiliated with Pi-hole or any third-party organizations.

## License
none

## Contact
TBA

## Last Updated
This README was last updated on 2025-05-11.
