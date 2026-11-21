# MATUDI Digital Muse

An experimental interactive 3D digital character experience.

## Current experience
- Procedural Three.js character with drag rotation and a 360-degree turn.
- Wave, look direction, and expression controls.
- Local scripted chat and optional browser speech synthesis.
- Ambient orbit lighting and a lightweight cursor-particle trail.
- Responsive layout with reduced-motion support for the ambient layer.

## Motion component research
OriginKit was reviewed as a source of motion-component ideas. The current motion layer is independently implemented for this project; it does not contain copied OriginKit source code.

OriginKit's free tier provides access to part of its component catalog with daily copy limits and no card requirement. Exact component source retrieval through its API/MCP requires an account API key. No paid OriginKit plan or paid service is used here.

## Hosting
This is a static site intended for free GitHub Pages hosting. The repository includes a GitHub Actions Pages workflow. Pages must be enabled for this repository before the public preview URL can be considered live.

## Run
Open `index.html` through a static web server. The 3D renderer loads Three.js from jsDelivr, so an internet connection is required.
