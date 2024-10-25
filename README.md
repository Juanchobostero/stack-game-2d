# 🎮 Stack Game 2D

A challenging 2D stacking game built with Astro where players test their precision by stacking blocks perfectly on top of each other. The higher you stack, the harder it gets!

![Stack Game Preview](public/preview.png)

## 🎯 Game Features

- Responsive 2D gameplay
- Progressive difficulty
- Score tracking
- High score persistence
- Smooth animations
- Sound effects
- Mobile-friendly controls

## 🚀 Getting Started

1. Clone this repository
2. Install dependencies:
```bash
npm install
```
3. Start the development server:
```bash
npm run dev
```
4. Open your browser and navigate to `localhost:4321`

## 🎮 How to Play

1. Click/tap to drop the moving block
2. Try to align it perfectly with the block below
3. Successfully stacked blocks earn points
4. Misaligned blocks will be cut off
5. Game ends when you miss completely

## 🛠️ Tech Stack

- [Astro](https://astro.build) - Web framework
- HTML Canvas - Game rendering
- TypeScript - Game logic
- Web Audio API - Sound effects
- Local Storage - Score persistence

## 📦 Project Structure

```
/
├── src/
│   ├── components/
│   │   ├── Game.astro
│   │   ├── ScoreBoard.astro
│   │   └── Controls.astro
│   ├── layouts/
│   │   └── GameLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── game/
│       ├── engine.ts
│       ├── block.ts
│       └── audio.ts
└── public/
    ├── sounds/
    └── images/
```

## 🧞 Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`            | Starts local dev server at `localhost:4321`      |
| `npm run build`          | Build your production site to `./dist/`          |
| `npm run preview`        | Preview your build locally, before deploying     |

## 🎨 Customization

You can customize various aspects of the game by modifying the following:

- `src/game/config.ts` - Game settings and difficulty
- `public/sounds/` - Game sound effects
- `src/styles/` - Visual styling and animations

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by classic arcade games
- Sound effects from [OpenGameArt](https://opengameart.org)
- Built with [Astro](https://astro.build)
