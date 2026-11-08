# Editing workflow

1. Inventory footage: duration, orientation, frame rate, audio and colour metadata.
2. Review motion across each candidate moment, not just a single thumbnail.
3. Record selections as source file plus input/output times. Reject intersecting intervals from the same source and duplicate source files.
4. Choose music for the requested language, theme and energy. Analyse its pulse and audible start; verify low-confidence tempo estimates with a second method.
5. Assemble a narrative: animated opener, training progression, strong actions and a deliberate finish. Never extend a timeline by repeating the same moment.
6. Apply smooth transitions, selected speed ramps and consistent colour management. Check frame accounting after overlapping transitions.
7. Normalize audio using measured loudness. Default to approximately -14 LUFS with true-peak headroom for AAC encoding; verify the actual export.
8. Export for the intended playback environment. For compact vertical delivery, a starting profile is HEVC/hvc1, 1080×1920, 30 fps, approximately 6 Mbps video, AAC stereo, BT.709 and faststart. Adapt to the source rather than assuming every job is vertical.
9. Fully decode the result, review every scene and transition, and check duration, audio start, clipping, silence, black frames and freezes.
10. Copy the deliverable to the requested location and verify that its checksum matches the checked render.

## Local session convention

Keep source files, music, plans, intermediates and reports in `local/`. A plan should identify both prepared media and original source time ranges so a cached render cannot hide repeated footage.

## Reference tooling

The initial local session used FFmpeg and the third-party [video-editor skill](https://github.com/genchebur90-debug/video-editor-skill/tree/main/video-editor). That package is not vendored or relicensed here. Review its license and instructions before reuse or redistribution.
