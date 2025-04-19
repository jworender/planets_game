# Solar System Simulation Game

This project is an interactive browser-based simulation of the solar system, featuring realistic orbital mechanics and a fun asteroid-launching game. Built entirely in HTML5 and JavaScript, it allows you to experiment with gravity, orbits, and collisions in a visually engaging way.

## Features

- **Realistic Solar System Model:** Includes the Sun and all major planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune) with accurate masses and orbital distances.
- **Asteroid Launching:** Click and drag anywhere on the screen to launch an asteroid with a custom trajectory and velocity.
- **Adjustable Parameters:**
  - **Asteroid Mass:** Change the mass of the asteroid before launch.
  - **Zoom:** Scale the view from close-up to wide solar system perspectives.
  - **Planet Gravity Factor:** Increase or decrease the gravitational pull of the planets.
  - **Initial Velocity:** Fine-tune the speed of your launched asteroid.
  - **Sun Scale Toggle:** Optionally display the Sun at its true scale.
- **Scoring System:** Earn points for each full orbit your asteroid completes around the Sun and for crossing planetary orbits. Lose points for colliding with planets.
- **Visual Effects:** Includes explosion animations for collisions and tooltips for planet names.
- **Touch Support:** Playable on both desktop and touchscreen devices.

## How to Play

1. **Open `planets.html` in your web browser.**
2. **Launch an Asteroid:** Click and drag on the canvas to set the direction and speed, then release to launch.
3. **Adjust Controls:** Use the sliders and checkboxes in the control panel (top left) to modify asteroid mass, zoom, gravity, and velocity.
4. **Score Points:** Try to achieve stable orbits and cross planetary orbits without colliding with planets.
5. **View Tooltips:** Hover over planets to see their names.

## Controls

- **Asteroid Mass:** Sets the mass (in kg) of the next asteroid to launch.
- **Zoom:** Changes the scale (meters per pixel) of the simulation.
- **Planet Gravity Factor:** Multiplies the gravitational pull of all planets.
- **Initial Velocity:** Adjusts the launch speed of the asteroid.
- **Sun to-scale:** Toggles the Sun's display between a visible size and its true scale.
- **Score:** Displays your current score.

## Technical Details

- Physics are simulated using Newtonian gravity.
- Time advances in 6-hour increments per animation frame.
- All calculations and rendering are performed client-side in JavaScript.

## Getting Started

1. Clone or download this repository.
2. Open `planets.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No installation or dependencies required.

## License

This project is open source and available under the MIT License.
