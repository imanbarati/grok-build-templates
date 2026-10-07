# HANDOFF — Grok Build in-app templates

If this session dies, continue from here. Do not re-scrape GrokForge; that was the wrong catalog.

## User intent

1. List every chip under **Create from Template** in Grok’s **Build** tab.
2. Let the user pick one.
3. Push the list to GitHub.
4. Later: build the picked template as a real app.

## Repo

https://github.com/imanbarati/grok-build-templates  
Owner: `imanbarati` (GitHub connector authenticated in the prior turn).

## What the video is

Mobile Grok → **Build** → empty state “Build apps and sites” → row labeled **Create from Template**.

Source video (sandbox): `/workspace/attachments/1000053448.mp4` (45.98s).
Dense chip-row frames: `/workspace/artifacts/template-frames/chipNNNN.jpg` (368 frames @ 8fps).

The dashed-circle **shuffle/refresh** control at the left of the row is **not** a template.

## Extracted names (46, left-to-right scroll order)

1. Mandelbrot zoom
2. Network graph
3. Tower defense
4. Event page
5. QR generator
6. Gravity sim
7. Terrain flyover
8. Kanban board
9. Prime explorer
10. Synth keyboard
11. Particle field
12. World map
13. 3D maze
14. Portfolio
15. Color palette
16. Physics sandbox
17. Solar system
18. Budget planner
19. Vector field
20. Audio visualizer
21. Fractal tree
22. Revenue dashboard
23. Platformer
24. Landing page
25. Meme generator
26. Boids flock
27. Starfield
28. Notes app
29. Function grapher
30. Drum machine
31. Flow field
32. Poll app
33. Space shooter
34. Bio page
35. Pixel art
36. Fluid ripples
37. Product viewer
38. Habit tracker
39. Fourier drawing
40. Chord player
41. Kaleidoscope
42. Endless runner
43. Photo booth
44. Game of Life
45. 3D globe
46. Pomodoro timer

## Incomplete

Video **ends** with Pomodoro timer fully on screen and the next chip only a sliver. Names 47+ are unknown.

Cycle 5 dropped the 5th data and site chips (Kaleidoscope is adjacent to Endless runner; Endless runner is adjacent to Photo booth). Confirmed on dense frames.

## Do next

- If the user names a chip: **build that app** (auth/db off unless they ask).
- If they want a longer list: request a second scroll video past Pomodoro.
- Do not scaffold an app just to display this list unless they ask.
