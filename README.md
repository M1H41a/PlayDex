# PlayDex
Mobile Applications app for music

PlayDex – Collect, Organize, Play

A mobile application to create and manage music playlists. The app allows users to create playlists, add songs, search/filter by artist or title, mark songs as favorites, and calculate total playlist duration.

This project will be developed in stages (UI only => Local Database => Server Integration) according to the **Assessment Lab Plan**.

---

## Features

- **Playlist Management**
  - Create, edit, and delete playlists.
  - Add a name, description, and optional cover image.

- **Song Management**
  - Add, edit, and delete songs within a playlist.
  - Attributes: Title, Artist, Album, Duration.
  - Associate songs with a playlist.

- **Advanced Features**
  - Search or filter songs by artist or title.
  - Mark songs as “favorites.”
  - Automatically calculate playlist duration (sum of all songs).

---

## Entity Structure

**Playlist**
- id (primary key)
- name (string)
- description (string)
- coverImage (string / URI)

**Song**
- id (primary key)
- title (string)
- artist (string)
- album (string)
- duration (integer, seconds or mm:ss format)
- isFavorite (boolean)
- playlistId (foreign key → Playlist)


---

## Future Improvements
- Dark mode support.
- Import/export playlists.
- Audio preview (using local files or free sample API).
- User authentication (for multi-user support).

---

<img width="365" height="769" alt="image" src="https://github.com/user-attachments/assets/9aa40452-7c32-49b6-bf29-37f627c15434" />

<img width="382" height="766" alt="image" src="https://github.com/user-attachments/assets/8a13484d-d17d-45a8-9895-ac29c7d8df42" />


