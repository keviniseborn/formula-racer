# Racing Game

A cartoonish 3D racing game built with React, TypeScript, and Three.js.

## Features

- 3D racing environment with a circular track
- Cartoonish block car with basic controls
- Keyboard-based controls (arrow keys)
- Score tracking based on distance traveled
- First-person camera that follows the car

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

1. Clone this repository

```bash
git clone <your-repository-url>
cd racing-game
```

2. Install dependencies

```bash
npm install
# or
yarn install
```

3. Start the development server

```bash
npm start
# or
yarn start
```

4. Open your browser and navigate to http://localhost:3000

## Controls

- **Up Arrow**: Accelerate
- **Down Arrow**: Brake/Reverse
- **Left Arrow**: Turn left
- **Right Arrow**: Turn right

## Project Structure

The project is organized into a modular structure to make it easy to maintain and extend:

- `components/` - React components for the game UI
- `models/` - 3D models for the car, track, etc.
- `utils/` - Utility functions for controls, game logic, etc.
- `types/` - TypeScript interfaces and types
- `styles/` - CSS styles for the game UI

## Technologies Used

- React
- TypeScript
- Three.js
- CSS3

## Development Roadmap

Planned features for future versions:

- [ ] More complex track layouts
- [ ] AI opponents
- [ ] Power-ups and speed boosts
- [ ] Collision detection and physics
- [ ] Multiple car options
- [ ] Lap timing and race positions
- [ ] Sound effects and music

## License

This project is licensed under the MIT License - see the LICENSE file for details.
