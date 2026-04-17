# Project Notes

## Technical Debt

*   **Nextend Plugin requires DB secret storage** (Logged: 2026-04-17): The `nextend-facebook-connect` plugin does not natively support `wp-config.php` constants for its credentials and strictly requires database storage. The credentials were manually configured via the UI. The `.env` structure remains valid as our IaC blueprint.
