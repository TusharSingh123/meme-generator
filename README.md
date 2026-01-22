# Meme Generator

A fun and interactive React application for creating memes with custom text overlays. Generate memes by selecting images from a large library and adding your own top and bottom text.

## Features

- **Random Meme Selection**: Fetch random memes from the Imgflip API
- **Custom Text**: Add custom text to the top and bottom of memes
- **Live Preview**: See your meme in real-time as you edit the text
- **Large Meme Library**: Access thousands of meme templates from Imgflip
- **Responsive Design**: Works seamlessly on different screen sizes

## Tech Stack

- **React** 19.2.0 - JavaScript library for building user interfaces
- **Vite** 7.2.4 - Next generation frontend build tool
- **ESLint** - Code quality and style checking

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone or download the project
2. Navigate to the project directory:
   ```bash
   cd meme-generator
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Project

#### Development Mode
Start the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:5173`

#### Build for Production
Create an optimized production build:
```bash
npm run build
```

#### Preview Production Build
Preview the production build locally:
```bash
npm run preview
```

#### Lint Code
Check code quality:
```bash
npm lint
```

## Project Structure

```
meme-generator/
├── public/
│   └── index.css          # Global styles
├── src/
│   ├── components/
│   │   ├── Header.jsx     # Header component
│   │   └── Main.jsx       # Main meme editor component
│   ├── images/            # Image assets
│   ├── App.jsx            # Main app component
│   ├── main.jsx           # App entry point
├── index.html             # HTML entry point
├── package.json           # Project dependencies and scripts
├── vite.config.js         # Vite configuration
└── eslint.config.js       # ESLint configuration
```

## How to Use

1. **Add Text**: Enter your custom text in the top and bottom text fields
2. **Generate Random Meme**: Click the button to randomly select a new meme template from the library
3. **Preview**: Your meme will update in real-time as you type
4. **Share**: Once you're happy with your meme, take a screenshot or save it

## API Reference

This project uses the **Imgflip Meme API** to fetch available meme templates.

- Endpoint: `https://api.imgflip.com/get_memes`
- Documentation: [Imgflip API](https://imgflip.com/api)

## Components

### Header
Displays the application title and header information.

### Main
The main component containing:
- Text input fields for top and bottom text
- Button to generate random memes
- Live meme preview with overlaid text

## Future Enhancements

- Export/download meme as image
- Save favorite memes
- Customize text styling (font, size, color)
- Drag and drop text positioning
- Share memes directly to social media

## License

This project is open source and available for personal and educational use.

## Contributing

Feel free to fork this project and submit pull requests for any improvements.
