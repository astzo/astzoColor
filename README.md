# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents.

## 🎨 Color Palette

### ☀️ Light Theme

| Role       | Color                                                    | HEX Code   | Name 
|------------|----------------------------------------------------------|------------|------
| Text       | ![#110e0d](https://placehold.co/40x20/110e0d/110e0d.png) | `#110e0d`  | 
| Background | ![#fcf9f8](https://placehold.co/40x20/fcf9f8/fcf9f8.png) | `#fcf9f8`  |
| Primary    | ![#0B0B45](https://placehold.co/40x20/0B0B45/0B0B45.png) | `#0B0B45`  | Dark Navy Blue
| Secondary  | ![#00ffff](https://placehold.co/40x20/00ffff/00ffff.png) | `#00ffff`  | Cyan
| Accent     | ![#FF5C00](https://placehold.co/40x20/FF5C00/FF5C00.png) | `#FF5C00`  | Neon Orange

---

### 🌙 Dark Theme

| Role       | Color                                                   | HEX Code   |
|------------|----------------------------------------------------------|------------|
| Text       | ![#f2efee](https://placehold.co/40x20/f2efee/f2efee.png) | `#f2efee`  |
| Background | ![#070403](https://placehold.co/40x20/070403/070403.png) | `#070403`  |
| Primary    | ![#b1a8ff](https://placehold.co/40x20/b1a8ff/b1a8ff.png) | `#b1a8ff`  |
| Secondary  | ![#00ffff](https://placehold.co/40x20/00ffff/00ffff.png) | `#00ffff`  |
| Accent     | ![#FF5C00](https://placehold.co/40x20/FF5C00/FF5C00.png) | `#FF5C00`  |



## Tailwind CSS Variables

```css
@layer base {
  :root {
    --text: #110e0d;
    --background: #fcf9f8;
    --primary: #0B0B45;
    --secondary: #00ffff;
    --accent: #FF5C00;
  }
  .dark {
    --text: #f2efee;
    --background: #070403;
    --primary: #b1a8ff;
    --secondary: #00ffff;
    --accent: #FF5C00;
  }
},

```
