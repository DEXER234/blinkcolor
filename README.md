# Color Palette Web App

## Overview

This web app allows users to extract beautiful color palettes from images, preview gradients, and export palettes in multiple formats. Designed with a modern, cohesive UI, it leverages Lucide Icons, Google Fonts, and Color Thief for a seamless and visually appealing experience.

---

## Features

- **Image Upload & Color Extraction:**
  - Upload any image to extract up to 8 prominent colors using [Color Thief](https://lokeshdhakar.com/projects/color-thief/).
- **Palette Paging:**
  - View palettes 3 colors at a time with Next/Previous navigation.
- **Live Gradient Preview:**
  - Instantly preview gradients and solid color combinations with a dramatic 3D effect.
- **Copy Code Instantly:**
  - Copy CSS or Tailwind code for your gradients with a single click, with visible code blocks and toast notifications.
- **Export Options:**
  - Download your palette as JSON, SVG, PNG, CSS variables, SCSS, Tailwind config, or a shareable image card via a modal popup.
- **Modern UI/UX:**
  - Animated multicolor gradient heading, consistent gray backgrounds, dark borders, and a clean, responsive layout.
- **Lucide Icons:**
  - All icons are from [Lucide](https://lucide.dev/), ensuring a modern and unified look.
- **Google Fonts:**
  - Uses Google Fonts for a professional, readable appearance.
- **Feature Cards:**
  - Features are presented in visually consistent cards with icons and descriptions.
- **Image Preview:**
  - Uploaded images are shown in full (object-contain) for accurate palette extraction.

---

## Technologies Used

- **HTML5, CSS3, JavaScript (Vanilla)**
- **[Tailwind CSS](https://tailwindcss.com/)** for utility-first styling
- **[Lucide Icons](https://lucide.dev/)** for all iconography
- **[Google Fonts](https://fonts.google.com/)** for typography
- **[Color Thief](https://lokeshdhakar.com/projects/color-thief/)** for color extraction

---

## Getting Started

1. **Clone or Download the Repository**
   ```bash
   git clone <repo-url>
   # or download and unzip the folder
   ```
2. **Open `index.html` in your browser**
   - No build step required; everything runs client-side.

---

## Usage

1. **Upload an Image:**
   - Click the upload area and select an image file.
2. **View Extracted Palette:**
   - The app displays up to 8 extracted colors, 3 at a time, with navigation.
3. **Preview Gradients:**
   - See a live preview of gradients and solid color combinations.
4. **Copy or Export:**
   - Use the Copy CSS/Tailwind buttons or open the Export modal to download your palette in various formats.

---

## Customization

- **Icons:**
  - All icons use Lucide; you can swap icons by changing the `data-lucide` attribute.
- **Fonts:**
  - Google Fonts are loaded in the HTML `<head>`; change as desired.
- **Colors & Styles:**
  - Tailwind classes control all styling for easy customization.

---

## Credits

- **Logo:** [icons8-drop-100.png](https://icons8.com/icons/set/drop)
- **Icons:** [Lucide Icons](https://lucide.dev/)
- **Color Extraction:** [Color Thief](https://lokeshdhakar.com/projects/color-thief/)
- **Fonts:** [Google Fonts](https://fonts.google.com/)

---

## License

This project is for personal and educational use. Please credit the original authors of any third-party assets used. 