# Sun Spacetime Gravity Visualization

Interactive classroom illustration of gravitational time dilation using a connected, deformable 3D lattice. Open index.html in a browser; no installation or build step is required.

Drag the Sun to move the field, drag empty space to rotate, and scroll to zoom. X, Y and Z sliders provide precise positioning. Density, exaggeration and Sun display size are adjustable. Keys 1–4 select presentation stages.

## Scientific interpretation

Stationary-clock rates outside an ideal spherical, non-rotating Sun follow alpha(r) = sqrt(1 - 2GM/(r c²)). The chosen visual mapping is x' = s + alpha(|x-s|)^A (x-s), where s is the Sun position and A exaggerates the mapping. It is a visual metaphor, not physical spatial compression or an isometric embedding of spacetime. Moving the Sun recomputes a static field; propagation delays, gravitational waves and motion effects are not simulated. The numeric clock readout remains unexaggerated. Sources and equations are included in the application.

Live website: https://kuke2013-hub.github.io/clock-cube/

## Hosting

For GitHub Pages, publish from the main branch and the root folder. The application is self-contained HTML, CSS and JavaScript with no external runtime dependencies.
