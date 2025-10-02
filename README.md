# splat

This is a WebGL implementation of a real-time renderer for [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/), a recently developed technique for taking a set of pictures and generating a photorealistic navigable 3D scene out of it.

You can [try it out here](https://dimakuzov.github.io/splat-viewer/).




## controls

movement (arrow keys)

- left/right arrow keys to strafe side to side
- up/down arrow keys to move forward/back
- `space` to jump

camera angle (wasd)

- `a`/`d` to turn camera left/right
- `w`/`s` to tilt camera up/down
- `q`/`e` to roll camera counterclockwise/clockwise
- `i`/`k` and `j`/`l` to orbit

trackpad
- scroll up/down to orbit down
- scroll left/right to orbit left/right
- pinch to move forward/back
- ctrl key + scroll up/down to move forward/back
- shift + scroll up/down to move up/down
- shift + scroll left/right to strafe side to side

mouse
- click and drag to orbit
- right click (or ctrl/cmd key) and drag up/down to move forward/back
- right click (or ctrl/cmd key) and drag left/right to strafe side to side

touch (mobile)
- one finger to orbit
- two finger pinch to move forward/back
- two finger rotate to rotate camera clockwise/counterclockwise
- two finger pan to move side-to-side and up-down

other
- press 0-9 to switch to one of the pre-loaded camera views
- press '-' or '+'key to cycle loaded cameras
- press `p` to resume default animation
- drag and drop .ply file to convert to .splat
- drag and drop cameras.json to load cameras

## other features

- press `v` to save the current view coordinates to the url
- open custom `.splat` files by adding a `url` param to a CORS-enabled URL
- drag and drop a `.ply` file which has been processed with the 3d gaussian splatting software onto the page and it will automatically convert the file to the `.splat` format
