# Computer Graphics Research Map

A paper-led guide to computer graphics research, organized around major problem areas and the work that shaped them.

**Live site:** [hoytxu.me/cg-research-map](https://hoytxu.me/cg-research-map)

## About

This project began as a way to understand the breadth of computer graphics and to identify a direction for deeper study. The current version reflects a growing interest in physical simulation, so that area receives more detailed coverage than the others.

The map is a personal study aid rather than an exhaustive survey. It connects each topic to an earlier and a later representative paper, making it possible to move quickly from a broad research area to primary sources.

## What is included

The interactive outline groups the field into five problem-oriented areas:

- **Rendering & Appearance** — light transport, materials, ray tracing, denoising, and non-photorealistic rendering
- **Geometry & Modeling** — meshes, procedural modeling, and geometry acquisition or reconstruction
- **Animation & Physical Simulation** — character motion, deformable and rigid bodies, fluids, particle methods, and differentiable simulation
- **Imaging & Inverse Graphics** — computational photography, inverse rendering, and neural scene representations
- **Visualization & Interaction** — scientific and medical visualization, VR, AR, and MR

A separate reader presents chronological landmark-paper trails for rendering, geometry, physical simulation, and neural graphics. Selected papers include first-page previews that link to the full source.

## Using the map

Visit the [live site](https://hoytxu.me/cg-research-map), or open `index.html` directly in a modern browser.

- Select a research area to reveal or hide its subtopics.
- Use **Expand all** and **Collapse all** to control the complete outline.
- Follow the **Earlier** and **Later** links for representative work in each area.
- Select a paper preview or title in the landmark lists to open the source.

## Local development

The site is a self-contained HTML document with no build step or package dependencies. To serve it locally:

```sh
python3 -m http.server 8000
```

Then open [localhost:8000](http://localhost:8000). The paper preview images are stored in `assets/papers/`; the research data, styles, and interaction logic are contained in `index.html`.

## Design

The interface uses a restrained, print-inspired academic layout. It is responsive on narrow screens, supports keyboard interaction for expandable topics, and lazy-loads paper previews.

## Scope and roadmap

The collection is curated and necessarily incomplete. Planned extensions include:

- visual examples and historical context for individual subfields
- books, courses, software, datasets, and other learning resources
- directories of researchers, laboratories, and major publication venues
- additional landmark-paper trails and interactive demonstrations

Corrections and suggestions for important missing work are welcome.
