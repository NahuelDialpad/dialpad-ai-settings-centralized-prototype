# Dialpad centralized AI settings concept

A presentation-ready, self-contained prototype for managing AI governance from one dedicated destination in Dialpad Admin.

The proposed model brings three local views together:

- **Company** sets the global AI ceiling and keeps Data sharing separate.
- **Offices** support comparison, bulk administration, and complete in-place configuration.
- **Calling Groups** combine Departments, Contact Centers, and Coaching Teams without losing their Office hierarchy.

## Run the prototype

Open `index.html` in a modern browser. No install, build, account, or network connection is required.

For a local web server, run this command from the prototype directory:

```sh
python3 -m http.server 8765
```

Then open `http://127.0.0.1:8765/#/ai-settings/company`.

## Suggested presentation path

1. Open **Presentation guide** at the bottom-right of the prototype.
2. Start at **Company** to establish the global ceiling and distinct capability decisions.
3. Move to **Offices** to show the scalable table, bulk changes, and in-place detail drawer.
4. Move to **Calling Groups** to show the consolidated entity model, filters, and recording disclaimer.
5. Use **Reset** before another walkthrough to restore the seeded state.

## Prototype boundaries

- Uses sample data only.
- Makes no network requests and does not collect or persist data.
- Demonstrates product behavior and information architecture, not production implementation or final visual design.
- Excludes User AI settings, Agent Builder, routing, licensing, connectors, credentials, and RBAC redesign.

This experiment is independent from the existing entity-based prototype and should be deployed to a separate site or repository.
