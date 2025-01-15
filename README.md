# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents.



## Tailwind CSS Variables

```css
@layer base {
  :root {
    --text: #0f060e;
    --background: #fbf4fb;
    --primary: #800080;
    --accent/secondary: #5218FA;
  }
  .dark {
    --text: #f9f0f8;
    --background: #0b040b;
    --primary: #ff80ff;
    --accent/secondary: #3d05e6;
  }
},

```

```
@layer base {
  :root {
    --text: hsl(307, 43%, 4%); /* Dark brownish purple */
    --background: hsl(300, 47%, 97%); /* Very light lavender */
    --primary: hsl(300, 100%, 25%); /* Purple */
    --accent/secondary: hsl(255, 96%, 54%); /* Han Purple */
  }
  .dark {
    --text: hsl(307, 43%, 96%); /* Very light lavender (light mode text) */
    --background: hsl(300, 47%, 3%); /* Very dark purple */
    --primary: hsl(300, 100%, 75%); /* Light pinkish purple */
    --accent/secondary: hsl(255, 96%, 46%); /* Bright purple with a bluish tint */
  }
}

```