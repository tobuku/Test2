# CLAUDE.md - Project Context for Claude Code

## Project Overview

**Repository**: https://github.com/tobuku/Test2
**Live Site**: https://tobuku.github.io/Test2/
**Purpose**: Testing and experimentation repo for GSAP animations and web development concepts

## Current State

The site is **VOID Studio** - a cinematic, award-winning style digital agency landing page showcasing advanced GSAP animations.

### Files

- `index.html` - Main HTML structure
- `style.css` - All styling with CSS custom properties
- `script.js` - GSAP animations, Lenis smooth scroll, interactions

### Tech Stack

- **GSAP 3.12.5** + ScrollTrigger (CDN)
- **Lenis 1.1.13** for smooth scrolling (CDN)
- **Fonts**: Syne (display), Instrument Serif (italics), Space Mono (labels)
- Vanilla HTML/CSS/JS (no build step)

### Key Features Implemented

1. **Loader**: Counting animation (0-100%) with progress bar
2. **Hero Section**:
   - Split-text reveal with staggered animations
   - Floating 3D geometric shapes with morphing borders
   - Animated gradient mesh background
   - Stats with counting animations
3. **About Section**: Pinned scroll with word-by-word text reveal
4. **Work Section**: Horizontal scroll portfolio triggered by vertical scroll
5. **Services Section**: Counter animations on scroll
6. **Marquee**: Infinite scroll with acceleration on scroll
7. **Contact**: Interactive form with tag selection
8. **Interactions**: Magnetic buttons, text scramble on hover

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
- Site is fully responsive
- This is a sandbox for experimentation - feel free to try new things!
