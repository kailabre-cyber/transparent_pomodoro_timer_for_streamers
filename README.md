# Transparent Pomodoro Timer for Streamers
Pomodoro Overlay for Twitch/OBS

This project is a Pomodoro-style timer overlay for OBS, built with HTML, CSS, and vanilla JavaScript.
It follows the classic Pomodoro technique: 25 minutes of focused work followed by a 5-minute break, cycling automatically between the two. Simply load the HTML file as a local browser source in OBS and start your sessions.

# How it works:

- **Large digital timer** in the center showing the session in `MM:SS` format  

- A Pomo counter at the top tracks the number of completed focus sessions.

- The session type (“FOCUS” or “BREAK”) is shown below the timer.

- An animated progress ring around the timer visually represents the time left, in red during focus sessions and green during breaks.

- When a session ends, a notification popup appears in the top-right corner to indicate whether it’s time for a break or to focus again.

- Two control buttons — Start/Pause and Reset — appear when hovering over the timer to keep the overlay clean while streaming.

# Features:

- Transparent background for seamless integration into OBS scenes.

- Fully offline — works as a local HTML file.

- Automatic session switching between focus and break.

- Tracks and displays the total Pomodoro count (Pomo X).

- Easy to customize session lengths, colors, and fonts by editing the code.

- Lightweight, using no external libraries.

# How to Use

1. Download or clone this repository

2. In OBS, add a new Browser Source. Check "Local File" and select 'pomodoro.html' from the project folder.

3. Click in "Interact with" in OBS to interact with the pomodoro timer: hover the mouse in the element to see the buttons "START", "PAUSE" and "RESET".

# Example in OBS
![pomodoro-timer-first-screen](https://github.com/kailabre-cyber/transparent_pomodoro_timer_for_streamers/blob/main/pomo0.JPG)
![when-hovering-the-mouse](https://github.com/kailabre-cyber/transparent_pomodoro_timer_for_streamers/blob/main/pomo1.png)

# Future Improvements

- Alert sounds at start/end of sessions
- Pre-made themes
- Twitch API integration

# License
This project is distributed under the MIT License — feel free to use and modify it.
