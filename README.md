# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents.

## 🎨 Color Palette

### ☀️ Light Theme

| Role       | Color                                                   | HEX Code   |
|------------|----------------------------------------------------------|------------|
| Text       | ![#110e0d](https://placehold.co/40x20/110e0d/110e0d.png) | `#110e0d`  |
| Background | ![#fcf9f8](https://placehold.co/40x20/fcf9f8/fcf9f8.png) | `#fcf9f8`  |
| Primary    | ![#090057](https://placehold.co/40x20/090057/090057.png) | `#090057`  |
| Secondary  | ![#00fff2](https://placehold.co/40x20/00fff2/00fff2.png) | `#00fff2`  |
| Accent     | ![#ff8800](https://placehold.co/40x20/ff8800/ff8800.png) | `#ff8800`  |

---

### 🌙 Dark Theme

| Role       | Color                                                   | HEX Code   |
|------------|----------------------------------------------------------|------------|
| Text       | ![#f2efee](https://placehold.co/40x20/f2efee/f2efee.png) | `#f2efee`  |
| Background | ![#070403](https://placehold.co/40x20/070403/070403.png) | `#070403`  |
| Primary    | ![#b1a8ff](https://placehold.co/40x20/b1a8ff/b1a8ff.png) | `#b1a8ff`  |
| Secondary  | ![#00fff2](https://placehold.co/40x20/00fff2/00fff2.png) | `#00fff2`  |
| Accent     | ![#E66000](https://placehold.co/40x20/E66000/E66000.png) | `#E66000`  |



## Tailwind CSS Variables

```css
@layer base {
  :root {
    --text: #110e0d;
    --background: #fcf9f8;
    --primary: #090057;
    --secondary: #00fff2;
    --accent: #E66000;
  }
  .dark {
    --text: #f2efee;
    --background: #070403;
    --primary: #b1a8ff;
    --secondary: #00fff2;
    --accent: #E66000;
  }
},

```
## hsl color

```
@layer base {
  :root {
    --text: hsl(15, 13%, 6%);
    --background: hsl(15, 40%, 98%);
    --primary: hsl(246, 100%, 17%);
    --secondary: hsl(177, 100%, 50%);
    --accent: 	hsl(25, 100%, 45%);
  }
  .dark {
    --text: hsl(15, 13%, 94%);
    --background: hsl(15, 40%, 2%);
    --primary: hsl(246, 100%, 83%);
    --secondary: hsl(177, 100%, 50%);
    --accent: 	hsl(25, 100%, 45%);
  }
}

```
## oklch color

```
@layer base {
  :root {
    --text: oklch(16.71% 0.006 39.34);
    --background: oklch(98.41% 0.003 39.48);
    --primary: oklch(21.22% 0.139 269.85);
    --secondary: oklch(90.12% 0.157 188.22);
    --accent: oklch(0.65 0.1852 45.19);
  }
  .dark {
    --text: oklch(95.42% 0.004 39.48);
    --background: oklch(11.23% 0.009 44.41);
    --primary: oklch(77.24% 0.123 287.90);
    --secondary: oklch(90.12% 0.157 188.22);
    --accent: oklch(0.65 0.1852 45.19);
  }
}

```