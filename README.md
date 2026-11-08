# AI Video Editing

ИИ-видеомонтаж · AI-assisted video editing.

A workspace for producing dynamic, music-driven video montages with an AI assistant and FFmpeg.

The first editing workflow focuses on training highlights: selecting distinct source moments, matching cuts to the music, adding slow motion at key actions, animating an opening image, and exporting compact HEVC video.

## Project status

The project workspace is initialized. Existing session scripts, original media, render plans and quality reports are kept locally under `local/`. This public repository currently contains project documentation, editing requirements and collaboration rules; it is not yet a packaged editing application.

## Editing principles

- Keep source selection traceable to its file and input time range.
- Do not reuse footage or overlap selected source intervals within one montage.
- Match transitions to measured musical accents; inspect the result visually.
- Start music at the first frame when requested and avoid abrupt audio endings.
- Use slow motion selectively for meaningful actions.
- Preserve the source orientation and manage HDR-to-SDR conversion explicitly.
- Check the exported file for decode errors, unintended black frames, freezes, clipping and silence.
- Describe HEVC exports as perceptually high-quality compression, not mathematically lossless video.

## Local material

`local/` is excluded from Git. Keep original footage, copyrighted tracks, downloaded tools, virtual environments, personal notes and generated exports there. Completed deliverables may also be copied to the Desktop.

Do not add media to the public repository without a separate publication request.

See [editing workflow](docs/editing-workflow.md) and [contribution rules](CONTRIBUTING.md).
