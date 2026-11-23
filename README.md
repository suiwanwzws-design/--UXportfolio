# DREAMSCAPE — Dream Exploration Lab

A responsive React + TypeScript + Vite experience inspired by the generated high-fidelity visual concept.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Build

```bash
npm run build
npm run preview
```

## Interactions
- Select planets in the bottom carousel or use the arrow controls.
- Search planets using the search field.
- Open the world profile using “Start Exploring” or “View Details”.
- Save the current world to the collection.
- Toggle the ambient sound visual indicator.
- Move the pointer to create subtle parallax on the central planet.

## Implementation notes
- Canvas starfield uses `requestAnimationFrame` and handles device pixel ratio.
- The planet, rings, cloud bands, nebula, and breathing glow are CSS-animated.
- `prefers-reduced-motion` is respected.
- Ambient sound is represented as a UI control/visual state; no audio track is bundled.
