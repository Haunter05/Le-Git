
# Le-Git 🎥✅

Le-Git (Lecture + Git) is a lightweight **desktop app** built with **Electron + SQLite** that helps you **track, organize, and manage lecture/playlists** locally — without depending on the cloud.  

Think of it as your **personal progress tracker** for YouTube playlists or any group of study videos.  

---

## ✨ Features

- 📂 **Nodes** = Playlists / Custom Groups  
  - Create nodes for playlists or your own custom groups.  
  - Track progress with simple checkboxes.  

- ⏱️ **Video Capture**  
  - Capture the currently playing video (title + timestamp).  
  - Save it automatically under a chosen node.  

- ✅ **Quick Mark Progress**  
  - Enter “mark up to video #” → All videos up to that number are auto-marked complete.  

- 📝 **Notes per Node**  
  - Add personal notes for each playlist/group.  
  - Saved locally and editable anytime.  

- 🌙 **Dark Mode**  
  - Toggle light/dark mode for comfort.  

- 🗑️ **Delete Nodes**  
  - Remove unwanted playlists/groups.  

- 💾 **Local Storage**  
  - Data is saved in `legit.db` (SQLite).  
  - 100% offline, no cloud dependency.  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Vanilla JS  
- **Backend**: Electron (Node.js + Chromium)  
- **Database**: SQLite (via `sqlite3` Node package)  

---

## 📂 Folder Structure

```

Le-Git/
│── main.js           # Electron entry point
│── package.json      # Project config & dependencies
│── preload.js        # IPC bridge between frontend & backend
│── legit.db          # Local SQLite database (auto-created)
│
├── index.html        # App UI
├── renderer.js       # Frontend logic
├── styles/
│   └── style.css     # App styling

````

---

## 🚀 Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/<your-username>/Le-Git.git
cd Le-Git
````

### 2. Install dependencies

```bash
npm install
```

### 3. Run the app

```bash
npm start
```

---

## 🔮 Future Enhancements (Optional Ideas)

* 🔍 Search within nodes
* 📊 Progress visualization with charts
* 🖱️ Drag & drop reordering of videos
* 🔔 Reminders for unfinished nodes

---

## 🤝 Contributing

1. Fork this repo
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added feature xyz"`)
4. Push branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License

MIT License © 2025
Free to use, modify, and share.

---


