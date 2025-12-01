# 😂 Da Trex – Meme Viewer Website

A fun, simple, and interactive meme-viewing website where users can browse memes, like them, upload their own memes, switch between dark/light mode, and search for memes online using a public API.

---

## 🌐 Live Features

### ✔️ Meme Navigation  
- Browse through built-in memes (`Previous` / `Next` buttons).  
- Smooth image transitions.

### ✔️ Meme Search  
Uses **Imgflip Meme API** to search memes by name.  
User types in search bar → website fetches similar memes online.

### ✔️ Dark / Light Mode  
Toggle between themes for a better viewing experience.

### ✔️ Like Counter  
Users can like memes and see a live count.

### ✔️ Meme Upload  
Upload your own image → instantly displayed as a meme.

---

## 📸 How the Website Works

### **1. User Interface (index.html)**  
- A header with title, search bar, and mode toggle  
- Main container showing:
  - Meme Image  
  - Caption  
  - Next/Previous meme buttons  
  - Like button  
  - Upload button  
- Connected to JavaScript for full interaction  
(From file: `index.html` :contentReference[oaicite:3]{index=3})

---

## 🧠 Main Logic (script.js)

### 🔍 Search Function  
Fetches online memes from Imgflip API and displays matching ones.

### 🌗 Mode Toggle  
Adds/removes `.dark` class from `<body>` to switch themes.

### 🖼 Meme Navigation  
Stores meme list in array → moves using index pointer.

### 👍 Likes  
Simple counter stored in a variable and displayed on screen.

### 📤 Upload Meme  
Converts user-uploaded file into a local URL and shows it in the image preview.

(From file: `script.js` :contentReference[oaicite:4]{index=4})

---

## 🎨 Styling (style.css)

- Google Fonts (Poppins)
- Gradient background
- Dark mode theme styling
- Hover animations
- Modern rounded UI components

(From file: `style.css` :contentReference[oaicite:5]{index=5})

---

## 🛠️ Tech Stack

| Part | Technology |
|------|------------|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | JavaScript |
| API Used | Imgflip Meme API |
| Assets | Local Images + Uploaded Images |

---



## 📁 Project Structure

/Da-Trex/
│── index.html

│── style.css

│── script.js

└── /images/

├── meme1.jpg

├── meme2.jpg

└── meme3.jpg


---

## 🚀 How to Run

### 1️⃣ Download project  
### 2️⃣ Open **index.html** in any browser  
That’s it — no installation needed!

---

## 🙌 Acknowledgement

Thanks to:  
- **Imgflip API** for meme data  
- Open-source inspiration for fun meme projects  
- Everyone who enjoys memes 😄  

---

## 📎 References

- Imgflip API: https://api.imgflip.com/get_memes  
- Files used:  
  - index.html :contentReference[oaicite:6]{index=6}  
  - script.js :contentReference[oaicite:7]{index=7}  
  - style.css :contentReference[oaicite:8]{index=8}  



