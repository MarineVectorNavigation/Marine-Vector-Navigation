FIXED VERSION

1) Extract the ZIP.
2) In VS Code: File > Open Folder and choose the extracted folder.
3) Right-click index.html in Explorer > Open with Live Server.
4) Keep internet connected because Three.js loads from jsDelivr.

The fix adds a browser import map so OrbitControls can resolve the 'three' module correctly.
