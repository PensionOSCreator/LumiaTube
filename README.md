LumiaTube

A lightweight, custom video client for Windows 10 / Windows 10 Mobile that lets you browse and play online videos through a local streaming backend.

Instead of relying on built-in web playback, the app uses a PC-based server to fetch and process video content, then streams it back to the device as standard media for smooth in-app playback.

✨ Features
Video search and selection UI
Thumbnail support
In-app video playback
Custom local streaming backend
Designed for low-power / legacy devices like Windows 10 Mobile
Simple navigation with back support

🧠 How it works
The app sends a video request to a local server
The server fetches and prepares the media
The app streams the processed video directly using MediaPlayerElement

⚙️ Tech Stack
UWP (C# / XAML)
Python (Flask backend)
yt-dlp for media extraction
📌 Notes

This project is experimental and built for learning how media pipelines and custom clients can be designed on constrained platforms.

In order to run the APPX you need to do the following:

Open the Project in VS Studio Code
Go to MainPage.xaml.cs
Input your Google Cloud Console API key
Then go to PlayerPage.xaml.cs
Input your machines IP address
Then:
Go to the top bar of VS Studio Code and go Project --> Publish --> Create App Packages...
Select Sideloading
Create a new signature (Won't install on WP without one)
Select ARM only.
Press create.

After that you should be able to install the .appx on your WP.
