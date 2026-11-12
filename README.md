# The Scriptures

A quiet, browser-based KJV reading and reflection app built with HTML, CSS, and JavaScript.

## Features

- Browse and read the bundled King James Version text.
- Explore daily devotions and verse topics.
- Try a daily quiz and review reading progress.
- Save bookmarks and preferences on the current device.
- Use passage search and voice input when the browser supports speech recognition.

## Run locally

Open index.html in a modern web browser. The app has no build step or package installation.

## How data is stored

This version keeps reading progress, bookmarks, theme, and profile details in the browser's local storage on the current device. It does not include Firebase or cloud syncing, and the profile form does not create an online account.

## Project files

| File | Purpose |
| --- | --- |
| index.html | Application page structure. |
| styles.css | Layout, colors, and responsive styling. |
| app.js | Reading, devotion, quiz, search, and local progress features. |
| kjv-data.js | Bundled King James Version Bible text. |

The Bible data file identifies the KJV text as public domain. No separate license has been specified for the app code.

## Privacy

The app runs in the browser and saves its user-entered profile and reading progress locally. Do not add real user data to source files before publishing.
