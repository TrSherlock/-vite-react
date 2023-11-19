```bash
npm craete vite@latest .
Last Version: Yes
Select a freamwork: React
Select a variant: Javascript
npm install

Tailwindcss
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

File: tailwind.config.js
```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
  darkMode: "class"
}
```
  
File: index.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
