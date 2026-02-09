# CS Queue Meetings Intro

A simple web timer used to mark the start of CS Internship introductory meetings and interview sessions. It displays a large countdown toward the configured meeting time (default `18:00`) and offers a compact settings panel for a few display modes.

<img width="1919" height="906" alt="image" src="https://github.com/user-attachments/assets/1ecb9e8d-5d20-4cfc-804f-025f21e000a8" />

## Purpose

Use this page to show a clear, prominent timer at the start of weekly meetings or interviews. The interface focuses on a single large countdown and short on-screen instructions for hosts.

## Live demo

https://cs-internship.github.io/CS-Queue-Meetings-Intro/

## How it works

- The main page shows a big timer that counts down to the selected meeting time.
- If the target time is passed, the timer displays a celebration indicator.
- The page includes short instructions asking attendees to send their Telegram username privately to the program bot before the session.

## Settings (in the page)

- `Meeting Time` (time input): set the target time the countdown reaches (default `18:00`).
- `DVD Mode` (checkbox): enables a moving visual element for display screens.
- `Interview Mode` (checkbox): Simplifies on-screen text for switching between interview and introduction sessions.

To start a session, open `index.html`, set the meeting time if needed, toggle any mode, then watch the large timer on screen.

## Notes

- The app is implemented with a few lines of HTML and JavaScript in `index.html` and `script.js`.
- It is designed for in-room or streamed displays — no backend required.

## License

This project is licensed under the [MIT License](./LICENSE).

## Contact / Author Info

- **Author:** [Ali Sadeghi](https://github.com/Ali-Sdg90)
- **Developed for:** [CS Internship Program](https://github.com/cs-internship)
