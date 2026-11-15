# shivani-album

Build a single-file, self-contained HTML photo album website using the photos I attach. Embed all images as base64 (resize to about 1000px wide, JPEG quality 80). Use no external libraries except Google Fonts.

STYLE
- Modern, animated, cinematic. The mood is soft, romantic and dreamy.
- Palette: deep plum background (#1b0f2e), rose (#ff7aa8), lilac (#b9a2ff), gold (#ffc46b), soft white text.
- Fonts: Fraunces (bold italic) for headings and Outfit (light) for body text.

HERO (movie-banner style, full screen)
- Photos crossfade every 5 seconds with a slow Ken Burns zoom and drift.
- Black cinema letterbox bars at the top and bottom slide away on page load.
- A huge title with my name rises letter by letter from behind a mask.
- A hand-drawn SVG underline draws itself under the title.
- Add a tagline, plus a caption, a progress line and a counter (01 / 07) at the bottom.
- Animated SVG hearts, flowers and flapping butterflies float upward over the photos with a soft glow.
- Add a scroll-down mouse cue.

FILM STRIP
- A slightly tilted section with two rows of photo thumbnails scrolling in opposite directions, infinite loop.
- Pause on hover.

ALBUM GRID
- Masonry columns with rounded photo cards.
- On hover, a card lifts and tilts slightly, the photo zooms, and a caption slides up.
- Clicking a photo opens a full-screen lightbox with prev/next buttons, keyboard arrows, Esc to close, and swipe on touch.

RESPONSIVE
- Mobile (<600px): 2 columns, smaller title, thinner letterbox bars, fewer floating particles, lightbox buttons at the bottom.
- Tablet (600–1023px): 2 columns.
- Desktop (1024px+): 3 columns, and 4 columns above 1500px.
- Phone landscape: smaller title and hidden tagline.
- Touch devices: captions always visible.
- Use safe-area insets and the viewport-fit=cover meta tag.

ACCESSIBILITY
- Respect prefers-reduced-motion.
- Visible keyboard focus.
- Alt text and aria-labels on images and buttons.

CONTENT
- Title: "[YOUR NAME]"
- Tagline: "a little album of light, laughter and pink skies"
- Write a short, sweet caption for each photo.
