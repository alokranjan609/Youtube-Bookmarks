# YouTube Bookmarking Extension

## Overview

This Chrome extension allows users to bookmark specific times in YouTube videos and easily return to those moments with a single click. By leveraging DOM manipulation and an understanding of YouTube's internal classes, the extension enhances your video-watching experience, making it easier to jump back to your favorite moments.

## Features

- **Bookmark Video Times**: Save specific timestamps in any YouTube video for quick access later.
- **Return to Bookmarked Time**: Click the play button in the extension to resume playback from the exact bookmarked moment.
- **User-Friendly Interface**: Simple and intuitive design that integrates seamlessly with YouTube.

## Installation

1. **Clone or Download** the repository.
    ```bash
    git clone https://github.com/alokranjan609/Youtube-Bookmarks.git
    ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** by toggling the switch in the top-right corner.
4. Click on **Load unpacked** and select the folder where you cloned/downloaded the repository.
5. The extension will now appear in your browser's extension bar.

## Usage

1. Navigate to any YouTube video.
2. Use the extension's interface to bookmark the current timestamp.
3. To return to a bookmarked timestamp, simply click the play button in the extension.

## Development

This extension uses DOM manipulation and specific YouTube classes to interact with the video player. It's a straightforward example of how web extensions can enhance user experience by integrating directly with existing web applications.

### Folder Structure

- **manifest.json**: The extension's manifest file containing permissions and basic info.
- **popup.html**: The HTML file for the extension's popup interface.
- **popup.js**: Contains the JavaScript code that handles DOM manipulation and bookmark management.
- **background.js**:Contains the JavaScript code that  listens for updates to browser tabs and specifically looks for YouTube video pages.
- **popup.css**: Basic styling for the extension's popup.
- **contentScript.js**:Contains the JavaScript code whose primary purpose is to allow users to add, play, and delete bookmarks at specific timestamps in YouTube videos.
- **utils.js**:Contains the function getActiveTabURL which is designed to retrieve the URL of the currently active tab in the user's browser

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check out the [issues page](https://github.com/alokranjan609/Youtube-Bookmarks/issues) if you want to contribute.


