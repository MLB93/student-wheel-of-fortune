# Student Wheel of Fortune

An animated wheel for randomly selecting students. The app is a single HTML file and needs no Python, web server, installation, or internet connection.

## Getting started

1. Download [student-wheel-of-fortune.html](./student-wheel-of-fortune.html) or open it from the project folder.
2. Double-click `student-wheel-of-fortune.html` to open it in Microsoft Edge, Chrome, or Firefox.
3. Create a class, add students, and select **Spin**.

## Features

- Manage multiple classes and their student lists.
- Add or remove students, or manually mark them active or inactive.
- The selected student remains highlighted on the wheel, is marked inactive in the list, and gets the selection date.
- Inactive segments remain visible until the next spin, then are removed from the wheel.
- Manually reactivating a student clears their selection date and winner highlight.
- Class lists, active states, selection dates, the current winner, theme, sidebar preference, and last-export timestamp are saved in the browser.
- Collapse the student sidebar to make more room for the wheel.
- On desktop, the app fits the window and long class lists scroll inside the sidebar.
- The selected class name stays visible above the wheel while the sidebar is collapsed.
- Find save status, import/export, theme, and sound controls in the student sidebar.
- Switch between light and dark mode.
- The wheel has an optional click sound. Near the end, it slows almost to a stop at a segment boundary and sometimes slips into the neighboring segment at the last moment.
- Export a backup as JSON or import a previously exported file. The app displays the last export date and includes that timestamp in the JSON backup.
- Press Space to spin when an input, button, or select control is not focused.

Data is automatically saved in the browser on this device. This browser-based app cannot silently overwrite a backup file; use **Export** to download a JSON backup when you want a portable copy. Its last-export date is shown in the app and travels with the JSON file. Importing a backup restores that timestamp. The JSON file contains student names, activity states, and selection dates, so keep it private.
