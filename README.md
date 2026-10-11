# Classroom Spin Wheel

An animated wheel for randomly selecting students. The app is a single HTML file and needs no Python, web server, installation, or internet connection.

## Getting started

1. Download [index.html](./index.html) or open it from the project folder.
2. Double-click `index.html` to open it in Microsoft Edge, Chrome, or Firefox.
3. Create a class, add students, and select **Spin**.

## Features

- Manage multiple classes and their student lists.
- Add or remove students, or manually mark them active or inactive.
- The selected student remains highlighted on the wheel, is marked inactive in the list, and gets the selection date.
- Inactive segments remain visible until the next spin, then are removed from the wheel.
- Manually reactivating a student clears their selection date and winner highlight.
- Class lists, active states, selection dates, the current winner, theme, and sidebar preference are saved in the browser.
- Collapse the student sidebar to make more room for the wheel.
- Switch between light and dark mode.
- The wheel has an optional click sound. Near the end, it slows almost to a stop at a segment boundary and sometimes slips into the neighboring segment at the last moment.
- Export a backup as JSON or import a previously exported file.
- Press Space to spin when an input, button, or select control is not focused.

Data stays on this device in the browser used to open the file. Export a JSON backup regularly to preserve your classes or use them in another browser. The JSON file contains student names, activity states, and selection dates, so keep it private.
