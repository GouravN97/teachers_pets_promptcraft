# Revenant Division Interface --- README

This project contains the interactive recruitment portal for **The
Nexus://Revenant Division**.\
The site uses animated boot-sequences, profiling phases, dossier
generation, secret inputs, and a toggleable holographic city map. All
interactions are handled entirely on the client side with HTML, CSS, and
JavaScript.


## How to run

-   **index.html**\


## Features

-   **Boot overlay** with staged activation lines\
-   **Instinct / Augment / Allegiance** profiling system\
-   **Automated role + dossier generator**\
-   **Submission uplink** to simulate packet transmission\
-   **Hidden GLITCH cipher** unlocking a secret modal\
-   **City Map viewer** (open/close panel via top-right toggle)\
-   **Ambient audio engine** (toggleable)

## Navigation

-   `index.html` --- main recruitment portal\
-   `index4.html` --- auto-loaded page after the intro video completes

## Notes

-   No backend is required; all logic runs locally in the browser.\
-   City map image must exist as `citymap.png` in the same directory.\
-   The intro video page redirects to `index4.html` only after video
    playback finishes.
