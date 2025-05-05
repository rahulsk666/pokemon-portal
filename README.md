# Pokemon Portal

Pokemon Portal is an interactive 3D experience built using React Three Fiber (R3F) and Vite. It showcases animated 3D models of creatures in themed environments, allowing users to explore and interact with them.

## Features

- **3D Models**: Includes animated models of Fish King, Dragon, and Cactoro.
- **Interactive Camera**: Smooth camera controls to focus on specific creatures.
- **Themed Environments**: Each creature is displayed in a unique environment.
- **Hover and Click Interactions**: Hover over creatures to trigger animations and double-click to focus on them.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/pokemon-portal.git
   cd pokemon-portal
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the app in your browser at `http://localhost:3000`.

## Project Structure

```
├── public/
│   ├── fonts/
│   │   └── Caprasimo/
│   │       ├── Caprasimo-Regular.ttf
│   │       └── OFL.txt
│   ├── models/
│   │   ├── Cactoro.gltf
│   │   ├── Dragon_Evolved.gltf
│   │   └── Fish.gltf
│   ├── textures/
│   │   ├── anime_art_style_a_water_based_pokemon_like_environ.jpg
│   │   ├── anime_art_style_cactus_forest.jpg
│   │   └── anime_art_style_lava_world.jpg
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Cactoro.jsx
│   │   ├── Dragon_Evolved.jsx
│   │   ├── Experience.jsx
│   │   └── Fish.jsx
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── assets/
│       └── react.svg
├── .gitignore
├── index.html
├── LICENSE
├── package.json
├── README.md
└── vite.config.js
```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.

## Dependencies

- **React Three Fiber**: For rendering 3D scenes.
- **@react-three/drei**: Utility components for R3F.
- **Three.js**: Core 3D library.
- **Maath**: For easing and animations.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- 3D models generated using [gltfjsx](https://github.com/pmndrs/gltfjsx).
- Fonts provided under the [SIL Open Font License](public/fonts/Caprasimo/OFL.txt).
