# Pattern Studio

A single-file web tool for designing building surfaces made of many small parts (bricks, timber sticks and planks, pavers, tiles, cut sheet) and sending them to fabrication: drawings, schedules and robot programs. Built for ARCH 540 (UBC M.Arch), Assignment 2.

**Open `index.html` (or `tool/pattern-studio.html`) in a browser. That is the whole install.** No build step, no server. It loads three.js r128 from cdnjs and Google Fonts. On GitHub Pages, `index.html` is the tool.

## What is in this folder

| Folder | What |
|---|---|
| `index.html`, `tool/pattern-studio.html` | The tool (passes 1 to 126). 341 automated checks pass (`python tool/qa/run-qa.py`). |
| `designs/` | One folder per design. Each holds, in this order: `1-demo-…-full.mp4` (the tool tutorial, then the robot film), `2-speaker-notes-….pdf` (a timed script for that film), `parts/` (the tutorial and robot film on their own; dark and light versions where made), `stills/`, `rhino/` (the Rhino scene the robot film was made from). |
| `designs/00-whole-tool` | A tour of every panel of the tool, with its notes. |
| `HANDOFF.md` | State of the work, what is not finished, how to continue. |
| `tool/DEVELOPER-NOTES.md` | Every pass, every function name, every rule learned. |

## The designs

1. **Brick gallery facade** · a redesign after the Chi She gallery facade (Archi-Union Architects, Shanghai): a 22 m street facade under gables or a straight top; an open bond that opens toward the top, a belly of brick over the door; laid by a robot from a rising lift.
2. **Twisted brick tower** · an open-bond tower turned 55 degrees from foot to head and drawn in at mid-height; every brick rests on at least 59 % of its bed.
3. **Curved brick wall** · a pleated brick curtain on a curve, with two swells.
4. **Timber block wall** · the curved wall's twin in oak blocks, dowelled course to course.
5. **Timber pavilion** · straight sticks stacked at right angles and cut to a carved volume: a canopy you can stand under, a passage, a hollow.
6. **Interlocking plywood tunnel** · 1,166 short plywood planks half-lapped at every crossing, winding in plan.
7. **Lattice wall** · straight laths bent into geodesics and bolted at every crossing.
8. **Permeable modular pavers** · a paved ground whose pavers open toward planted joints along a route.
9. **Pocket park** · rectangular modular pavers of five sizes and tones, a winding path, planted beds and seats; laid by a mobile robot.

The robot motion in every film is illustrative (a KUKA KR120 R2900; no collision check). Construction details stated in the tool and the notes are first checks, not an engineer's design, and say so.
