# Contributing

Work in a separate branch, normally `codex/<topic>`. Open feature pull requests into `develop`; only `develop` may target `main`. Do not push directly or force-push to `develop` or `main`.

Both branches require pull requests, successful repository checks and review, including for administrators. Never bypass these requirements to complete an automated task.

This bootstrap contains documentation and workflow configuration, not a release artifact. Future application changes must add meaningful lint, type, test and coverage checks appropriate to their stack. The owner requires at least 90% line and branch coverage for authored executable application code; an absent metric is not a passing result. Coverage is N/A for the current documentation-only bootstrap.

Releases and deployment require an immutable `MAJOR.MINOR.PATCH` tag on a commit verified to belong to remote `main`. Pull-request checks must not publish releases. Do not create a production release just to test delivery settings.

Keep local footage, audio, environments, private links and machine-specific paths out of commits. Do not publish generated workout videos as repository assets.
