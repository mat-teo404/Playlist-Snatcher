# PlaylistSnatcher

# Overview
This project was created to get higher quality music for my speakers on spotify without needing to pay for a subscription service. it works by using yt-dlp to download youtube videos in the best audio format that it can, which is m4a at the release of this version (1.0.0.).
## Disclaimer
A personal music management tool designed for educational and archival purposes. This project helps users organize and explore their Spotify playlists and profile data locally with better bitrate and codec.

⚠️ Important: This software is provided “as is” for personal, non-commercial use only. Downloading or distributing copyrighted content without permission may violate copyright laws. The author does not condone or encourage unauthorized use of this software and is not responsible for any misuse or legal consequences.

## License
This project is licensed under a custom [MIT Non-Commercial License](LICENSE.md).  
**Use is restricted to non-commercial, educational, or personal purposes only.**

## Requirements
* **ngrok** is already installed, but you need an account and to reserve a free static domain: [how to reserve a static domain](https://ngrok.com/blog-post/free-static-domains-ngrok-users)
* **spotify developer account** is free, just sign in at [this link](https://developer.spotify.com/dashboard) or at developer.spotify.com and follow the steps to create an account (steps will be in the installation tab)
* _PlaylistSnatcher_ uses **python**, **ffmpeg**, and **yt-dlp**, but installation is not needed due to being portable versions already installed.
* Thanks for downloading and using my project :)

## Installation
1. Create Ngrok account and [reserve a domain](https://ngrok.com/blog-post/free-static-domains-ngrok-users)
<img width="905" height="1073" alt="Screenshot 2025-07-18 193306" src="https://github.com/user-attachments/assets/fdca4266-5845-4f46-add3-ebc5121c958b" />
<img width="2047" height="613" alt="Screenshot 2025-07-18 193610" src="https://github.com/user-attachments/assets/a01ebe8a-5ecb-4336-b955-f6beab159e7a" />
2. go to spotify's developer dashboard and create an app, then put in your ngrok redirect domain name in as **Https://(your ngrok domain.app)/callback** and turn on web api and web playback sdk (may not be needed, but they worked for me)
3. go into PlaylistSnatcher\config.json and input your spotify client id and client secret id (both in spotify dev app), then put in the redirect uri **Https://(your ngrok domain.app)/callback**, your authtoken [here](https://dashboard.ngrok.com/get-started/your-authtoken), and your ngrok domain [here](https://dashboard.ngrok.com/domains)
4. run the *Playlist Snatcher.exe*
<img width="1508" height="591" alt="Screenshot 2025-07-18 194922" src="https://github.com/user-attachments/assets/d2beb501-a638-4d5b-87c4-d71a5045603d" />
5. if you get this error message, refresh until you see this screen:
<img width="1411" height="816" alt="Screenshot 2025-07-18 194936" src="https://github.com/user-attachments/assets/74d30de4-0fe1-46e1-9678-fa24e1621a54" />
6. it will take about a minute or so after to open up the GUI, I have had various boot timings so give it a bit before you start troubleshooting. I am using windows 11, and have not tried on W10, but I'm assuming it works on there
