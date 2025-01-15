# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents.



## Tailwind CSS Variables

```css
@layer base {
  :root {
    --text: #0f060e;
    --background: #fbf4fb;
    --primary: #800080;
    --secondary: #662ad5;
    --accent: #5218FA;
  }
  .dark {
    --text: #f9f0f8;
    --background: #0b040b;
    --primary: #ff80ff;
    --secondary: #662ad5;
    --accent: #3d05e6;
  }
},

```

```
@layer base {
  :root {
    --text: hsl(307, 43%, 4%); /* Dark brownish purple */
    --background: hsl(300, 47%, 97%); /* Very light lavender */
    --primary: hsl(300, 100%, 25%); /* Purple */
    --secondary: hsl(261, 67%, 50%); /* Deep purple with blue undertone */
    --accent: hsl(255, 96%, 54%); /* Han Purple */
  }
  .dark {
    --text: hsl(307, 43%, 96%); /* Very light lavender (light mode text) */
    --background: hsl(300, 47%, 3%); /* Very dark purple */
    --primary: hsl(300, 100%, 75%); /* Light pinkish purple */
    --secondary: hsl(261, 67%, 50%); /* Deep purple with blue undertone */
    --accent: hsl(255, 96%, 46%); /* Bright purple with a bluish tint */
  }
}

```