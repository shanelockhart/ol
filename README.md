# Operators Logic

Single-file showcase landing page for **Operators Logic**: deterministic autonomous operator infrastructure.

Open `index.html` in any modern browser. No build step. Tailwind CSS, Three.js (r160), GSAP 3.12 + ScrollTrigger, and Lucide icons load from CDNs.

## What's inside
- **WebGL Logic Core hero:** chrome sphere in a refractive glass shell, two interlocking brushed-silver rings with GPU-animated cobalt particle streams, and an icosahedral wireframe cage. It tilts toward the cursor (lerped, max 8°), can be dragged to orbit (damped), and shrinks and recedes on scroll. The render loop pauses when the hero is off-screen or the tab is hidden, and DPR is capped at 2.
- **Fallback:** a CSS mesh-gradient core shows when WebGL is unavailable, the GPU context is lost, or `prefers-reduced-motion` is on.
- Live telemetry strip, a 4-module bento grid with live widgets, an interactive operator simulator (3 triggers, deterministic replay), a comparison matrix, and a CTA with email dispatch, plus a footer.
