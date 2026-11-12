WAFA FIT PWA fixes — 2026-11-12

1. Original HTML/CSS/JS retained. Additive CSS fixes for iOS bounce, fixed viewport, inner content scrolling and bottom navigation safe area.
2. Added actual 192, 512 and 180 pixel icons derived from the provided logo.png.
3. Existing manifest.webmanifest retained with an added 180px icon entry.
4. Service worker cache version updated to v3 so updated assets can be installed.
5. Upload the contents of WAFA-FIT-PWA to your GitHub Pages repository, including the icons folder. On iPhone, remove the old Home Screen shortcut and add it again to refresh the icon.

Note: iOS home-indicator system area cannot be removed by a web app; the navigation background and safe area are aligned instead.
