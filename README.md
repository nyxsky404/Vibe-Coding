# Vibe-Coding

A template repository containing various vibe coding projects while exploring different AI-powered IDEs (Integrated Development Environments). This repository is designed to serve as a starting point for your projects, showcasing how AI can assist in building them.

## 📋 Repository Structure

This repository is set up as a template repository with the following structure:

```
Vibe-Coding/
└── pixel-pet/  (Git submodule)
    ├── src/
    ├── public/
    ├── package.json
    └── ...
```

### Submodules

- **Pixel-Pet**: A React-based virtual pet project built with Vite. This project showcases React patterns with a playful interface.

## 🚀 Getting Started

### Clone with Submodules

To clone this repository along with its submodules, use:

```bash
git clone --recursive https://github.com/nyxsky404/Vibe-Coding.git
```

If you've already cloned the repository without the `--recursive` flag, you can fetch the submodules with:

```bash
git submodule update --init --recursive
```

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## 💻 Working with Pixel-Pet Submodule

To work with the Pixel-Pet submodule:

```bash
cd pixel-pet
npm install
npm run dev
```

This will launch the development server for the Pixel-Pet project.

### Updating the Submodule

To update the Pixel-Pet submodule to the latest version:

```bash
git submodule update --remote pixel-pet
git add pixel-pet
git commit -m "Update Pixel-Pet submodule to latest version"
```

## 🛠️ Use as a Template

This repository is set up as a template. To use it as a starting point for your own projects:

1. Click the "Use this template" button on GitHub
2. Follow the prompts to create a new repository based on this template
3. Clone your new repository with submodules using the command above

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

