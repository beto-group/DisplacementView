---
id: displacement-view-216
version.obsidian: 1.4.11
---

### Tab: Displacement View

- **Description**: An interactive WebGL visualizer applying real-time displacement mapping shaders to images and videos, with built-in recording capabilities, auto-sway animations, and a themed control panel.

- **Does**:
  - **Dynamic Displacement Shader**: Applies interactive height-displacement math to images and videos.
  - **Built-in Recording**: Captures the canvas to high-bitrate WebM or MP4 output.
  - **Themed Controls**: Natively styles the lil-gui panel using Obsidian CSS theme tokens.
  - **Full-tab Integration**: Reparents into the pane edge-to-edge via custom React portaling.

- **Can’t**:
  - **Offline without Cache**: CDN script components require network on first boot before storing locally.
