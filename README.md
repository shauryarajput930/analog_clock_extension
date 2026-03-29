# Analog Clock Extension

A beautiful analog clock Chrome extension that replaces your new tab page with a functional and stylish timepiece.

## Description

This Chrome extension displays an analog clock that updates in real-time, providing an elegant way to check the time whenever you open a new tab. The clock features hour, minute, and second hands that move smoothly to display the current time.

## Features

- **Real-time Updates**: Clock hands update every second to show accurate time
- **Clean Design**: Minimalist and elegant analog clock interface
- **New Tab Override**: Replaces Chrome's default new tab page
- **Responsive Layout**: Works well on different screen sizes

## Installation

1. Download or clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" and select the extension folder
5. The extension will be installed and ready to use

## Usage

Once installed, simply open a new tab in Chrome to see the analog clock. The clock will automatically display your current local time and update every second.

## Files Structure

```
Analog_Clock_Extension/
├── manifest.json      # Extension configuration
├── index.html         # Main HTML structure
├── style.css          # Styling for the clock
├── index.js           # Clock functionality
├── 2.png             # Extension icon
├── clock.png         # Clock face image
└── README.md         # This file
```

## Technical Details

- **Manifest Version**: 3
- **Type**: Chrome Extension
- **Override**: New Tab Page (`chrome_url_overrides.newtab`)
- **Technologies**: HTML, CSS, JavaScript

## Compatibility

- Google Chrome (Manifest V3 compatible)
- Other Chromium-based browsers (Edge, Brave, etc.)

## Version

- **Current Version**: 1.0

## Author

Created as a web development project for FSD (Full Stack Development) coursework.

## License

This project is open-source and available for educational purposes.
