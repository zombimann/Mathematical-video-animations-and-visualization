# Chaotic Billiards & Circle Fractals

This notebook explores the intersection of geometry and chaos theory through simulations of light rays (or particles) reflecting inside a circular boundary.

## Contents

1.  **Iterative Ray Tracing**: A simulation where a ray bounces inside a circle, with a fixed 90-degree inward turn at every impact point, creating a self-similar geometric path.
2.  **3.D Projection Animation**: An animated visualization that projects the 2D path into a pseudo-3D space with dynamic rotation and perspective.
3.  **High-Density Chord Visualization**: A high-resolution renderer that generates thousands of chords based on specific turn angles (e.g., the 'golden angle'), creating intricate, fractal-like patterns.
4.  **Parameter Comparison**: A multi-plot comparison showing how slight variations in the 'turn angle' can lead to radically different emergent structures.

## How to Use

*   **Adjusting Patterns**: In the chord visualization cells, modify the `TURN_DEG` variable. Small changes (e.g., from 80.5 to 80.6) can create entirely different symmetries.
*   **Animation**: The cells use `matplotlib.animation` and `IPython.display.HTML` to render videos directly in the browser. Ensure your environment supports HTML5 video playback.
