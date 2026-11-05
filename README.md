# Pawsibilities Ranch Dog Rescue — Enchanted Ranch Website

Complete standalone rescue website for GitHub Pages, no subfolders.

Includes the approved circular logo (`enchanted-ranch-logo.png`), illustrated ranch homepage (`enchanted-ranch-hero.webp`), animated sequential paw trail, 19 dog profiles/photos and approved stories, mission, contact and donations.

## Publishing
Create a SEPARATE repository (e.g. `pawsibilities-ranch`) to preserve Pawtential. Extract this ZIP, upload the files (not the ZIP) to the repository root, then Settings → Pages → Deploy from branch → main → /(root).

## Editing
`dogs.json` contains the 19 dog records. Replace individual .webp photos as needed. `styles.css` contains colors, animations, layout. `script.js` contains dog profile behavior.

## Important
The hero is a single illustrated composition with visual text/navigation baked into the artwork; invisible accessible clickable link areas overlay the desktop navigation. On mobile, separate real HTML navigation is shown. The animated paw trail is a CSS overlay and uses approximate placement over the painted path. The hero art's "Events" label routes to Contact because there is not yet an events page; update when you add one. Animations respect reduced-motion settings. Donations use third-party provider links; there is no onsite payment collection.


## Latest design corrections
- Removed animated paw overlays, butterflies, and barn shimmer.
- The homepage illustration uses its original aspect ratio at all screen sizes, never cropped.
- The wooden navigation text in the artwork is linked by transparent clickable areas on desktop and mobile; no duplicate buttons.
- Interior pages use sunset/lavender gradients, ornate accents and warm decorative cards to match the enchanted homepage.
- On narrow phones, the image and embedded navigation shrink together. Visitors may need to zoom for small menu text.
