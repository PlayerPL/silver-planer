# Silver Planner

Silver Planner is a lightweight, single-file web app for planning event layouts on a scalable 2D canvas.
It helps you place and manage zones (rectangles and ellipses), adjust dimensions in meters, and export the final plan as SVG.

## What It Does

- Defines a planning area (width, height, name)
- Adds elements using shapes and presets
- Moves and edits elements with mouse + property panel
- Supports pan, zoom, fit-to-view, and grid/labels toggles
- Duplicates and deletes selected elements
- Saves and loads projects in browser `localStorage`
- Auto-saves work and restores autosave on startup
- Exports plans to SVG for sharing and printing

## Tech Stack

- Plain HTML
- CSS
- Vanilla JavaScript
- SVG rendering
- Browser `localStorage`

## Getting Started

1. Clone the repository.
2. Open `index.html` in a modern browser.
3. Start adding and arranging elements.

No build step or dependencies are required.

## Usage Notes

- Coordinates and dimensions are in meters.
- Grid step can be changed in the **Obszar** tab.
- Use mouse wheel (or touch pinch) for zoom.
- Use arrow keys to nudge the selected element (`Shift` for bigger steps).

## Repository Structure

- `index.html` - complete application (UI, styles, logic)
- `read.me` - project description for GitHub

## Roadmap Ideas

- Undo/redo history
- Element rotation
- Layer ordering and locking
- Import/export JSON project files
- Snapping improvements

## Contributing

1. Fork the repo.
2. Create a feature branch.
3. Commit focused changes with clear messages.
4. Open a pull request.

## License

Choose a license before publishing (for example MIT).
