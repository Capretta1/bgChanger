# Background Color Changer

A simple React application that allows users to change the background color of the page by clicking on color buttons. Built with [Vite](https://vitejs.dev/), [React](https://react.dev/), and styled using [Tailwind CSS](https://tailwindcss.com/).

## Features

- Instantly change the background color by clicking a button
- Responsive and modern UI with Tailwind CSS
- Fast development experience with Vite

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/bgchanger.git
   cd bgchanger
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the Development Server

Start the local development server:

```sh
npm run dev
# or
yarn dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

### Building for Production

To build the app for production:

```sh
npm run build
# or
yarn build
```

### Previewing the Production Build

To preview the production build locally:

```sh
npm run preview
# or
yarn preview
```

## Project Structure

```
bgchanger/
├── public/
├── src/
│   ├── [`src/App.jsx`](src/App.jsx )
│   ├── [`src/App.css`](src/App.css )
│   ├── [`src/main.jsx`](src/main.jsx )
│   ├── [`src/index.css`](src/index.css )
│   └── assets/
├── [`index.html`](index.html )
├── [`package.json`](package.json )
├── [`tailwind.config.js`](tailwind.config.js )
├── [`postcss.config.js`](postcss.config.js )
├── [`vite.config.js`](vite.config.js )
└── ...
```

## Customization

To add more colors, edit [`App.jsx`](src/App.jsx) and add more `<button>` elements with the desired color values.

## License

This project is licensed under the MIT
