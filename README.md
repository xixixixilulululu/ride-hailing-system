# Ride-Hailing System Prototype

A browser-based front-end prototype that demonstrates a simple ride-booking journey: sign in, enter a route, calculate a simulated fare, match with a demo driver, complete the trip, and submit a rating.

This repository accompanies an academic object-oriented analysis and design project by Tianrui Liu and Zixi Wu, supervised by Dr. Hamza Dijigal.

## Demo features

- Login, sign-up, and password-reset screens
- Rider, driver, and administrator role selectors
- Pickup and drop-off entry
- Immediate or scheduled ride selection
- Randomized demo fare and arrival-time estimates
- Simulated driver match and trip confirmation
- Simulated SOS alert
- Trip completion, feedback, and star rating

## Important scope note

This code is a **client-side user-interface prototype**, not a production ride-hailing service. It does not include a server, database, persistent accounts, real authentication, GPS or map integration, driver dispatch, payment processing, push notifications, or emergency-service integration. The displayed driver, fare, and arrival time are simulated in the browser. No form data is sent to an external service.

The accompanying paper presents the broader system analysis, UML models, database design, testing strategy, and deployment plan. Those design artifacts describe the proposed full system; they should not be interpreted as features implemented by this HTML prototype.

## Run locally

No installation or build step is required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Enter any non-empty email or phone value and password, choose a role, and select **LOGIN**.

For the booking demo, enter pickup and drop-off locations and select **CONFIRM BOOKING**. The first click calculates a simulated fare; the second continues to the confirmation screen.

## Project structure

```text
.
├── index.html
├── README.md
└── docs
    ├── ride-hailing-system-paper.pdf
    └── ride-hailing-system-poster.pdf
```

## Documentation

- [Project paper](docs/ride-hailing-system-paper.pdf)
- [Project poster](docs/ride-hailing-system-poster.pdf)

The two PDF files are included without content changes and are named according to their actual contents.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript

## Suggested next steps

- Replace simulated authentication with a secure backend
- Add a persistent relational database
- Integrate a real mapping and location service
- Implement driver matching and real-time trip updates
- Connect a compliant payment provider
- Add automated tests and continuous integration
- Perform accessibility, privacy, and security reviews before real-world use

## License

No open-source license has been selected. Unless a license is added, the authors retain all rights to the source code and project materials.
