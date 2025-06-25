# React Quiz

A simple interactive quiz application built with React.

## Features

- Multiple-choice questions about React
- Progress tracking and scoring
- Timer for each quiz session
- Highscore tracking
- Responsive and modern UI

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:

   ```sh
   git clone <your-repo-url>
   cd react-quiz
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:

```sh
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Running the Quiz API Server

The quiz questions are served from a local JSON server. Start it with:

```sh
npm run server
```

This will serve questions from `data/questions.json` at [http://localhost:8000/questions](http://localhost:8000/questions).

### Building for Production

To build the app for production:

```sh
npm run build
```

## Project Structure

- `src/` — React components and styles
- `data/questions.json` — Quiz questions data
- `public/` — Static assets and HTML template

## Customization

- Add or edit questions in [`data/questions.json`](data/questions.json).
- Modify styles in [`src/index.css`](src/index.css).

## License

This project is open source and available under the
