# Pixel Pet 🐱

A virtual pet game built with React and Vite where you can take care of your own digital companion. Watch your pet's moods change as you interact with it through feeding, playing, and managing its sleep schedule.

## Features

- **Real-time Status Monitoring**: Keep track of your pet's hunger, happiness, and energy levels
- **Interactive Controls**: Feed, play, and manage your pet's sleep schedule
- **Persistent State**: Your pet's status is saved in localStorage, so it remembers its state between sessions
- **Dynamic Mood System**: Pet's expression changes based on its overall well-being
- **Responsive Design**: Works well on both desktop and mobile devices

## Getting Started

### Prerequisites

- Node.js (version 14.0.0 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/nyxsky404/Vibe-Coding.git
```

2. Navigate to the project directory:
```bash
cd pixel-pet
```

3. Install dependencies:
```bash
npm install
```

### Running the Application

To start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

To build for production:
```bash
npm run build
```

## How to Play

- **Feed**: Click the "Feed" button to increase your pet's hunger meter
- **Play**: Interact with your pet to boost its happiness (requires sufficient energy)
- **Sleep**: Toggle sleep mode to help your pet recover energy

## Technical Stack

- React 19
- Vite 6
- CSS3 for styling
- Local Storage for state persistence

## Project Structure

```plaintext
pixel-pet/
├── src/
│   ├── components/
│   │   └── PixelPet.jsx
│   ├── styles/
│   │   └── PixelPet.css
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.css
├── public/
├── index.html
└── package.json
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Built with React and Vite
- Uses emoji for pet expressions
- Inspired by classic virtual pet games
```
