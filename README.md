# Next.js Routing and External UI Libraries

This repository demonstrates the use of **Next.js app routing** (file-based routing) along with external UI libraries like **Shadcn UI** and **Aceternity UI**. It provides a structured approach to build scalable web applications with reusable components and modern design.

## Features

- **File-Based Routing:** Utilizes Next.js app routing for intuitive and organized navigation.
- **Reusable UI Components:** Includes custom and external UI components for rapid development.
- **Integration of External Libraries:** Demonstrates the use of Shadcn UI and Aceternity UI for enhanced styling and functionality.
- **Responsive Design:** Built with Tailwind CSS for seamless responsiveness.

## Folder Structure

```
📦 nextjs-routing-and-external-ui-libraries
├─ .gitignore
├─ README.md
├─ app
│  ├─ about
│  │  ├─ carousel
│  │  │  └─ page.jsx
│  │  └─ page.jsx
│  ├─ card
│  │  └─ page.jsx
│  ├─ globals.css
│  ├─ layout.js
│  ├─ page.jsx
│  └─ table
│     └─ page.jsx
├─ components.json
├─ components
│  └─ ui
│     ├─ 3d-card.jsx
│     ├─ background-lines.jsx
│     ├─ button.jsx
│     ├─ card.jsx
│     ├─ carousel.jsx
│     ├─ menubar.jsx
│     └─ table.jsx
├─ jsconfig.json
├─ lib
│  └─ utils.js
├─ next.config.mjs
├─ package-lock.json
├─ package.json
├─ postcss.config.mjs
├─ public
│  ├─ file.svg
│  ├─ globe.svg
│  ├─ next.svg
│  ├─ vercel.svg
│  └─ window.svg
└─ tailwind.config.mjs
```

### Key Directories and Files

- **app/**
  - Contains the Next.js pages and routes, structured using file-based routing.
  - Examples: `about/page.jsx`, `card/page.jsx`, and `table/page.jsx`.

- **components/ui/**
  - Houses reusable UI components such as `button.jsx`, `carousel.jsx`, and `3d-card.jsx`.

- **lib/**
  - Includes utility functions for additional functionality (e.g., `utils.js`).

- **public/**
  - Stores static assets like SVG files.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kstubhieeee/nextjs-routing-and-external-ui-libraries.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nextjs-routing-and-external-ui-libraries
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Technologies Used

- **Next.js** for server-side rendering and routing.
- **Tailwind CSS** for styling.
- **Shadcn UI** and **Aceternity UI** for pre-built, customizable components.

## Components Overview

- **Button Component:** A customizable and reusable button for various use cases.
- **Carousel Component:** A dynamic carousel for showcasing content.
- **3D Card Component:** A visually appealing card with 3D effects.
- **Table Component:** A simple table for displaying structured data.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Author

Developed by [kstubhieeee](https://github.com/kstubhieeee).

