# MiniCountdownProject
The mini-project aims to display a countdown towards the new year, with circular  progress ring, quarter markers, synthesized sound effects, and Canvas fireworks.

A single-page, interactive New Year countdown website built using pure HTML, CSS, and Vanilla JavaScript.
It features a live countdown, circular year progress ring, quarter markers (Q1–Q4), user-gesture-compliant sound effects, and performance-optimized fireworks, all running without any external libraries or build tools.

Open the file in a browser and it just works.
Features-
-> Live New Year Countdown

Counts down to January 1, 2026 (00:00:00 local time)

Automatically rolls over to the next New Year every year

Displays:

Days
Hours
Minutes
Seconds

Updates every second with smooth visual transitions along with:
- Circular Year Progress Ring
- SVG-based circular progress ring
- Represents progress through the current year
- Uses real date math (leap-year safe)

Behavior:

0% on January 1

100% on December 31

Displays a live percentage at the center

Automatically resets when the year changes

Quarter Markers (Q1–Q4)

Visual markers placed evenly around the ring
Labels:

Q1 (Jan–Mar)
Q2 (Apr–Jun)
Q3 (Jul–Sep)
Q4 (Oct–Dec)

The Active quarter is highlighted with glow and scale animation

Subtle sound cue when entering a new quarter

Fireworks & Confetti (Performance-Optimized) as a short animation

Canvas-based particle system

Uses requestAnimationFrame

Efficient particle cleanup

Automatically stops after celebration

Triggers when countdown reaches zero

Sound Effects (Browser-Safe)

Generated using Web Audio API 

Sounds include:

Pop

Sparkle

Chime

Audio initializes only after user interaction

Click

Keypress

Sound can be toggled on/off

- UI & Design:

Bright, festive gradients

Celebration mode → calm post-celebration mode

Glowing text and cards

Responsive layout (mobile-friendly)

Respects prefers-reduced-motion accessibility setting

How It Works (High Level)

- Date Logic
- Uses JavaScript Date objects
- Handles leap years automatically
- State Machine
- Countdown mode
- Celebration mode
- Post-celebration mode

Rendering

- SVG for progress ring
- Canvas for fireworks
- DOM updates every second

Getting Started
1.Download
- Save the file as:
- index.html

2.Run

- Open directly in your browser:
  Double-click index.html


No server. No localhost. No setup.

📁 Project Structure
index.html
├─ HTML structure
-  Embedded CSS styles
-  Embedded JavaScript logic


Everything lives in a single file for simplicity and portability.

Tested On
Chrome
Edge
Firefox


Free to use, modify, and share.
No dependencies. No restrictions.
