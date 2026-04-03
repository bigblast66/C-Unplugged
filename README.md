# C Unplugged

## Overview
C Unplugged is a command-line based music management system written in C. It allows users to manage songs, albums, and playlists through a structured program.

It is similar to a simplified backend of a music application like Spotify, where the focus is on handling data such as songs and playlists rather than building a user interface.

## Features
- Manage songs, albums, and playlists
- Store and organize music data using files
- Modular design using multiple C files and headers
- Command-line based interaction

## Project Structure
- `main.c` – Entry point of the program
- `songs.c / songs.h` – Handles song-related operations
- `album.c / album.h` – Manages albums
- `playlist.c / playlist.h` – Handles playlist logic
- `instructions.c / instructions.h` – User interaction and instructions
- `music.txt` – Stores song data
- `makefile` – For compiling the project

## Why I built this
I built this project to understand how data can be organized and managed in C using structures and files. It helped me learn how larger programs are split into multiple modules and how they interact.

## Limitations
- No graphical interface (CLI only)
- Limited user interaction compared to real applications
- Basic data handling

## Future Improvements
- Add a graphical interface
- Improve user interaction
- Add features like search and sorting
