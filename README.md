# React + Vite + Tailwind

version : 1.0


### Install Tailwind with vite

```bash
  npm install -D tailwindcss postcss autoprefixer
  npx tailwindcss init -p # 테일윈드 초기 설정

```

### Configuration Tailwind setting

```javascript
// tailwind.config.js

export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

  ...
}
```