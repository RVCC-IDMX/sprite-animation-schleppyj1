# Sprite Animation

This project is a starter repository for learning sprite animation and character movement in Phaser 3. It provides a foundation for creating side-scrolling games with animated characters using spritesheets.

## Project Overview

- Create animated characters using spritesheets
- Implement character movement with keyboard input
- Learn about sprite animation states (idle, walking)
- Understand basic side-scroller concepts
- Implement scene management for game states

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- NPM (v8 or higher)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone this repository
2. Navigate to the project directory
3. Install dependencies:
   ```
   npm install
   ```

### Development

1. Start the development server:
   ```
   npm run dev
   ```
2. Open your browser and go to: `http://localhost:3000`

### Building for Production

1. Create a production build:
   ```
   npm run build
   ```
2. Preview the production build:
   ```
   npm run preview
   ```

## Project Structure

```
phaser-sprites/
├── docs/                 # Documentation and assignment files
│   ├── assignment.html   # Step-by-step assignment instructions
│   ├── index.html        # Assignment overview page
│   ├── sprite-sheets.html # Information about sprite sheets
│   ├── side-scrollers.html # Information about side-scrolling games
│   └── ...               # Other documentation files
├── public/               # Static assets
│   └── assets/
│       ├── images/       # Game images and sprite sheets
│       └── sounds/       # Game audio files
├── src/                  # Source code
│   ├── main.js           # Game entry point
│   └── scenes/           # Game scenes
│       ├── TitleScene.js  # Title screen
│       ├── GameplayScene.js # Main gameplay
│       └── GameOverScene.js # Game over screen
├── index.html            # Game HTML wrapper
├── package.json          # Project dependencies
├── vite.config.mjs       # Vite configuration
└── netlify.toml          # Netlify deployment configuration
```

## Assignment Tasks

Developers will:
2. Create animations for different character states
3. Implement keyboard controls for movement
4. Add visual feedback for character actions
5. Extend the game with additional features
6. Deploy the completed game to Netlify

## Documentation

The `/docs` directory contains comprehensive documentation:

- `index.html` - Overview and introduction to the assignment
- `assignment.html` - Step-by-step instructions
- `sprite-sheets.html` - Guide to working with spritesheets
- `side-scrollers.html` - Introduction to side-scrolling games
- Other reference materials on animation concepts

## Resources

- [Phaser 3 Documentation](https://photonstorm.github.io/phaser3-docs/)
- [Phaser 3 Examples](https://phaser.io/examples)
- [Game Art 2D Free Sprites](https://www.gameart2d.com/freebies.html)
- [Vite Documentation](https://vitejs.dev/guide/)
- [Netlify Documentation](https://docs.netlify.com/)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements

- Phaser.io for the amazing game framework
- Game Art 2D for free sprite assets
