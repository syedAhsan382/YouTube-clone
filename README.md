# 📺 YouTube Clone

A fully responsive YouTube homepage clone built using **pure HTML and CSS** — no JavaScript, no frameworks. This project replicates the core look and feel of YouTube's UI, including a fixed header, collapsible-style sidebar, and a responsive video grid.

---

## 🔗 Live Preview

> Open `index.html` in your browser to view the project locally.

---

## ✨ Features

- 🔝 **Fixed Header** — Stays at the top while scrolling, includes:
  - Hamburger menu icon & YouTube logo
  - Functional-looking search bar with search & voice search buttons
  - Tooltips on hover (Create, Search, Search with voice)
  - Notification bell with unread count badge
  - Upload icon and YouTube apps icon
  - Channel profile picture
- 📌 **Fixed Sidebar** — Left-side navigation with icons and labels for:
  - Home, Explore, Subscriptions, Originals, YouTube Music, Library
- 🎬 **Video Grid** — 15 real YouTube video cards, each featuring:
  - Clickable thumbnail linking to the actual YouTube video
  - Video duration overlay on the thumbnail
  - Channel profile picture
  - Video title, channel name, views, and upload date
- 📱 **Fully Responsive Layout**:
  - 3 columns on desktop
  - 2 columns on tablets (below 999px)
  - 1 column on mobile (below 600px)

---

## 🎥 Videos Featured

| Channel | Video |
|---|---|
| Marques Brownlee | Talking Tech and AI with Google CEO Sundar Pichai |
| Markiplier | Try Not To Laugh Challenge #9 |
| Answer in Progress | I Memorized 3,141 Digits of Pi to Prove a Point |
| Veritasium | The Simplest Math Problem No One Can Solve - Collatz Conjecture |
| CS Dojo | Kadane's Algorithm to Maximum Sum Subarray Problem |
| MrBeast | Anything You Can Fit In The Circle I'll Pay For |
| RealLifeLore | Why Planes Don't Fly Over Tibet |
| Tech Vision | Inside The World's Biggest Passenger Plane |
| ThenX | The SECRET to Super Human STRENGTH |
| Business Insider | How The World's Largest Cruise Ship Makes 30,000 Meals Everyday |
| Destination Tips | Dubai's Crazy Underwear Train |
| TED-Ed | What Would Happen If You Didn't Drink Water? |
| Binging with Babish | Secret Ingredient Soup From Kung Fu Panda |
| MrWhosetheBoss | I Bought the World's Rarest Tech! |
| Ryan Trahan | I Survived On $0.01 For 30 Days |

---

## 🛠️ Built With

- **HTML5** — Semantic structure (`header`, `nav`, `main`, `section`)
- **CSS3** — Styling and layout, including:
  - CSS Grid (video grid, video info layout)
  - Flexbox (header, sidebar, search bar)
  - CSS `position: fixed` (header and sidebar)
  - CSS `position: absolute` (video duration badge, tooltips, notification count)
  - Media queries for responsiveness
  - CSS hover effects and transitions
- **Google Fonts** — Roboto font family

---

## 📁 Folder Structure

```
youtube-clone/
│
├── index.html
│
├── styles/
│   ├── general.css
│   ├── header.css
│   ├── sidebar.css
│   └── vedio.css
│
├── icons/
│   ├── hamburger-menu.svg
│   ├── youtube-logo.svg
│   ├── search icon.svg
│   ├── voice-search-icon.svg
│   ├── upload.svg
│   ├── youtube-apps.svg
│   ├── notifications.svg
│   ├── home.svg
│   ├── explore.svg
│   ├── subscriptions.svg
│   ├── originals.svg
│   ├── youtube-music.svg
│   └── library.svg
│
├── thumnails/
│   ├── thumbnail-1.webp
│   ├── thumbnail-2.webp
│   ├── thumbnail-3.webp
│   ├── ... (15 thumbnails total)
│
└── channel-pic/
    ├── channel pic.jpg
    ├── channel-1.jpeg
    ├── channel-2.jpeg
    ├── ... (15 channel pictures total)
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/syedAhsan382/youtube-clone.git
   ```

2. **Open the project**
   ```bash
   cd youtube-clone
   ```

3. **Run it** — Simply open `index.html` in any browser. No setup or installation needed!

---

## 📸 Screenshots

![YouTube Clone Screenshot](screenshots/preview.png)

---

## 🙋‍♂️ Author

**Your Name**  
[GitHub](https://github.com/syedAhsan382) • [LinkedIn](www.linkedin.com/in/syed-muhammad-ahsan-263ab8351)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

> ⚠️ *This project is made for educational purposes only. YouTube and its logo are trademarks of Google LLC.*
