# Gleaning the Cube

*An interactive Rubik's cube tutorial — in a single HTML file.*

A cheeky nod to the 1989 Christian Slater skateboarding film *Gleaming the Cube*, minus the skateboards, plus a solvable cube.

## What it is

A self-contained, zero-dependency single-page app that teaches the beginner (layer-by-layer) method with a live 3D cube:

- **3D sandbox** — drag to orbit, turn faces with buttons or the keyboard (`U D L R F B`, Shift for reverse), scramble, undo, and type your own move sequences.
- **Nine-stage tutorial** — notation, the Daisy, White Cross, first-layer corners, middle-layer edges, Yellow Cross, Yellow Face, corner placement, and the final edges. Each stage has loadable practice positions and a "Stuck?" troubleshooter.
- **Sequence player** — step forward *and* backward through any algorithm, with the current move highlighted.
- **Turn hints** — hover any turn button (or the next move in the sequence bar) to preview exactly which layer will move and in which direction; during a turn the moving layer is spotlighted with a direction arrow. Toggleable, on by default.
- **Progress tracking** — the stage chips watch the actual cube state and check off as your solve advances, pointing at what to work on next.
- **Drop in: last layer** — a drill mode that scrambles only the top layer for endless stage 5–8 reps.

Every algorithm and practice position was machine-verified move-by-move against a cube simulator during development.

## Running it

Open `index.html` in any modern browser. That's it — no build step, no server, no dependencies (fonts load from Google Fonts and degrade gracefully offline).

---

*No skateboards were harmed in the solving of this cube.*
