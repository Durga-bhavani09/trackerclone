# PHP Website Cloner (TrackerClone)

This project is a simple PHP-based Website Cloner tool that downloads a website and saves it locally.

It works similar to tools like HTTrack and is useful for learning web crawling and scraping concepts.

## Features
- Fetches webpage HTML using PHP cURL
- Extracts internal links automatically
- Downloads website files
- Saves pages locally for offline viewing

## Requirements
Before running the project make sure you have:

- XAMPP / Apache Server
- PHP installed
- Internet connection

## Installation

1. Clone the repository

git clone https://github.com/Durga-bhavani09/trackerclone.git

2. Move the project folder to XAMPP htdocs directory

Example:
C:\xampp\htdocs\trackerclone

3. Start Apache server from XAMPP Control Panel.

## How to Run

1. Open your browser.

2. Go to:

http://localhost/trackerclone

3. Enter the website URL you want to clone.

Example:
https://example.com

4. Click the download / clone button.

5. The website files will be saved in the project folder.

## Project Structure

```
trackerclone/
│
├── index.php              # UI for entering URL
├── crawler.php            # Main crawling logic
├── functions.php          # Helper functions
├── config.php             # Configuration file
├── test.php               # Testing file
│
├── downloads/             # Cloned websites storage
│   ├── facebook.com/
│   ├── instagram.com/
│   └── snapchat.com/
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│
├── README.md
└── LICENSE
```

## Disclaimer

This project is developed for educational purposes only. Do not use it to copy or misuse copyrighted websites.

## Author

Durga Bhavani ﻿#trackerclone
