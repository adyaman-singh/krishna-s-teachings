# krishna-s-teachings
An interactive 3D book experience built with React Three Fiber and Three.js, showcasing Krishna's teachings through beautiful visuals and smooth page-turning animations.


---

# 📖 3D Interactive Book - Krishna's Teachings
<img width="1456" alt="Screenshot 2025-04-04 at 5 04 26 PM" src="https://github.com/user-attachments/assets/d8be20ba-c074-4911-a88f-5c999aa0ac53" />
<img width="1463" alt="Screenshot 2025-04-04 at 5 04 49 PM" src="https://github.com/user-attachments/assets/5b73849e-79e4-4ee7-9c78-748cfdb2db10" />



An immersive 3D book experience featuring realistic page physics and smooth animations, built with React Three Fiber and Three.js.

## ✨ Features

- **Realistic Page Turning**  
  Custom bone-based animation system for natural page physics
- **Dynamic Lighting**  
  Shadow-casting directional light with ambient occlusion
- **Interactive UI**  
  Page navigation controls with audio feedback
- **Optimized Performance**  
  Skinned meshes with efficient rendering
- **Responsive Design**  
  Works on desktop and mobile devices

## 🛠 Technologies

![React Three Fiber](https://img.shields.io/badge/-React%20Three%20Fiber-000000?logo=react)
![Three.js](https://img.shields.io/badge/-Three.js-000000?logo=three.js)
![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white)
![Jotai](https://img.shields.io/badge/-Jotai-000000?logo=react)

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/adyaman-singh/krishna-s-teachings.git
   ```
2. Install dependencies:
   ```bash
   cd krishna-s-teachings && npm install (if vite is not running add it to dev dependency and try)
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## 🎮 Controls

| Action               | Command                      |
|----------------------|------------------------------|
| Turn Page Forward    | Click right page edge        |
| Turn Page Backward   | Click left page edge         |
| Jump to Page         | Use bottom navigation buttons|
| Rotate Book          | Click+drag                   |
| Zoom                 | Scroll/pinch                 |

## 📂 Project Structure

```
src/
├── assets/               # Textures and audio
├── components/
│   ├── Book/             # 3D book implementation
│   ├── UI/               # Navigation interface
│   └── Experience.jsx    # Scene setup
├── App.jsx               # Root component
└── main.jsx              # Entry point
```

## 🌈 Customization

To add your own content:

1. Replace images in `/public/textures/`
2. Update `pages` array in `UI.js`:
   ```js
   const pictures = ["your-image-1", "your-image-2"];
   ```
3. Adjust book dimensions in `Book.js`:
   ```js
   const PAGE_WIDTH = 1.28;  // Modify as needed
   ```

## 🚨 Troubleshooting

If you encounter push errors:
```bash
# For large files:
git lfs install
git lfs track "*.jpg" "*.png"
git add .gitattributes

# For connection issues:
git config --global http.postBuffer 524288000
```

## 📜 License

MIT © [Adyaman Singh]  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
