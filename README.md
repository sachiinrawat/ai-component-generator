# AI Component Generator

> Generate modern, animated, and responsive UI components with AI in seconds.

## Overview

AI Component Generator is a web application that leverages Google Gemini AI to generate high-quality, production-ready UI components based on your description. Choose your preferred framework (HTML + CSS, Tailwind, Bootstrap, etc.), describe your component, and get instant code with live preview and download options.

## Features

- **AI-powered UI code generation** (Google Gemini API)
- **Framework selection**: HTML + CSS, Tailwind CSS, Bootstrap, and more
- **Live code editor** (Monaco Editor)
- **Instant preview** of generated components
- **Copy or download** generated code
- **Responsive, modern UI** built with React and Tailwind CSS
- **Toast notifications** for user feedback

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Google Gemini AI](https://ai.google.dev/)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- [React Select](https://react-select.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Getting Started

### 1. Clone the repository

```sh
 git clone https://github.com/sachiinrawat/ai-component-generator.git
 cd ai-component-generator
```

### 2. Install dependencies

```sh
 npm install
```

### 3. Start the development server

```sh
 npm run dev
```

The app will be available at [http://localhost:5173](http://localhost:5173) (or as shown in your terminal).

## Usage

1. Select your desired framework (HTML + CSS, Tailwind, Bootstrap, etc.).
2. Describe the UI component you want (e.g., "modern animated login form").
3. Click **Generate** to let AI create the code.
4. View, copy, or download the generated code. Use the **Preview** tab to see the component live.

## Project Structure

- `src/components/` – Reusable UI components (e.g., Navbar)
- `src/pages/` – Main pages (Home, NoPage)
- `src/App.jsx` – App routing
- `src/main.jsx` – App entry point

## Customization

- **API Key**: The Google Gemini API key is currently hardcoded in `src/pages/Home.jsx`. For production, use environment variables for security.
- **Frameworks**: Add or modify frameworks in the `options` array in `Home.jsx`.

## License

MIT
