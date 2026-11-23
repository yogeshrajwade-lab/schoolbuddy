# SchoolBuddy

SchoolBuddy is a small homework planner for students and families. It runs in a web browser and saves assignments locally without an account or server.

## Try it

Open `index.html` in a current desktop or mobile browser to try the interface. For consistent storage, use a stable URL, such as a local server or GitHub Pages. Browser support for storage on pages opened directly from disk can vary.

To run it locally with Python installed, open a terminal in this directory:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Then visit `http://localhost:8000`. Keep using the same browser profile and URL to access your saved assignments.

## What you can do

- Add, edit and delete assignments with a subject and due date.
- Mark assignments complete and reopen them.
- Filter open, overdue and completed assignments.
- See overall completion progress.

The app stores assignments in your browser's local storage. Clearing site data can remove them. There is no cross-device sync, account recovery or automatic backup. On a shared browser profile, other users of that profile may be able to see saved assignments.

## Contribute

Open a GitHub issue with the browser and steps to reproduce a bug, using fictional assignment details. Pull requests that improve accessibility, keyboard use and reliability are welcome. The app uses plain HTML, CSS and JavaScript with no build step.

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE).
