# Accessible Names

## Purpose

Define the accessible names standard for SearchCanvas so the lightweight search interface remains accessible, privacy-conscious, and predictable across browsers.

## Current baseline

SearchCanvas currently contains a static HTML and CSS search layout with no build step or active search integration. This guide separates current behavior from planned functionality.

## Acceptance criteria

- The accessible names requirement is explicit and observable.
- Keyboard, touch, and assistive-technology behavior is considered.
- Query and navigation behavior avoids surprising redirects.
- Privacy and local-storage impact is documented.
- Fallback and recovery behavior is clear.

## Verification checklist

- [ ] Open the page through a local HTTP server.
- [ ] Test keyboard-only interaction.
- [ ] Check mobile and desktop viewport sizes.
- [ ] Confirm the browser console has no new errors.
- [ ] Confirm no tracking or credential data is introduced.

## Review guidance

Keep implementation work focused on one accessible names outcome and avoid copying third-party branding or behavior without review.