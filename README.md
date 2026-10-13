# New Yashbindu — SVJ Developers

Single-page marketing website built from the *New Yashbindu* brochure.

- **Stack:** plain HTML + Tailwind CSS (CDN) + GSAP 3 / ScrollTrigger + Three.js (r128), no build step.
- **Hero:** a procedurally modelled 3D tower in Three.js with a day/night toggle, light trails and windows that light up floor by floor.
- **Sections:** About, Gallery (horizontal scroll on desktop), Specifications, Floor Plans (tabs + zoom), Cut Section (3D tilt), Connectivity (animated map), Contact (enquiry sent via WhatsApp).
- **Assets:** `assets/img/` holds images cropped from the brochure PDF.

## Run locally

Any static server works, for example:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
