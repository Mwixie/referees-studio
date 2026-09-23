# The Referees Studio

Private development project for an animated-first documentary workflow. No public release authorised.

## Current prototype
`index.html` is a dependency-free browser scene planner. It includes three generic civic test scenes, editable narration and visual briefs, evidence notes, review status, archival replacement notes, a shared illustration style, prompt copying, image attachment and JSON export/import.

**It does not generate illustrations, audio or video. No model, external API, paid service or hosting is connected.** Starter wording is not approved film narration or a verified assessment of Zambia.

## Using it
Serve this folder with a local static web server for desktop testing, for example `python3 -m http.server 8000`, and open http://localhost:8000. An iPad needs a reachable, appropriately protected hosting environment; the GitHub file view does not run this app. Do not enable public hosting for production content without producer approval.

Changes are stored only in that browser, when available. Export JSON backups; import them on another device. Exported files include attached images and research notes. No automatic cloud sync or Muse/Notion integration is configured. Keep attached images below 2 MB; large projects can exceed browser storage, in which case export immediately.

## Development sequence
See [production plan](docs/production-plan.md). Test three coherent illustrations before choosing image-generation infrastructure, then test narrated motion and citations before expanding to a full film.

## Collaboration and safeguards
Track changes here and coordinate editorial notes by scene ID through the shared Notion production hub. Keep credentials outside client code and repository files. Code access and deployed-site access are separate. Keep the producer's legal name out of publication credits. Review source-code, model and asset licences before reuse. No third-party generator code has been imported yet.
