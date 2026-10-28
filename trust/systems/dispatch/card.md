# AI TrustBOM system card

> **draft (unapproved)**

## Identity

- **System:** Dispatch Service
- **Repository:** `portfolio-service`
- **Commit:** `10870bcce49b680dca7ca5c77addca5ed5012aa5`
- **Graph fingerprint:** `404632fc8ed3`
- **Full fingerprint (SHA-256):** `404632fc8ed35e55e5f608a1aa7146b63fbcd79a8ef8dac9e5788d6a050ffcff`
- **CLI version:** `1.0.0`
- **Description:** MTP-27 synthetic dispatch service.

## Draft classification

- **Role:** `unknown`
- **GPAI provider:** `false`
- **High risk:** `unknown`
- **Article 50:** `unknown`

## Models

| Provider | Model | Region | Endpoint | Source | Cite |
|---|---|---|---|---|---|
| openai | gpt-4o | us-east-2 | https://api.openai.com/v1 | manual | `apps/dispatch/trust/manual.yml:3` |

## Declared subprocessors

| Provider | Party | Purpose | Location | DPA path | Cite |
|---|---|---|---|---|---|
| openai | OpenAI (US) | Synthetic dispatch inference | United States | trust/dpas/openai.md | `trust/dpas/openai.md`<br>`trust/subprocessors.yml:7` |

## Data handling

Trust declares, for each AI provider used by this system, how long prompts and customer data are retained, whether that data is used to train provider models, and how deletion is requested. AI TrustBOM does not read, fetch or verify provider terms. "unknown" means Trust has not declared the value; it is not a statement that data is retained, used for training, or safe.

| Provider | Prompt retention | Training use | Deletion path | Source | Cite |
|---|---|---|---|---|---|
| openai | unknown | unknown | unknown | undeclared | none |

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

Commit `10870bcce49b680dca7ca5c77addca5ed5012aa5` using AI TrustBOM CLI `1.0.0`.

