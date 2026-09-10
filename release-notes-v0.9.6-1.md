# TaskRunner v0.9.6-1

## Updates

- Added a local AI planner with Ollama, LM Studio, and hosted OpenAI-compatible model profiles.
- Added reviewable generated task cards so users choose what to add with one click.
- Added Pocket offline mode, timer controls, notes, task creation, and encrypted queued sync.
- Added Mochi, coach renaming, clearer controls, and eight Pocket themes.

## Bug fixes and reliability

- Fixed delayed LAN listener checks being reported as definite host startup failures.
- Suppressed overlapping host-start attempts while the listener initializes.
- Made Pocket retries idempotent so dropped acknowledgments cannot duplicate changes.
- Kept Today, Inbox, Active, and Done views distinct as tasks change state.
- Aligned Windows installer metadata and public download links at v0.9.6-1.

## Known follow-up

Pocket task creation cancel behavior is being hardened so cancel always closes the flow without creating a task.
