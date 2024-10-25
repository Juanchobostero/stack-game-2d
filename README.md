# 🎮 Stack Game 2D

![{77439A3B-E944-4211-80A4-EF4B08876A26}](https://github.com/user-attachments/assets/4114f688-68ea-42d7-8552-c06f60939fbb)

![{C256ED68-AF60-46E3-B6A6-3A4ACD1EED43}](https://github.com/user-attachments/assets/7cfc0412-3df2-469d-8adb-f57a154e4f60)


A challenging 2D stacking game built with Astro where players test their precision by stacking blocks perfectly on top of each other. The higher you stack, the harder it gets!

![Stack Game Preview](public/preview.png)

## 🎯 Game Features

- Responsive 2D gameplay
- Progressive difficulty
- Score tracking
- High score persistence

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

## 📦 Project Structure

```
/
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── GameLayout.astro
│   ├── pages/
        └── game.astro
│   │   └── index.astro
└── public/
```

## 🧞 Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`            | Starts local dev server at `localhost:4321`      |
| `npm run build`          | Build your production site to `./dist/`          |
| `npm run preview`        | Preview your build locally, before deploying     |


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

- Midudev (https://github.com/midudev)
- Built with [Astro](https://astro.build)
