# Underwater Effect Studio

A browser-based tool for creating photorealistic 2D snapshots of how objects and people look when viewed through a water surface — either from above or below.

Built with WebGL (no dependencies).

## Features

- **Viewer Above** — subject is underwater, seen through a refracting surface with projected caustic light patterns and specular glints
- **Viewer Below** — subject is above water, seen through Snell's window with sparkle caustics and total internal reflection at the edges

## Controls

| Control | Description |
|---|---|
| Sun direction pad | Drag to set sun azimuth |
| Sun elevation | Angle of sun above horizon |
| Sun brightness | Overall light intensity |
| Water color | Tint of the water |
| Turbidity | How murky/absorbing the water is |
| Wave scale / speed / choppiness | Surface animation |
| Caustic intensity / scale | Projected light pattern strength and size |
| Sparkle intensity | Bright focal-point flares (viewer-below mode) |
| Refraction strength | How much the surface warps the subject |
| Subject depth | Depth of subject below (or above) surface |

## Usage

Open `index.html` in any modern browser. Upload a subject image, paste one with Ctrl+V, or drag and drop onto the canvas. Adjust the controls and hit **Download Image** to save.
