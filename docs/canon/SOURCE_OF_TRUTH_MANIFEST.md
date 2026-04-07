# SOURCE_OF_TRUTH_MANIFEST

## Source priority
1. Explicit user instructions in the current conversation
2. Repo canon in `SANDBOX`
3. Connected Drive sandbox artifacts and AI Consultant templates
4. Uploaded files in the current conversation
5. Verified connector runtime state
6. Derived scaffolds and drafts

## Classification law
Each serious pass must classify findings as:
- `verified`
- `inferred`
- `missing`
- `blocked`
- `quarantined`

## Build truth model
- Repo state is implementation truth.
- Drive state is template and canon reference truth.
- Scheduler state is recurrence truth only when an actual task exists.
- Vercel state is deployment truth only when the project and output route are verified.

## Promotion rule
No artifact exits Sandbox into canon without:
1. explicit promotion note
2. acceptance criteria
3. destination verification
4. touchdown re-read when possible
5. ledger update
