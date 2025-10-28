# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the `binaryplayground` repository - a single-page portfolio website showcasing digital ventures crafted by Jason Conroy. The site displays three web properties: Frags.au, BrinyBits, and Jetty Works.

## Project Structure

```
binaryplayground/
├── index.html          # Main HTML file with semantic HTML5 structure
├── styles.css          # CSS styling with minimalistic design
├── assets/            # Directory containing logo images
│   ├── frags-logo.png     # Frags.au logo (transparent background)
│   ├── brinybits-logo.png # BrinyBits logo (transparent background)
│   └── jettyworks-logo.png # Jetty Works logo (transparent background)
└── README.md          # Basic project documentation
```

## Design Specifications

- **Typography**: Pixelify Sans font for the "Binary Playground" title, Inter for body text
- **Color Scheme**: Warm charcoal (#525252) as accent color, minimalistic black/white/gray palette
- **Layout**: Centered content with 800px max-width container, portfolio items in 450px width
- **Style**: Professional, minimalistic design with no rounded corners
- **Responsive**: Mobile-friendly with breakpoints at 768px and 480px

## Context7

Always use context7 when I need code generation, setup or configuration steps, or library/API documentation. This means you should automatically use the Context7 MCP tools to resolve library id and get library docs without me having to explicitly ask.
