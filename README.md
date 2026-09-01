# SearchCanvas

SearchCanvas is a lightweight search-interface project built with semantic HTML and CSS. The current baseline recreates the essential structure of a familiar search landing page: a centered brand image, search field, and two primary actions. The project will evolve into an original, accessible, keyboard-friendly search experience without depending on a frontend framework.

## Current capabilities

- Minimal search landing-page layout
- Centered logo, query field, and action buttons
- Plain HTML and CSS with no build step
- Small codebase suitable for learning browser fundamentals

## Technology

- HTML5
- CSS3
- Browser-native form and accessibility APIs planned for future iterations

## Project structure

```text
Google Clone/
├── index.html     # Page structure
├── styles.css     # Layout and component styles
└── google.png     # Existing image asset
```

## Run locally

No dependencies are required.

1. Clone the repository.
2. Open `Google Clone/index.html` directly in a browser.

For consistent local URLs, start a small HTTP server from the repository root:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/Google%20Clone/`.

## Development direction

SearchCanvas will move away from a static visual exercise and become a complete standalone search interface. Planned work includes semantic forms, query submission, configurable search providers, keyboard shortcuts, accessible labels and status messages, recent-search storage, suggestion rendering, theme preferences, responsive layouts, offline behavior, unit tests, browser tests, and privacy-focused settings.

## Quality goals

- Preserve a fast, dependency-light experience
- Support keyboard-only and screen-reader navigation
- Avoid misleading claims or branding
- Keep search-provider behavior explicit and configurable
- Validate layouts across mobile and desktop widths
- Add tests alongside interactive behavior

## Contributing

1. Create a focused branch from `main`.
2. Keep each pull request limited to one behavior or quality improvement.
3. Test with keyboard navigation and a mobile-sized viewport.
4. Include manual verification steps in the pull-request description.

## Trademark notice

SearchCanvas is an independent interface project. Third-party product names and images remain the property of their respective owners and should be replaced as the project identity is completed.

## License

Add a project license before redistributing modified versions.