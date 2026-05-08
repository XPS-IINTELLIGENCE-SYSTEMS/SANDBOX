# Strategic Minds OS Local Runner

This folder contains local-runner setup instructions.

The runner is intended to run on the operator's Windows machine and process approved command rows from the Command Center workbook.

## Responsibilities

- read approved/scheduled command rows
- run safe local scripts
- run benchmark scraper
- sync outputs to Drive
- sync sandbox repo
- write logs locally

## Safety rules

- do not store secrets in the repo
- do not run production deploy commands without approval
- do not publish Shopify live changes
- do not run Supabase production migrations
- do not call paid APIs unless a row is marked approved

## Scheduler

Use Windows Task Scheduler to run the local runner every 5 or 15 minutes.

Command:

powershell -NoProfile -ExecutionPolicy Bypass -File "C:\SMA\SHOPIFY_WORKFLOW_SYSTEM\Code\scripts\90-smos-local-runner.ps1"
