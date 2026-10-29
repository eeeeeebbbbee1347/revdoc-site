# RevDoc Prototype

RevDoc is an installable, mobile-friendly web app prototype for exploring and sharing patient experience feedback. The two profiles at the top are hypothetical examples provided for this prototype. Their submitted review text is shown in Bangla. The remaining profiles are fictional examples.

## Preview

Open index.html in a browser. For installation and offline caching, serve this folder over localhost or HTTPS; service workers do not run from a file URL.

## Features

- Search and filter eight profiles by name, specialty, and location.
- The two hypothetical profiles appear first with the supplied 4.3 and 4.9 ratings and qualifications.
- Submit 1–5 star ratings and category ratings for communication, respect, and helpfulness.
- Submitted reviews are stored in this browser's local storage. No patient name is requested or displayed.
- Basic pattern checks can flag a review for human attention. This is not an AI model and cannot establish whether a review is true.
- The report control is a prototype placeholder.
- The web app manifest and service worker support installation as a PWA when hosted over localhost or HTTPS.

## Prototype limitations

This is a front-end prototype, not a live service. It has no server, visit verification, secure admin accounts, or real doctor directory. Do not submit real patient information. Before public launch, replace fictional data with verified listings, design a privacy-preserving backend and moderation workflow, and get Bangladesh-specific legal review.

