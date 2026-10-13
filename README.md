# Fancy 🎨

**Fancy** is a lightweight, macOS-inspired web tool designed to transform and beautify your post screenshots, UI mockups, and images by placing them onto stunning backgrounds with customizable corner radii, precise positioning, scaling, and professional strokes.

---

## ✨ Features

- **3x3 Background Theme Selector:** Instantly switch between stunning background themes (like local high-resolution landscapes and wallpapers).
- **Custom Image Upload:** Upload any image or screenshot to frame and style.
- **Precision Controls:**
  - **Position (X & Y):** Fine-tune placement.
  - **Image Scale (X & Y):** Resize your asset seamlessly.
  - **Corner Radius:** Apply smooth, modern rounded corners (defaults to 50px).
  - **Stroke & Weight:** Add customizable colored borders/strokes.
- **Smooth Scrubbing UI:** Click and drag left/right on any numeric field to quickly adjust values.
- **High-Resolution PNG Export:** Export your final composite artwork instantly with a single click.
- **Zero Dependencies:** Pure HTML5, CSS3, and Vanilla JavaScript—no complex build steps required.

---

## 🚀 Getting Started

Because modern web browsers enforce strict security policies (CORS) regarding local file access, running this app requires a local development server so that local background images load correctly.

### Running Locally

1. Clone or download this repository into a local folder along with your background images (`1.jpg` through `9.jpg`).
2. Run a local web server using one of the following methods:

   * **Using Python (Recommended):**
     Open your terminal or command prompt inside the project directory and run:
     ```bash
     python3 -m http.server
     ```
     Then open your browser and navigate to `http://localhost:8000`.

   * **Using VS Code:**
     Install the **Live Server** extension, right-click `index.html`, and select **"Open with Live Server"**.

---

## 🛠️ Project Structure

```text
📁 fancy/
├── index.html        # Main application file (HTML, CSS, and JS)
├── 1.jpg             # Background theme 1 (Default)
├── 2.jpg             # Background theme 2
├── 3.jpg             # Background theme 3
├── 4.jpg             # Background theme 4
├── 5.jpg             # Background theme 5
├── 6.jpg             # Background theme 6
├── 7.jpg             # Background theme 7
├── 8.jpg             # Background theme 8
└── 9.jpg             # Background theme 9
