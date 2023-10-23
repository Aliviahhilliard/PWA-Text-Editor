# PWA Text Editor

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Description

This is a Progressive Web Application (PWA) that allows developers to create, store, and retrieve notes or code snippets, with or without an internet connection.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client-server folder structure
WHEN I run `npm run start` from the root directory
THEN my application starts up the backend and serves the client
WHEN I run the text editor application from my terminal
THEN my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN the text editor functions in the browser without errors
WHEN I open the text editor
THEN IndexedDB immediately creates a database storage
WHEN I enter content and click off of the DOM window
THEN the content in the text editor is saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN the content has been retrieved from IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I have a registered service worker using workbox
WHEN I register a service worker
THEN my static assets are pre-cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I have proper build scripts for a webpack application
```

## Features

- Client-Server Architecture
- Webpack for JavaScript bundling
- Service Worker and Manifest for PWA
- IndexedDB for offline storage
- Deployment scripts for Heroku
- Workbox for service worker registration

## Technologies Used

- JavaScript (ES6+)
- HTML5
- CSS3
- Node.js
- Webpack
- IndexedDB
- Workbox
- Heroku

## Installation

1. Clone the repository.
2. Navigate to the root directory and run `npm install`.
3. Run `npm run start` to start the application.

## Usage

- Open the application and start creating notes or code snippets.
- Use the Install button to download the application as a PWA.

## Deployment

- Run `npm run build` to create a production-ready build.
- Deploy to Heroku using the build scripts included.

## Contributing

Please refer to the project's style and contribution guidelines for submitting patches and additions. 

## License

MIT License. See the `LICENSE` file for details.
