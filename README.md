# Apple MacBook Pro Landing Page (WIP)

A modern Apple-style MacBook Pro landing page built with React, Vite, GSAP animations, and interactive 3D models using React Three Fiber.

## Status

This project is currently **in progress** and not finished yet.

Implemented so far:
- Navigation bar and hero section
- Interactive product viewer with:
  - Color switching
  - 14" / 16" model switching
  - 3D model rendering with lights
- Scroll-based showcase animation section

Still in progress:
- Responsive and accessibility polish
- Content refinement and section completeness
- Final animation tuning and cleanup
- Production-level optimization

## Tech Stack

- React 19
- Vite 7
- GSAP + ScrollTrigger
- React Three Fiber + Drei + Three.js
- Zustand
- Tailwind CSS 4

## Project Structure

```txt
src/
  components/
    NavBar.jsx
    Hero.jsx
    ProductViewer.jsx
    Showcase.jsx
    three/
    models/
  store/
  constants/
```

## Getting Started

### 1) Install dependencies

```bash
npm install
```

### 2) Run development server

```bash
npm run dev
```

### 3) Build for production

```bash
npm run build
```

### 4) Preview production build

```bash
npm run preview
```

## Scripts

- `npm run dev` - start Vite dev server
- `npm run build` - create production build
- `npm run preview` - preview production build
- `npm run lint` - run ESLint

## Notes

- 3D assets are located in `public/models`
- Video assets are located in `public/videos`
- Some UI text and layout details may change during development

## License

This project is for learning and portfolio purposes.
