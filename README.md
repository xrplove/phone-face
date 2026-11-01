# Phone Face 🏮

A tiny, single-file web page that turns a phone screen into a friendly animated face. It blinks, glances around, and moves its mouth while it speaks short lines aloud using the browser's built-in speech voices. Made with love for the House of 589 — PISCES589HZ.

## What's inside

- `index.html` is the whole app: HTML, CSS and JavaScript in one file, with no build step and no dependencies.
  - Two eyes that blink and look around at random intervals.
  - A mouth that animates while it talks.
  - Preset buttons with a few warm, comforting lines.
  - A text box: type something and press **Speak** (or Enter) to hear it.
  - A 🎤 button that listens once (on browsers that support speech recognition) and gently repeats what it heard.
  - "Tap to wake me" goes full-screen and asks the screen to stay awake, where the browser allows it.

## How to use it

1. Open `index.html` in a modern mobile or desktop browser. You can serve it locally, or host it on GitHub Pages.
2. Tap **Tap to wake me**.
3. Tap a preset line, type your own, or use 🎤.

Speech and microphone features depend on what your browser supports. If speech synthesis isn't available, the mouth still animates and the text shows as a caption.

## License

MIT — see [LICENSE](LICENSE).
