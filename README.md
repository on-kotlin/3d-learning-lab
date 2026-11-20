# 3D Learning Lab

Interactive, lesson-first 3D views that help students learn science by exploring, not just watching.

> Status: early stage — planning and initial setup. No working demo yet.

## Why

Existing tools like Sketchfab (model gallery) and BioDigital (anatomy-focused) are great for viewing 3D models, but they aren't built around actual lessons. 3D Learning Lab ties every 3D scene to a curriculum topic with guided steps and quick checks, so students learn by doing.

## Planned features

- **Lesson-first 3D scenes** — each scene maps to a curriculum topic, with step-by-step guided tasks.
- **Clickable labels & explanations** — rotate, zoom, and click parts of a model to learn what they are and what they do.
- **Quick quizzes** — short checks tied to each lesson.
- **Teacher lesson editor** — turn a 3D model into an interactive lesson (labels, steps, questions) without writing code.
- **AI tutor (later)** — students ask questions about the part they're looking at, answered in the context of the current scene.

## First module

Middle school life science, aligned with **NGSS MS-LS1** (from molecules to organisms: structures and processes):

- 3D animal cell — organelles with labels and functions
- 3D human heart — chambers, valves, and blood flow

## Roadmap

| Phase | Scope |
| --- | --- |
| Week 1–2 | Three.js viewer, 3D cell and heart models, clickable labels, guided 5-step lesson |
| Week 3–4 | Simple teacher editor and quiz |
| Next | Share with teachers for feedback, iterate, expand to chemistry and physics |
| Later | AI tutor, native Android version |

## Tech stack (planned)

- [Three.js](https://threejs.org/) for 3D rendering in the browser
- Vite + TypeScript
- Runs in any modern browser, including low-end tablets and phones

## License

TBD
