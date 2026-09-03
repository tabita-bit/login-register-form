# Login & Register Form

A React application featuring login and register forms built with custom, reusable input components.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Author](#author)

## Overview
This project implements a login and registration UI in React. The `App` component toggles between the `LoginForm` and `RegisterForm` components based on state, allowing the user to switch between the two views without a page reload. It was built as part of coursework to practice React fundamentals: components, props, state, and controlled forms.

## Features
- Login form and register form as separate, reusable components
- Seamless switching between login/register views via a single state toggle
- Styled input groups with focus states
- Dark-themed form UI

## Tech Stack
| Category   | Technology     |
|------------|----------------|
| Framework  | React 19       |
| Build Tool | Vite           |
| Linting    | ESLint         |
| Language   | JavaScript (JSX) |

## Project Structure
```
lab3/
├── src/
│   ├── components/
│   │   ├── LoginForm.jsx     # Login form component
│   │   └── RegisterForm.jsx  # Register form component
│   ├── App.jsx                # Root component — toggles between login/register
│   ├── App.css                # Form styling
│   ├── main.jsx                # Entry point
│   └── index.css               # Base/global styles
├── index.html
├── package.json
└── vite.config.js
```

## Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm

### Installation
```bash
git clone https://github.com/tabita-bit/Lab-3.git
cd Lab-3
npm install
```

### Run the development server
```bash
npm run dev
```
Then open the local URL shown in the terminal (usually `http://localhost:5173`).

## Available Scripts
| Command           | Description                        |
|--------------------|-------------------------------------|
| `npm run dev`      | Start the development server        |
| `npm run build`    | Build the app for production        |
| `npm run preview`  | Preview the production build        |
| `npm run lint`     | Run ESLint checks                   |

## Author
Tabita Mali — [github.com/tabita-bit](https://github.com/tabita-bit)
