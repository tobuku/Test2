# CLAUDE.md - Project Context for Claude Code

## Project Overview

**Repository**: https://github.com/tobuku/Test2
**Live Site**: https://tobuku.github.io/Test2/
**Purpose**: Testing and experimentation repo for GSAP animations and web development concepts. This site serves as the testing ground for **ProveForMe.com**.

## Current State

The site is **VOID Studio** - a cinematic, award-winning style digital agency landing page showcasing advanced GSAP animations with 34 integrated images across 12+ animated sections.

### Files

- `index.html` - Main HTML structure
- `style.css` - All styling with CSS custom properties
- `script.js` - GSAP animations, Lenis smooth scroll, interactions
- `img/` - 34 images (1.jpg through 34.jpg)

### Tech Stack

- **GSAP 3.12.5** + ScrollTrigger (CDN)
- **Lenis 1.1.13** for smooth scrolling (CDN)
- **Fonts**: Syne (display), Instrument Serif (italics), Space Mono (labels)
- Vanilla HTML/CSS/JS (no build step)

### Image Distribution

| Images | Section | Animation Techniques |
|--------|---------|---------------------|
| 1-2 | Hero | Clip-path reveal, 3D mouse parallax, scroll parallax, glow effect |
| 3 | About | Circular mask, scroll-driven 360deg rotation, grayscale-to-color |
| 4-6 | Showcase | Asymmetric grid, directional stagger reveals, inner parallax |
| 7-11 | Work Cards | Grayscale-to-color hover, scale parallax during horizontal scroll |
| 12 | Cinematic | Pinned circle clip-path iris reveal, counter-zoom |
| 13-14 | Duo | Opposing parallax, rotation entrance, gradient divider |
| 15-20 | Image Reel | Dual-row infinite scroll, opposite directions, scroll-speed boost |
| 21-23 | Stack Cards | Pinned stacking, fly-in with rotation, fanned deck effect |
| 24-29 | Bento Grid | Asymmetric mosaic, unique clip-path reveals per item |
| 30-31 | Diagonal Split | Pinned wipe reveal from opposing sides, counter-zoom |
| 32-34 | Image Ribbon | Tilted continuous scroll, dynamic tilt on scroll |

### Page Section Order

1. Loader (counting animation 0-100%)
2. Navigation (fixed, mix-blend-mode difference)
3. Hero (images 1-2, floating shapes, gradient mesh, stats)
4. Image Reel Strip (images 15-20)
5. About (image 3, pinned word-by-word text reveal)
6. Showcase (images 4-6, staggered grid)
7. Stack Cards (images 21-23, pinned stacking)
8. Work (images 7-11, horizontal scroll portfolio)
9. Cinematic Reveal (image 12, circle iris reveal)
10. Bento Grid (images 24-29, mosaic)
11. Services (counter animations, icon grid)
12. Diagonal Split (images 30-31, wipe reveals)
13. Duo (images 13-14, opposing parallax)
14. Image Ribbon (images 32-34, tilted scroll)
15. Marquee (infinite text scroll with acceleration)
16. Contact (form with tag selection)
17. Footer

### Key Animation Techniques Used

- **ScrollTrigger pinning** with scrub for cinematic scroll-driven effects
- **Clip-path animations** (polygon, circle, inset) for image reveals
- **3D transforms** (perspective, rotateX/Y) for depth and mouse reactivity
- **Parallax** at multiple levels (container, inner image, scroll-driven)
- **Grayscale-to-color** CSS filter transitions on hover
- **Staggered reveals** with varied directions and rotations
- **Infinite CSS animations** for reels, ribbons, and marquees
- **Magnetic buttons** with elastic snap-back
- **Text scramble** effect on hover
- **Counter animations** with snap rounding

### Design System

```css
/* Colors */
--void-black: #0a0a0b
--void-purple: #8b5cf6
--void-blue: #3b82f6
--void-coral: #f97316

/* Fonts */
--font-display: 'Syne'
--font-serif: 'Instrument Serif'
--font-mono: 'Space Mono'
```

## Git Workflow

- Push directly to `main` branch
- GitHub Pages deploys automatically from `main`
- No PR required for this test repo

## Notes

- Standard arrow cursor (custom cursor was removed per user preference)
- Site is fully responsive with breakpoints at 1024px, 768px, and 480px
- This is a sandbox for experimentation - feel free to try new things!
- When adding new images, continue the naming convention (35.jpg, 36.jpg, etc.)
- All existing animations must be preserved when adding new features
