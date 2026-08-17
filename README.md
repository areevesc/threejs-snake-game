# Three.js Snake Game

A neon, cyberpunk Snake game rendered in 3D with [Three.js](https://threejs.org/).

## Play

[Play Three.js Snake Game](https://areevesc.github.io/threejs-snake-game/)

## Controls

- WASD or arrow keys: steer on desktop
- Swipe across the playfield: steer on mobile
- Space, a tap, or the on-screen pause button: pause or resume
- R: restart

The arena wraps at every edge while the locked camera pans across the board to catch each wrap. Collect the glowing food, avoid colliding with your own body, and beat your saved high score.

## Run locally

Serve this folder with any static web server and open index.html. For example:

~~~powershell
python -m http.server 8000
~~~

Then visit <http://localhost:8000/>.

Three.js 0.160.0 and its post-processing modules load from unpkg at runtime.
