# Theme Colors

This project defines **light** and **dark** themes with a visually appealing color palette. Each theme includes colors for text, background, primary actions, secondary actions, and accents.

☀️ Light Theme
<table> <tr> <th>Role</th> <th>Color</th> <th>HEX Code</th> </tr> <tr> <td>Text</td> <td><div style="width: 40px; height: 20px; background-color: #110e0d;"></div></td> <td>#110e0d</td> </tr> <tr> <td>Background</td> <td><div style="width: 40px; height: 20px; background-color: #fcf9f8;"></div></td> <td>#fcf9f8</td> </tr> <tr> <td>Primary</td> <td><div style="width: 40px; height: 20px; background-color: #090057;"></div></td> <td>#090057</td> </tr> <tr> <td>Secondary</td> <td><div style="width: 40px; height: 20px; background-color: #00fff2;"></div></td> <td>#00fff2</td> </tr> <tr> <td>Accent</td> <td><div style="width: 40px; height: 20px; background-color: #ff8800;"></div></td> <td>#ff8800</td> </tr> </table>

<hr/>

🌙 Dark Theme
<table> <tr> <th>Role</th> <th>Color</th> <th>HEX Code</th> </tr> <tr> <td>Text</td> <td><div style="width: 40px; height: 20px; background-color: #f2efee;"></div></td> <td>#f2efee</td> </tr> <tr> <td>Background</td> <td><div style="width: 40px; height: 20px; background-color: #070403;"></div></td> <td>#070403</td> </tr> <tr> <td>Primary</td> <td><div style="width: 40px; height: 20px; background-color: #b1a8ff;"></div></td> <td>#b1a8ff</td> </tr> <tr> <td>Secondary</td> <td><div style="width: 40px; height: 20px; background-color: #00fff2;"></div></td> <td>#00fff2</td> </tr> <tr> <td>Accent</td> <td><div style="width: 40px; height: 20px; background-color: #ff8800;"></div></td> <td>#ff8800</td> </tr> </table>



## Tailwind CSS Variables

```css
@layer base {
  :root {
    --text: #110e0d;
    --background: #fcf9f8;
    --primary: #090057;
    --secondary: #00fff2;
    --accent: #ff8800;
  }
  .dark {
    --text: #f2efee;
    --background: #070403;
    --primary: #b1a8ff;
    --secondary: #00fff2;
    --accent: #ff8800;
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
    --accent: hsl(32, 100%, 50%);
  }
  .dark {
    --text: hsl(15, 13%, 94%);
    --background: hsl(15, 40%, 2%);
    --primary: hsl(246, 100%, 83%);
    --secondary: hsl(177, 100%, 50%);
    --accent: hsl(32, 100%, 50%);
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
    --accent: oklch(74.42% 0.181 56.46);
  }
  .dark {
    --text: oklch(95.42% 0.004 39.48);
    --background: oklch(11.23% 0.009 44.41);
    --primary: oklch(77.24% 0.123 287.90);
    --secondary: oklch(90.12% 0.157 188.22);
    --accent: oklch(74.42% 0.181 56.46);
  }
}

```