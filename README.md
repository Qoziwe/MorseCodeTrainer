# Morse Code Trainer

A lightweight, interactive, single-file web application designed to help users learn, practice, and translate Morse code directly in their browser. 

The application is built using pure HTML, CSS, and JavaScript. It is fully responsive and optimized for both desktop and mobile devices.

## Features

* **Morse Code Translator:** Instantly converts English text into Morse code and vice versa.
* **Interactive Telegraph Key:** Simulate a real telegraph key using your mouse, touch screen, or keyboard.
* **Two Practice Modes:**
  * **Practice:** Guess random letters and get real-time feedback on your accuracy.
  * **Free Input:** Tap out Morse code freely and watch it decode into text letter-by-letter with automated word spacing.
* **Audio Synthesis:** Uses the native browser Web Audio API to generate realistic 600 Hz signals on-the-fly, requiring no external audio file downloads.
* **Sliding Reference Sidebar:** Access standard Morse code characters and timing rules directly from the main panel with a smooth animation.
* **100vh Desktop Layout:** Designed to fit perfectly within the desktop screen height without body scrolling, while seamlessly transitioning to a scrollable layout on mobile devices.

## Controls

* **Mouse/Touch:** Click or tap the circular **TAP** button.
* **Keyboard:** Press and hold the **Numpad Enter** key (the rightmost Enter key on the numeric keypad) to simulate the physical key.
* **Timings:**
  * **Dot (`.`):** Press and hold for less than 200 ms.
  * **Dash (`-`):** Press and hold for 200 ms or longer.
  * **Letter Separation:** Pause for 600 ms (auto-processes the current sequence).
  * **Word Separation (Free Input):** Pause for 1.4 seconds (auto-appends a space).

## Getting Started

Since this is a client-side application contained entirely within a single HTML file, there is no build step or installation required.

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/web-morse-trainer.git
