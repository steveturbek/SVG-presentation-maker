<image href="oxygen.svg" x="900" y="500" width="400" height="400"/>
<image href="turbek.png" x="300" y="500" width="400" height="400"/>

# SVG Presentation Maker

Creating presentations from markdown files

Steve Turbek turbek.com

---

## What Is This Tool?

The SVG Presentation Maker converts markdown files into interactive SVG-based presentations that run directly in your browser.

No complex setup. No dependencies. Just markdown and SVGs.

---

## Key Features

**Markdown-based slides** - Write your presentation in simple markdown

- **SVG graphics support** - Embed and display SVG images in your slides
- **Browser-based** - Runs entirely in the browser, no installation needed
- **Keyboard navigation** - Arrow keys to move between slides
- **Lightweight** - Minimal code, fast loading

---

## How It Works

1. Write your presentation in markdown
2. Use `---` to separate slides
3. Reference SVG files with the image syntax
4. Open in browser and present!

---

## Markdown Slide Format

Each slide is separated by `---` (three dashes)

```
# Slide Title
```

Content goes here

---

## Adding Images

Use the standard image tag to include SVG graphics:

```
<image href="image.svg" x="0" y="0" width="400" height="400"/>
```

- Position and size your images with x, y, width, and height attributes
- SVG files will be integrated, PNG and JPG files will be referenced.
- File must be in the folder path in the image tag in presentation.md

---

## Backgrounds

Backgrounds are images

```
<image href="BG.svg" x="0" y="0" width="100%" height="100%"/>
```

---

## Navigation

- **Right Arrow** / **Space** - Next slide
- **Left Arrow** - Previous slide
- **Home** - First slide
- **End** - Last slide

Simple keyboard controls for smooth presentations

---

## File Structure

```
/files
  ├── presentation.md    (your markdown content)
  ├── image1.svg        (SVG graphics)
  ├── image2.svg
  └── ...
```

Keep your markdown and SVG files in the files directory

---

## Why SVG Presentations?

- **Infinite scalability** - SVG graphics never pixelate
- **Small file sizes** - Vector graphics are compact
- **Interactive potential** - SVGs can include animations and interactivity
- **Portable** - Single SVG file can contain text and SVGs
- **Designer-friendly** - Create graphics in Figma or Illustrator

---

## Getting Started

1. Edit `presentation.md` with your content
2. Add any SVG graphics to the `files` directory
3. Experiment with different layouts and SVG graphics.
4. Use the tool to generate your `presentation.svg`
5. Open in your browser
6. Present!

---

## Perfect For

- Quick presentations and demos
- Design portfolios showcasing SVG work
- Teaching and workshops
- Technical talks with code examples
- Any presentation where you want full control

---

## Open Source

This tool is open source and free to use.

Modify it, extend it, make it your own.
