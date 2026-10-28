# AI TrustBOM system card

> **draft (unapproved)**

## Identity

- **System:** Assist Service
- **Repository:** `portfolio-service`
- **Commit:** `2e1f7303d50a47fe6c20add107135d11a7208479`
- **Graph fingerprint:** `282d4db7ac75`
- **Full fingerprint (SHA-256):** `282d4db7ac75b2aec2a6222ea58ef3fd2502f1df8db3727d0a1b435f7f6019af`
- **CLI version:** `1.0.0`
- **Description:** MTP-27 synthetic assist service.

## Draft classification

- **Role:** `unknown`
- **GPAI provider:** `false`
- **High risk:** `unknown`
- **Article 50:** `unknown`

## Models

| Provider | Model | Region | Endpoint | Source | Cite |
|---|---|---|---|---|---|
| anthropic | claude-sonnet-4-5 | eu-west-1 | https://api.anthropic.com | manual | `apps/assist/trust/manual.yml:3` |

## Declared subprocessors

| Provider | Party | Purpose | Location | DPA path | Cite |
|---|---|---|---|---|---|
| anthropic | Anthropic (Ireland) | Synthetic assist inference | Ireland | trust/dpas/anthropic.md | `trust/dpas/anthropic.md`<br>`trust/subprocessors.yml:2` |

## Data handling

Trust declares, for each AI provider used by this system, how long prompts and customer data are retained, whether that data is used to train provider models, and how deletion is requested. AI TrustBOM does not read, fetch or verify provider terms. "unknown" means Trust has not declared the value; it is not a statement that data is retained, used for training, or safe.

| Provider | Prompt retention | Training use | Deletion path | Source | Cite |
|---|---|---|---|---|---|
| anthropic | unknown | unknown | unknown | undeclared | none |

## Tools

| Name | Effect | Source | Cite |
|---|---|---|---|
| unknown | unknown | unknown | none |

## MCP servers

| Name | Connection | Source | Cite |
|---|---|---|---|
| unknown | unknown | unknown | none |

## Declared data

| Class | Sent to model | Source | Cite |
|---|---|---|---|
| unknown | unknown | unknown | none |

## Declared controls

| Control | Value | Source | Cite |
|---|---|---|---|
| unknown | unknown | unknown | none |

## Evaluation gates

| Name | Path | Source | Cite |
|---|---|---|---|
| unknown | unknown | unknown | none |

## Findings

| ID | Severity | Message | Cite |
|---|---|---|---|
| none | info | No open scan findings. | none |

## Coverage statement

This card describes only what AI TrustBOM detected in tracked repository files and what Trust declared manually. It does not establish that other AI use is absent: files, ecosystems and runtime behaviour outside the method below may contain AI use that was not detected.

**Detector packs used:**

- assist-dotnet 1.0.0
- assist-go 1.0.0
- assist-java 1.0.0
- assist-js 1.7.0
- assist-python 1.4.0
- data-processing 1.0.0
- raw-http 1.0.0

**Ecosystems found with detector support:**

- None found

**Ecosystems found without detector support (AI use unknown):**

- None found

**Not in scope (excluded by Trust):**

- None declared

**Method limits:**

- Models, regions and endpoints are matched only in allowlisted configuration files by detector-pack patterns.
- Ecosystems are recognised from manifest and lockfile names only.
- Source code is not parsed; there is no AST or call-graph analysis.
- Runtime behaviour, network traffic and deployed infrastructure are not inspected.
- Only files tracked in Git at the scanned commit are read.

Ecosystems are recognised from tracked manifest and lockfile names only; an ecosystem without a recognised manifest or lockfile is not listed.

## Generated from

Commit `2e1f7303d50a47fe6c20add107135d11a7208479` using AI TrustBOM CLI `1.0.0`.

## Gate assessment

- **Status:** passed
- **Summary:** The current graph matches its approval and has no blocking policy conditions.

### Semantic changes

- Changed model anthropic / claude-sonnet-4-5 region: eu-central-1 -\> eu-west-1.

### Next step

No approval action is required.

