# Pixel Drift

An interactive generative pixel background with gentle motion, recognizable prompt scenes, color palettes, a clock, a focus timer and ambient audio.

## Run

No build or dependencies are required. Open `index.html`, or serve this folder with:

```sh
python3 -m http.server 8080
```

Visit http://localhost:8080.

## Controls

- Move, click or drag on the background to interact with the particles.
- Press **F** to enter fullscreen. Settings disappear until you exit with **F** or **Esc**.
- **R** randomizes, **H** hides controls and **Space** pauses animation outside fullscreen.
- Choose from 12 palettes and customize the background color independently.
- Use **Abstraction** to adjust distortion and fragmentation.
- Export the current frame as PNG.

## Prompt scenes

English and Vietnamese keyword prompts select procedural scenes. Supported subjects include koi, flowers, mountains, forests, oceans, cats, monkey onsen, durian, apple, orange, hearts, clouds and planets. Certain weather, moon, night and color keywords can modify a scene.

This is a browser-local procedural renderer, not an AI image-generation service. Unknown subjects are reported without replacing the current scene.

## Audio and timer

Ambient instrumental audio is synthesized with the Web Audio API and starts only after a user gesture. Keep the page open for the timer and chime; browsers may delay updates while a device sleeps.

## Hosting

Upload these files to any static host. No API keys, backend, account or build step is required. Fullscreen availability depends on browser and embedding permissions.
