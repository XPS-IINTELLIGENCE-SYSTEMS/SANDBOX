# COMPONENT_REGISTRY

## Workspace components

### idea-intake
Transforms a raw idea into a structured system brief.

### consultant-template-router
Uses AI Consultant template flow to decide which documents must exist before scaffolding.

### canon-builder
Creates missing canon docs before claiming system readiness.

### target-profile-manager
Represents the requested system as a target profile instead of a rename.

### recursive-builder
Runs one bounded pass: rehydrate, classify, build, verify, log.

### scaffold-generator
Produces repo structure, framework shell, package layout, and starter contracts.

### scheduler-controller
Produces the recurring loop prompt and schedule manifest.

### validation-gate
Stops unsafe promotion, missing canon, unverified writes, or architecture drift.

### release-controller
Packages validated workspace outputs into a promotion-ready artifact set.

## Shared surfaces
- repo canon
- Drive templates
- Vercel deploy shell
- scheduler handoff
- quarantine register
