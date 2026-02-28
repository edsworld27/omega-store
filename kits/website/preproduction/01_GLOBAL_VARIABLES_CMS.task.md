# TASK: GLOBAL VARIABLES (THE HOT SWAP PROTOCOL)

*This protocol ensures the project can be rebranded/modified instantly from a single source of truth.*

## Objectives
- [ ] **Create CMS / Config File:** Generate a global configuration file (e.g., `src/config.ts` or `data/site.json`).
- [ ] **Populate Brand Data:** Add all primary, secondary, and tertiary colors (in Hex/HSL) based on the approved `AESTHETIC_LAYER`.
- [ ] **Populate Typography:** Define the global font families.
- [ ] **Populate Copy:** Centralize the Company Name, Phone, Address, Email, and primary Taglines.
- [ ] **Populate Links:** Centralize all Social Media URLs.
- [ ] **Architectural Weaving:** Ensure ALL UI components pull their data/styles from this config file. **ZERO hardcoding allowed** in the frontend components (e.g., use `bg-[var(--primary)]` instead of `bg-blue-500`, or pass the data as props `title={config.hero.title}`).

## The "Hot Swap" Mandate
If the client changes their brand name or color hex to a competitor's, the Developer should only have to change *one* line in this `config` file to update the entire site.

## Evidence Required
- [ ] The generated `config` file (or equivalent).
- [ ] Snippet showing a UI component correctly pulling data from this config.
