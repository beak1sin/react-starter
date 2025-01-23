# ⚡️ React Starter Pack

A modern **React + TypeScript** starter pack with **TailwindCSS, ShadCN UI, ESLint (Airbnb), Prettier**, and **Pretendard font**, built with **Vite** for lightning-fast development.

## 🚀 Tech Stack

This project includes the following tools and technologies:

- **React** `18.3.1`
- **TypeScript** `5.5.4`
- **Vite** `6.0.5`
- **Tailwind CSS** `3.4.17`
- **ShadCN UI** (Radix UI based components)
- **ESLint (Airbnb + TypeScript)** `8.54.0`
- **Prettier** `10.0.1`
- **Pretendard Font**
- **Class Variance Authority (CVA)** `0.7.1`
- **Lucide Icons** `0.473.0`
- **React Hooks & Accessibility** (with ESLint rules)

---

## 💂️ Project Structure

```
react-starter/
├── public/                     # Static assets (favicon, images, etc.)
├── src/                         
│   ├── components/              # Reusable UI components
│   ├── layouts/                  # Layout components
│   ├── pages/                     # Page components (Home, About, etc.)
│   ├── routes/                    # Route definitions
│   ├── styles/                    # Global styles
│   ├── utils/                      # Utility functions
│   ├── main.tsx                    # Application entry point
│   └── vite-env.d.ts                # TypeScript environment
│
├── .eslintrc.json                 # ESLint configuration (Airbnb + TypeScript)
├── .prettierrc                     # Prettier formatting rules
├── index.html                      # Main HTML file
├── tailwind.config.js               # Tailwind CSS configuration
├── tsconfig.json                    # TypeScript configuration
├── vite.config.ts                    # Vite configuration
└── package.json                     # Project dependencies and scripts
```

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/react-starter.git
   cd react-starter
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Build the project for production:**
   ```bash
   npm run build
   ```

5. **Preview the production build locally:**
   ```bash
   npm run preview
   ```

---

## ✨ Features

- **Fast Development with Vite** 🏎️
- **Airbnb ESLint + Prettier Formatting** 🪑
- **Pre-configured Tailwind CSS** 💨
- **Atomic Design with ShadCN UI** 🎨
- **Pretendard Font Ready** 📝
- **Production-Ready Code Structure** 🏷️
- **Hot Module Replacement (HMR)** 🔥
- **Static Asset Handling (Public Directory)** 📂

---

## 🧩 Code Quality & Formatting

This project uses **ESLint (Airbnb)** and **Prettier** for code consistency.

### Linting

Run the following command to check code issues:

```bash
npm run lint
```

To automatically fix linting issues:

```bash
npm run lint:fix
```

---

## 🌟 Styling (TailwindCSS + Pretendard)

This project is configured with **TailwindCSS** for utility-first styling and the **Pretendard** font for better Korean typography.

### Custom Font Setup

`src/styles/global.css` includes Pretendard font import via CDN:

```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/Pretendard/dist/web/static/pretendard.css');

@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 📜 ESLint & Prettier Configuration

- **ESLint Rules:** Airbnb + TypeScript + Prettier
- **Prettier Config:** `.prettierrc`
- **Style Guide Enforced:** Consistent formatting on save

---

## 🔧 Available Scripts

| Command         | Description                           |
|-----------------|---------------------------------------|
| `npm run dev`   | Start development server              |
| `npm run build` | Build for production                  |
| `npm run preview` | Preview production build locally    |
| `npm run lint`  | Run ESLint to check code quality      |
| `npm run lint:fix` | Fix lint issues automatically      |

---

## 💁 License

This project is licensed under the MIT License. Feel free to use and modify.

---

## 📧 Contact

For any questions or feedback, feel free to reach out.

