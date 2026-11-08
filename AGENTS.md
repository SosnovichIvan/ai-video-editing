# AI Video Editing

- Work only in this project. Never write into a neighbouring project such as archDesign.
- Read README.md and docs/editing-workflow.md before editing video.
- Existing private session context is in local/CONTINUATION.md when present. It must never be committed.
- Media, downloads, environments, render plans, session state and generated files belong in ignored local/ directories. Final copies go to the location requested by the user.
- Reuse the locally available video-editor skill after reading its SKILL.md. Follow its measured audio, colour-management and quality-control practices.
- Keep an auditable mapping from each output scene to its original source time range. Reject repeated or overlapping source intervals.
- Preserve prior deliverables unless the user requests replacement.
- Inspect every scene and transition and fully decode the actual final export before delivery.
- Follow CONTRIBUTING.md for branches, review, verification and release rules. Never bypass protected branches.
- Do not upload personal footage, music, logs, private URLs, credentials or machine-specific paths to the public repository.
