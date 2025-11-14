# Bookmarklet Dev Tools
===============
## Preview
**Console:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/1.jpeg?raw=true)
**Elements:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/2.jpeg?raw=true)
**Network:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/3.jpeg?raw=true)
**Sources:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/4.jpeg?raw=true)
**Settings:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/5.jpeg?raw=true)
**Plugins:**  
![.](https://github.com/DeveloperEclipse/Bookmarklet-Dev-Tools/blob/main/assets/6.jpeg?raw=true)
===============
## Features
- **Console** – Log, warn, error, info, table, groups, and execute JavaScript with autocomplete and command history.
- **Element Selector** – Visual element selection with keyboard shortcuts (Ctrl+Shift+C), mobile friendly touch support, and delete functionality (Ctrl+Shift+D).
- **Elements** – View, and edit the DOM tree, with expandable nodes.
- **Network** – Monitor XHR, Fetch, and WebSocket requests with headers, payload, responses, and code generation (Python/JavaScript).
- **Sources** – View and download HTML, CSS, and JS files with syntax highlighting, line numbers, and Flask app export.
- **Application** – View and copy all cookies stored on the current page.
- **Settings** – 4 built in themes, adjustable panel size, position, and display options.
- **Plugins** – Load plugins from URL or run custom JavaScript code, with built in plugin management and API.
- **Panel** – Draggable floating button to reopen, resizable panel, and persistent settings.
===============
# Setup Bookmarklet Dev Tools
## I use safari for this tutorial.
1. Go to Safari and search anything.
2. Click share, add the page as a bookmark.
3. Click bookmarks then edit the bookmark URL to the code below
```js
javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/DeveloperEclipse/Bookmarklet-Dev-Tools@main/src.js';(document.head||document.documentElement).appendChild(s);})();
```
4. Finally, on any page click the bookmark.