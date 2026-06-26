# BPM-diagrams
Process diagram versions (ie Diagrams-as-Code - Mermaid) archive for the [Process Diagram Converter](https://callgenix.com/process-diagram-converter.html).

## What is this?

This repository stores diagram code snapshots (.mmd files) as users save changes using the Process Diagram Converter tool. Each save creates a new commit with the updated diagram.

## File structure

Files are named by format:

```
jpeg_JPEG.mmd        — JPEG format diagram
drawio_DRAWIO.mmd    — Draw.io format diagram
pdf_PDF.mmd          — PDF format diagram
bpmn_BPMN.mmd        — BPMN format diagram
svg_SVG.mmd          — SVG format diagram
```

## How it works

1. User makes changes in the Process Diagram Converter
2. Clicks "Apply" to see the change
3. Clicks "Save to GitHub" to commit
4. New version appears in the history dropdown
5. Previous versions can be viewed anytime

## Commits

Each commit includes:
- Timestamp (UTC)
- Session ID and format name
- What changed (marked with `%% ⚡ CHANGED SECTION`)

Example: `[SESSION-260625-143052] Applied change to JPEG format — JPEG update`

## Version history

Versions are stored as separate commits on the main branch. The dropdown in the tool shows v-0, v-1, v-2, etc. (newest first).

You can view any previous version by selecting it from the history dropdown.
