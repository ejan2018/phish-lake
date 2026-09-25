# Phish Lake — Phishing-Awareness Fishing Simulator 🎣🛡️

Phish Lake is an interactive, browser-based educational game that turns standard cybersecurity awareness training into a rewarding fishing arcade simulator. Players cast, hook, and reel in 30 distinct types of fish—each carrying a realistic mock email from a user's inbox. Players must analyze headers, attachments, and URLs to classify the message as legitimate or a malicious phish.

## 🚀 Live Demo
[👉 Play Phish Lake Live on GitHub Pages](https://ejan2018.github.io/phish-lake/) 

---

## 🎮 Game Flow & Mechanics

1. **Cast & Hook:** Hold the mouse/spacebar to charge and aim your bobber across the water. Strike immediately when the float dips.
2. **Reel/Slack Minigame:** Fight the fish using dynamic tension controls—**REEL** when the fish tires, and give it **SLACK** when it runs.
3. **Classify the Bait:** Open the recovered mail envelope. Closely inspect the sender address, hidden links, urgency indicators, or suspicious attachments. 
4. **Logbook & Shift Report:** Complete a 12-catch security drill shift to tally points, maintain accuracy streaks, and climb the local leaderboard.

---

## 🔥 Key Technical & Educational Features

### 🔐 1. Local-First Zero-Trust Registry
* Features an inline Angler Registry for lifetime score persistence across sessions.
* **Privacy Engine:** Passwords are completely secure, stored exclusively in browser local storage as salted, key-stretched **SHA-256 hashes**. Plaintext credentials never leave the device.

### 📖 2. Interactive Anti-Phishing Field Guide
Equipped with an integrated digital handbook training players on the six habits of elite threat analysis:
* Checking look-alike domains (e.g., `paypa1`, `micros0ft`).
* Inspecting hyperlink destination tooltips via hover masks.
* Spotting psychological urgency triggers and artificial timelines.
* Filtering unexpected `.zip` / executable email payloads.

### 🏆 3. Dynamic "Certificate Studio" Layout
At the end of a successful training shift, users can access an interactive layout workspace to generate official compliance documents:
* **HTML5 Camera/Upload Integration:** Capture an live webcam portrait or upload an avatar directly to the certificate frame.
* **Canvas Editing Tools:** Scale, zoom, crop, and filter the photo profile.
* **Sticker Placement Layer:** Click, drag, and drop official lake achievements or security seals onto the portrait workspace.
* **PNG Export:** Downloads a ready-to-print, clean certificate copy natively via browser assets.

---

## 🛠️ Tech Stack
* **HTML5 / CSS3 Grid & Flexbox** – Fluid UI panel layouts, field guide overlays, and responsive mobile-ready game frames.
* **Vanilla JavaScript (ES6+)** – Core fishing simulation math matrices, text comparison parsers, cryptographic hashing wrappers, and file stream generators.

---

## 📦 Local Installation & Run

Launch the game locally on your computer instantly without configuring heavy build pipelines:

1. **Clone the code repository:**
   ```bash
   git clone https://github.com
   ```
2. **Enter the directory:**
   ```bash
   cd phish-lake
   ```
3. **Launch the game:**
   Open the `index.html` file using any web browser to play immediately.

---

## 📄 License
Distributed under the open-source MIT License. Perfect for corporate internal security training runs, code adaptation, or educational variations.
