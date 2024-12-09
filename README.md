# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents. Gradients are also included for seamless UI design.

---

## Light Theme 🎨

| Name           | HEX       | Preview                                                                                              |
| -------------- | --------- | ---------------------------------------------------------------------------------------------------- |
| **Text**       | `#0F060E` | ![#0F060E](https://via.placeholder.com/50/0F060E/FFFFFF?text=+) Raisin Black (Dark Purple-Gray)      |
| **Background** | `#FBF4FB` | ![#FBF4FB](https://via.placeholder.com/50/FBF4FB/000000?text=+) Lavender Blush (Light Pinkish White) |
| **Primary**    | `#9E009E` | ![#9E009E](https://via.placeholder.com/50/9E009E/FFFFFF?text=+) Deep Magenta (Vibrant Purple)        |
| **Secondary**  | `#5400F0` | ![#5400F0](https://via.placeholder.com/50/5400F0/FFFFFF?text=+) Electric Indigo (Bright Purple-Blue) |
| **Accent**     | `#662AD5` | ![#662AD5](https://via.placeholder.com/50/662AD5/FFFFFF?text=+) Slate Blue (Medium Purple)           |

---

## Dark Theme 🌙

| Name           | HEX       | Preview                                                                                             |
| -------------- | --------- | --------------------------------------------------------------------------------------------------- |
| **Text**       | `#F9F0F8` | ![#F9F0F8](https://via.placeholder.com/50/F9F0F8/000000?text=+) Ghost White (Soft Off-White)        |
| **Background** | `#0B040B` | ![#0B040B](https://via.placeholder.com/50/0B040B/FFFFFF?text=+) Very Dark Magenta (Blackish Purple) |
| **Primary**    | `#FF61FF` | ![#FF61FF](https://via.placeholder.com/50/FF61FF/000000?text=+) Hot Pink (Bright Magenta-Pink)      |
| **Secondary**  | `#630FFF` | ![#630FFF](https://via.placeholder.com/50/630FFF/FFFFFF?text=+) Electric Violet (Bright Purple)     |
| **Accent**     | `#662AD5` | ![#662AD5](https://via.placeholder.com/50/662AD5/FFFFFF?text=+) Slate Blue (Medium Purple)          |

---

## Gradients 🌈

### Linear Gradients

| Gradient Name            | Preview                                                                                                  |
| ------------------------ | -------------------------------------------------------------------------------------------------------- |
| **Primary to Secondary** | ![Gradient](https://via.placeholder.com/300x50/9E009E/5400F0?text=+) `linear-gradient(#9E009E, #5400F0)` |
| **Primary to Accent**    | ![Gradient](https://via.placeholder.com/300x50/9E009E/662AD5?text=+) `linear-gradient(#9E009E, #662AD5)` |
| **Secondary to Accent**  | ![Gradient](https://via.placeholder.com/300x50/5400F0/662AD5?text=+) `linear-gradient(#5400F0, #662AD5)` |

### Radial Gradients

| Gradient Name            | Preview                                                                                                  |
| ------------------------ | -------------------------------------------------------------------------------------------------------- |
| **Primary to Secondary** | ![Gradient](https://via.placeholder.com/300x50/9E009E/5400F0?text=+) `radial-gradient(#9E009E, #5400F0)` |
| **Primary to Accent**    | ![Gradient](https://via.placeholder.com/300x50/9E009E/662AD5?text=+) `radial-gradient(#9E009E, #662AD5)` |
| **Secondary to Accent**  | ![Gradient](https://via.placeholder.com/300x50/5400F0/662AD5?text=+) `radial-gradient(#5400F0, #662AD5)` |

---

## Tailwind CSS Variables

### Light Theme

```css
:root {
  --text: 307 43% 4%;
  --background: 300 47% 97%;
  --primary: 300 100% 31%;
  --secondary: 261 100% 47%;
  --accent: 261 67% 50%;
}
```
