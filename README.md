# Student Wheel of Fortune

A simple, animated wheel for randomly selecting students in class. The app is a single HTML file that runs locally in your browser—no installation, internet connection, Python, or web server required.

## Get started

1. Open [student-wheel-of-fortune.html](./student-wheel-of-fortune.html) in Microsoft Edge, Google Chrome, or Mozilla Firefox.
2. Create a class with **＋ Class**.
3. Add students to the selected class.
4. Select **Spin** to choose a student.

## Using the app

### Classes and students

- Create and rename classes, and switch between them with the class selector.
- Add or remove students. Use the checkbox beside a student to mark them active or inactive.
- After a spin, the selected student is marked inactive, gets the selection date, and remains highlighted on the wheel until the next spin.
- Inactive wheel segments are removed when the next spin begins. Reactivating a student clears their selection date and winner highlight.
- Use **Rename** or **Delete class** below the student list to manage the selected class.

### Wheel and display

- The wheel slows down near the end and may slip into a neighboring segment for a suspenseful finish.
- Turn the optional click sound on or off in the sidebar.
- Switch between light and dark mode in the sidebar.
- Collapse the student sidebar to give the wheel more room. The selected class name remains visible while it is collapsed.
- On desktop, the app fits the window height and long student lists scroll within the sidebar. On smaller screens, the page can scroll normally.
- Press **Space** to spin when a text field, button, or selection control is not focused.

## Saving and backups

When you first open the app, choose whether to allow local saving. If you allow it, classes, student activity and selection dates, the current winner, theme, sidebar preference, and the last-export timestamp are saved in this browser on this device. The app's local-storage feature does not upload this saved data.

If you continue without saving, existing app data in this browser is deleted and new changes are kept only until you close or reload the page. The app asks again the next time you open or reload it. You can still use **Import** and **Export** to work with JSON backups. You can change the local-saving choice or turn it off and delete saved app data at any time with **Local data settings** in the sidebar.

When hosted on GitHub Pages, GitHub may process technical visit data such as IP addresses. See [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The app's local-saving choice does not control GitHub's hosting or logging.

Local browser storage is not a portable backup and may be lost if browser data is cleared. To create a backup, select **Export** in the sidebar. The downloaded JSON file includes the export date and can be loaded later with **Import**. Importing replaces the current classes and restores the timestamp recorded in the backup.

The browser cannot silently overwrite a backup file. Export a new JSON file whenever you want an up-to-date portable backup.

> Backup files contain student names and selection history. Store and share them with care.
