# EV Charging Handshake

A CSS-only animated EV charging interface that visualizes the connection handshake between an electric vehicle and a charging station.

## Features

- Animated charging connector
- Connector and charging-port handshake animation
- Physical latch engagement animation
- Animated energy-flow pulses
- Charging status indicator
- Battery and power information display
- Responsive layout
- Reduced-motion accessibility support
- No JavaScript or external libraries

## Usage

Open `demo.html` directly in a modern web browser.

The component loads `style.css` from the same directory and requires no build tools, dependencies, or JavaScript.

## How It Works

The component uses HTML to define the charging-station interface and CSS animations to simulate the charging handshake.

The main animations include:

- `connector-handshake` — moves the connector into position
- `latch-engage` — simulates the connector locking
- `energy-flow` — creates the charging energy pulses
- `status-pulse` — animates the connection indicator
- `handshake-progress` — visualizes connection progress

## Accessibility

The component includes a `prefers-reduced-motion` media query so users who request reduced motion receive a static version of the interface.

## Technologies

- HTML5
- CSS3
- CSS Keyframe Animations

No JavaScript or external dependencies are required.
