# NIGHTMARE VR — Psychological Horror Experience

## Overview

NIGHTMARE VR is an atmospheric landing site for a psychological VR experience that adapts to a player's biometric responses. The site presents the project as an immersive, experimental horror environment that evolves in real time using biofeedback-driven mechanics and carefully tuned audio-visual cues.

## Key features

- Cinematic landing page with large display typography and analog "film grain" and vignette overlays.
- Immersion-focused visuals: breathing animations, subtle glitch and distortion effects, scanlines, and ambient pulse layers.
- Sections for synopsis, system requirements, acquisition, visual documentation (gallery), subject testimonials, and a protocol/FAQ database.
- Interactive UI elements: download-initiate button (mock), FAQ toggles, ambient sound triggers that start after first interaction, mouse-trail visuals for tension.
- Clear safety warnings and a clinical, research-based aesthetic conveyed through copy and UI.

## Built with

- Tailwind CSS (via CDN) for layout and utility classes.
- Google Fonts: Cinzel, Inter, JetBrains Mono.
- Font Awesome for icons (CDN).
- Vanilla JavaScript for UI interactivity (FAQ toggles, download button behavior, ambient sounds).
- Inline CSS for special visual effects (grain, glitch layers, vignette, hover effects).

## How to preview locally

1. Open `index.html` in your browser (no build step required).
2. For the audio features to start reliably, interact with the page (click anywhere) to allow autoplay-permissioned audio playback.
3. The page uses external CDNs; ensure you have internet access when previewing.

## Content and tone notes

The site intentionally uses unsettling imagery and warnings. It frames the experience as research-grade (amygdala mapping, biofeedback), and contains explicit disclaimers about psychological risk. If this is fiction or promotional, consider clarifying “fictional / demo” in the copy if you want a broader audience or to avoid misunderstanding.

## Safety & legal

- The page contains strong warnings (subliminal audio, strobing). Keep these if you want to maintain the intended tone.
- If you plan any real-world or downloadable software, replace the mock download flow with secure hosting, a transparent EULA, and a health/consent notice. Never instruct users to disable antivirus or run untrusted executables.

## Optional next steps (I can do these for you)

- Insert this README into the repository (done).
- Add a dedicated About section to `index.html` using the medium or full text.
- Replace placeholder images and remote audio links with assets in a local `assets/` folder and update paths.
- Improve accessibility (reduced-motion toggle, aria attributes, alt text, and semantic markup).
- Extract inline styles into `index.css` and tidy CSS for maintainability.

## Contact / Attribution

This project was assembled as a concept landing page. If you'd like further edits (copy tweaks, accessibility improvements, or publishing steps), tell me which item above to work on next and I will apply the changes.
