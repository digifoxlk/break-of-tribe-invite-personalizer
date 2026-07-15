# Break of Tribe - Invitation Personalizer

A lightweight web tool for customizing **Break of Tribe · Path to the Roots** invitation cards for the KDU Auditorium event on **2026/08/22**. Enter a guest name, choose the Sinhala title, drag the name into place on the invitation preview, and download a personalized **PNG** or **PDF** - all in the browser with no backend.

## Features

- **Sinhala title toggle** - Choose between `ඔබතුමන්ට (Mr.)` and `ඔබතුමීයට (Mrs./Ms.)`; the inactive title is automatically crossed out on the invitation.
- **Drag-and-drop placement** - Move the guest name label anywhere on the invitation artwork using mouse or touch.
- **Live styling controls** - Change text size, view the rendered size in `px`, and pick text color instantly.
- **Export options** - Save the final invitation as a high-resolution **PNG** or **PDF**.
- **Client-side only** - No installation or server required.

## Usage

1. Open `index.html` in a modern browser.
2. Select the correct Sinhala title.
3. Type the guest's name in the input field.
4. Drag the dashed name label to the desired position on the invitation.
5. Adjust the text size and color if needed.
6. Choose `PNG` or `PDF`, then click **Download Invitation**.

## Project Structure

- `index.html` - main page and UI structure
- `assests/css/app.css` - styles and visual design
- `assests/js/app.js` - canvas rendering, drag interaction, and export logic
- `assests/js/jspdf.umd.min.js` - local jsPDF library for PDF export
- `assests/img/favicon.png` - favicon asset

## Notes

- The invitation background is rendered on a canvas using embedded image data.
- PDF export is implemented using a local `jsPDF` library.
- The app is designed for desktop and mobile browsers.

## License

This project is licensed under the Apache License 2.0. See the full license text in an `LICENSE` file if included.