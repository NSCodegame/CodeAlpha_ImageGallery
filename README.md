# 🎨 Responsive Image & Video Gallery

An elegant, responsive, and dynamic media gallery built with HTML, CSS, and JavaScript. It supports both **images** and **videos**, provides category-based filtering, a lightbox viewer with navigation, and a fun **"Surprise Me!"** button to enhance user engagement.

## 🖼️ Features

- 📁 **Media Filtering**: Easily switch between *All*, *Images*, and *Videos* with a stylish filter bar.
- 🔍 **Lightbox Viewer**:
  - Navigate through selected media with **Next** and **Previous** buttons.
  - View media fullscreen with dynamic height adjustment slider.
  - Responsive controls and keyboard shortcuts (⮜ ⮞ for navigation, Esc to exit).
- 🪄 **Surprise Me Button**: Loads a random media in the lightbox.
- 🎨 **Aesthetic UI**:
  - Beautiful glassmorphism filter bar.
  - Gradient backgrounds, hover effects, and smooth transitions.
  - Fully responsive masonry-style gallery layout.

## 📁 Project Structure

image-gallery/
│
├── index.html # Main HTML file
├── style.css # Styling for layout, filter bar, gallery, and lightbox
├── script.js # JavaScript logic for interactivity
└── image/ # Folder for images and videos

---

## 🛠️ Technologies Used

- ✅ **HTML5** – structure and layout
- 🎨 **CSS3** – responsive design, gradients, animations
- ✨ **Vanilla JavaScript** – DOM manipulation, interactivity

---

## 📸 How It Works

1. All media files (images/videos) are listed in a `media` array in `script.js`.
2. Buttons are generated dynamically to filter media by category (`Image`, `Videos`, `All`).
3. Clicking an item opens it in a full-screen **lightbox**, with:
   - Navigation buttons
   - Keyboard support
   - Adjustable height via slider
4. The **"Surprise Me!"** button randomly selects any media item to display in the lightbox.

---

## 🧪 How to Run

No setup needed!

1. **Clone this repository** or [Download ZIP](https://github.com/your-username/repo-name/archive/refs/heads/main.zip).
2. Ensure the `/image` folder has the listed media files.
3. Open `index.html` in your web browser.

---

## 🧩 Customization

- 📂 Add your media files to the `image/` folder.
- 📝 Edit the `media` array in `script.js` to include your files.
- 🎨 Modify `style.css` for theme, fonts, layout.
- 🎭 Add more categories like “Nature”, “Travel” etc., by tagging media.

---

## 🌐 Preview

> A sample screenshot or GitHub Pages link can be added here.

![Preview](https://via.placeholder.com/1200x600?text=Gallery+Preview)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to fork and modify it for personal or commercial use.

---

**Made with ❤️ using HTML, CSS, and JavaScript**
