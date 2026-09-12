<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

# Slap-Charger 🎯

## Basic Details

### Team Name: Zero&one

### Team Members

- Team Lead: Fidha Fathima - College of Engineering Trivandrum
- Member 2: Adhithyan K S - College of Engineering Trivandrum

### Project Description

Slap-Charger is an interactive, motion-triggered web application that turns phone shaking and slap gestures into a dynamic, gamified battery charging experience. Built with physical motion tracking and dynamic visual feedback, it simulates transferring kinetic energy directly into virtual mass power.

### The Problem (that doesn't exist)

In a world where phone batteries drain while sitting idle, people lack a high-energy, physical outlet to violently slap and shake their phones to pump kinetic energy back into their devices manually.

### The Solution (that nobody asked for)

A responsive Web App that captures 3D accelerometer data to track real-time shaking. Slapping your phone 6 times continuously charges your battery by 1% while unleashing high-energy character transformations and reactive continuous sound loops!

## Technical Details

### Technologies/Components Used

For Software:

- Languages used: HTML5, CSS3, JavaScript (ES6+)
- APIs used: Web Motion API (`DeviceMotionEvent`), HTML5 Media API (`Audio`)
- Tools used: VS Code, Netlify, Git, GitHub

For Hardware:

- Smartphone with motion sensors

### Implementation

For Software:

# Installation

```bash
# Clone the repository
git clone https://github.com/your-username/slap-charger.git

# Navigate to project folder
cd slap-charger
```

# Run

```bash
# Open index.html directly in a mobile browser or run via local web server (e.g. Live Server in VS Code)
npx serve .
```

### Project Documentation

For Software:

# Screenshots

![Screenshot1](Add screenshot 1 here with proper name)
_Displays the depleted hero state (`hero_weak.png`) and low-frequency idle audio mode when no phone motion is detected._

![Screenshot2](Add screenshot 2 here with proper name)
_Displays the powered-up hero state (`hero_max.png`), gold background flashes, and high-energy audio loop during active continuous shaking._

![Screenshot3](Add screenshot 3 here with proper name)
_Top-positioned dynamic battery bar showing progress from 0% to 100% based on continuous shake cycles._

# Diagrams

![Workflow](Add your workflow/architecture diagram here)
_Workflow showing device accelerometer motion detection (`√(x²+y²+z²) > 22`) triggering slap counters, dual audio toggles, and state decay timers._

### Project Demo

# Video

[Add your demo video link here]
_Demonstrates live phone motion tracking on a mobile browser, dynamic battery charging, state transitions, and automatic idle energy discharge._

# Additional Demos

[Add any extra demo materials/links]

## Team Contributions

- Fidha Fathima: Developed motion sensor detection logic (`DeviceMotionEvent`), battery charging/discharge algorithms, continuous audio loop switching, and UI layout structure.
- Adhithyan K S: Designed visual assets (`hero_weak.png`, `hero_max.png`), CSS transition effects, sound file integration (`high.mp4`, `low.mp4`), and Netlify deployment setup.

Made with ❤️ at TinkerHub Useless Projects

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)

![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)
