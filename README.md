# 🎁 Anniversary Gift Project

A romantic, interactive web-based gift designed to celebrate an anniversary. This project features a relationship quiz, a passcode-protected photo gallery, background music, and a final surprise video.

## ✨ Features

- **Interactive Quiz (`Quiz.html`):** A 10-question quiz about the couple's relationship. The user must pass this quiz to access the main gift.
- **Passcode Lock (`index.html`):** A beautiful lock screen requiring a 6-digit anniversary date (DDMMYY) to unlock.
- **Polaroid Memory Gallery:** A scattered polaroid photo gallery. Clicking on each photo reveals a sweet message.
- **Immersive Audio & Video:** 
  - Background music seamlessly plays from YouTube.
  - A final surprise video plays after all memories have been viewed.
- **Responsive Design:** Beautifully styled using modern CSS and Tailwind CSS, ensuring it looks great on mobile and desktop.

## 🚀 Getting Started

To run this project locally, simply open the HTML files in your web browser. No complex build tools or servers are required!

1. Clone or download the repository.
2. Open `index.html` in your preferred web browser. 
*(Note: You will be automatically redirected to `Quiz.html` if you haven't completed the quiz).*

## 🛠️ Customization Guide

You can easily customize this project for your own relationship by modifying the following files:

### `index.html` (Main Gift Page)
Open `index.html` and edit the `CONFIG` section inside the `<script>` tag:
- `correctPasscode`: Change to your 6-digit anniversary date.
- `bgMusicID`: Replace with your preferred YouTube video ID for background music.
- `surpriseVideoID`: Replace with the YouTube video ID of your surprise video.
- `messages`: Update the 10 short sweet messages.
- **Final Message:** Modify the HTML text block inside `<div id="finalMessage">`.

### `Quiz.html` (The Quiz Page)
- Update the relationship duration in the intro section (`<p class="intro-desc">`).
- Edit the `QUESTIONS` array in the `<script>` tag to add your own relationship trivia, options, and comments.

### Images (`/images`)
- Replace the files `1.jpg` to `10.jpg` in the `images` folder with your own photos.

## 💻 Tech Stack
- HTML5
- Vanilla JavaScript
- Tailwind CSS (via CDN)
- Google Fonts (Dancing Script, Kanit, Plus Jakarta Sans)
- YouTube Iframe API