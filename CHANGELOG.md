## 1.4.6 - 2026-03-24
- Cleaned up startup rendering by removing the duplicate cylinder redraw after load.
- Changed FiO₂ inputs for Ventilated, CPAP, and High Flow from decimal fractions to dropdown percentages (21% to 100%).
- Kept calculations unchanged internally by converting the selected percentage to a fraction for the formula.
- Improved small-screen cylinder card responsiveness with a more readable 2-column layout on very narrow mobile widths.
- Updated app version and service worker cache name to keep GitHub Pages/PWA refresh behaviour in sync.
## [1.4.5] - 2026-03-23

### Changed
- Reworked cylinder visual scaling to preserve clearer size differences on iPhone-sized screens
- Cylinder heights now render proportionally from relative capacity instead of fixed compressed mobile values

### Fixed
- HX, E, and CD cylinders no longer appear nearly identical to ZX on small screens

### Notes
- Visual cylinder sizes remain illustrative rather than physically exact, but relative differences are now much clearer across desktop, tablet, and mobile.
## [1.4.4] - 2026-03-23
### Added
- HX cylinder option (2,300 L)

### Changed
- Cylinder order updated to ZX, HX, E, CD
- Cylinder graphics rebalanced for desktop, tablet, and mobile layouts
- Mobile and tablet grid sizing adjusted to keep all cylinders visible without clipping

### Notes
- HX cylinder is displayed visually between ZX and E to reflect approximate relative capacity.
## [1.4.3] - 2026-03-23

### Changed
- Removed adult reference card from cylinder selector
- Tightened cylinder sizing further for small-screen layouts
- Adjusted cylinder card spacing and padding to prevent largest cylinder from clipping on mobile

### Added
- Copy Summary now includes current date and time

### Notes
- Mobile cylinder layout was simplified to focus only on selectable cylinders and reduce overflow risk.
## [1.4.2] - 2026-03-23

### Added
- Static adult size reference beside cylinder graphics

### Changed
- Narrowed cylinder cards for improved phone layout
- Reduced cylinder graphic widths and heights for smaller screens
- Improved cylinder grid fit within card padding on mobile devices

### Notes
- Mobile layout adjusted to better fit narrow screens without cylinder overflow.
## [1.4] - 2026-03-23

### Added
- Update banner for newer app versions
- Manual “Update now” action to clear cached files
- Footer authorship credit for Alin Pacurar

### Changed
- Improved version handling in the app
- Updated service worker to use better cache invalidation
- Network-first loading for HTML to reduce stale page issues

### Notes
- Users may still need one manual refresh immediately after deployment in some browsers, but future updates should be much more reliable.
