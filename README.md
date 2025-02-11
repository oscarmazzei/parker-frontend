# React + TypeScript + Vite

A modern **React** setup using **TypeScript** and **Vite** for fast, optimized development. Includes **ESLint**, **SCSS**, **styled-components**, **Zustand**, **React Router**, **Vitest**, and **Storybook**.

## 🚀 Features

- ⚡ **Vite** – Fast build and hot module replacement.
- 🛠 **TypeScript** – Type safety and maintainability.
- 🎨 **Styled-components & SCSS** – Flexible styling.
- 🖀 **React Router** – Seamless client-side navigation.
- 📆 **Zustand** – Lightweight global state management.
- ✅ **Vitest** – Fast and efficient testing.
- 📚 **Storybook** – UI development and documentation.

---

## 🛠 Installation & Setup

Ensure **Node.js (v16+)** is installed. Then, clone and install dependencies:

```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
npm install
```

### 🔥 Start Development Server
```sh
npm run dev
```
Runs at [http://localhost:5173](http://localhost:5173).

### 📦 Build for Production
```sh
npm run build
```
Creates an optimized build.

### ✅ Run Tests (Vitest)
```sh
npm run test
```

### 📚 Run Storybook
```sh
npm run storybook
```

---

## 📂 Project Structure

```
my-app/
│── src/
│   ├── components/    # Reusable UI components
│   ├── hooks/         # Custom React hooks
│   ├── pages/         # Page components
│   ├── store/         # Zustand stores
│   ├── styles/        # Global styles (SCSS, styled-components)
│   ├── App.tsx        # Main app component
│   ├── main.tsx       # React entry point
│─ .storybook/        # Storybook config
│─ .gitignore         # Git ignore rules
│─ package.json       # Project dependencies
│─ vite.config.ts     # Vite config
│─ tsconfig.json      # TypeScript config
│─ README.md          # Project docs
```

---

## 🔍 ESLint Configuration

Enable **type-aware linting** for production apps:

```sh
npm install eslint-plugin-react --save-dev
```

Modify **eslint.config.js**:

```js
import react from 'eslint-plugin-react';

export default tseslint.config({
  settings: { react: { version: '18.3' } },
  plugins: { react },
  rules: { ...react.configs.recommended.rules, ...react.configs['jsx-runtime'].rules },
});
```

---

## 🐝 License

Licensed under the **MIT License**.

---

## ✨ Contributing

1. Fork the repo.
2. Create a branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m "Add new feature"`.
4. Push: `git push origin feature-name`.
5. Open a **Pull Request**.

Happy coding! 🚀