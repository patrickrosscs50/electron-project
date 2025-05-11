# Electron Project

**My personal Electron desktop application.**

This is an Electron application based on the [Quick Start Guide](https://electronjs.org/docs/latest/tutorial/quick-start) within the Electron documentation.

## Project Overview

This project serves as a foundation for building cross-platform desktop applications using web technologies:
- HTML, CSS, and JavaScript for the frontend
- Node.js for backend functionality
- Electron to package everything as a native desktop application

## Key Files

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.
- `preload.js` - A content script that runs before the renderer process loads.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/patrickrosscs50/electron-project.git
# Go into the repository
cd electron-project
# Install dependencies
npm install
# Run the app
npm start
```

## Development

This project follows the Electron architecture which separates the application into:
- **Main Process**: Controls the application lifecycle, creates native elements, etc.
- **Renderer Process**: Handles the UI and user interaction

To start developing, simply modify the files as needed:
- Edit `index.html` to change the application's UI
- Modify `main.js` to change window settings or add menu items
- Update `renderer.js` to add interactive functionality

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [Electron Fiddle](https://electronjs.org/fiddle) - Electron Fiddle, an app to test small Electron experiments

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
