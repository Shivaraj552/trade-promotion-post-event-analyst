# Trade Promotion Post-Event Analyst

## 1. Project Overview

Build an AI-powered application that analyzes trade promotions using approved statistical methods.

The application will help users understand whether promotional campaigns increased sales and whether the results are statistically reliable.

## 2. Development Methodology

Follow Spec-Driven Development (SDD).7

Before writing or modifying code:

1. Read the Business Requirements Document.
2. Review the application architecture.
3. Understand the acceptance criteria.
4. Prepare an implementation plan.
5. Implement the approved functionality.
6. Write and execute tests.
7. Review the implementation against the requirements.

## 3. Technology Guidelines

Proposed technology stack:

* Python for backend development.
* FastAPI for REST APIs.
* OpenAI Responses API for natural-language interaction.
* SQLite for initial local development, if persistence is required.
* HTML, CSS and JavaScript for the user interface.
* Pytest for automated testing.
* Docker for containerization.
* Git and GitHub for version control.

Technology choices must be justified in the architecture documentation.

## 4. AI Development Rules

* Use AI to interpret user requests and explain results.
* Do not allow AI to invent statistical calculations.
* Use approved Python functions for numerical analysis.
* Validate all inputs before running calculations.
* Do not fabricate missing data.
* Do not present unsupported conclusions.
* Return reproducible results with supporting evidence.

## 5. Statistical Analysis Rules

The application must support:

* Documented baseline calculations.
* Control-group selection.
* Promotional uplift analysis.
* Confidence intervals.
* Validation using synthetic datasets.
* Detection of incomplete reporting periods.
* Reproducible calculations.

Statistical methods must be reviewed, documented and tested before implementation.

## 6. Repository Instructions

* Keep backend code inside `backend/`.
* Keep frontend code inside `frontend/`.
* Store documentation inside `docs/`.
* Store automated tests inside `tests/`.
* Use synthetic or approved public datasets inside `data/`.
* Maintain reusable skills inside `.agents/skills/`.
* Follow applicable folder-level `AGENTS.md` instructions.

## 7. Security Rules

* Never hardcode API keys or passwords.
* Use environment variables for secrets.
* Never commit `.env` files containing credentials.
* Do not use confidential customer or company data.
* Validate untrusted inputs.
* Use appropriately restricted execution environments.
* Follow secure coding practices.

## 8. Testing Requirements

* Write unit tests for statistical calculations.
* Validate results against known synthetic effects.
* Test incomplete-data refusal behavior.
* Test reproducibility across repeated executions.
* Run automated tests before merging changes.
* Maintain CI checks for approved statistical methods.

## 9. Documentation Requirements

Maintain the following documents:

* `README.md`
* `docs/BRD.md`
* `docs/ARCHITECTURE.md`
* `docs/REQUIREMENTS.md`
* `docs/TASK_PLAN.md`
* `docs/ACCEPTANCE_CRITERIA.md`
* `docs/EVALUATION.md`
* `docs/SECURITY.md`
* `docs/RUNBOOK.md`

## 10. Definition of Done

A feature is complete only when:

1. It meets the approved requirements.
2. Its implementation has been reviewed.
3. Relevant automated tests pass.
4. Statistical outputs are validated.
5. Security requirements are satisfied.
6. Documentation is updated.
7. The feature is ready for integration.

## 11. Codex Instructions

When working on this repository:

* Read this file before making changes.
* Follow the relevant folder-level instructions.
* Use reusable skills when applicable.
* Explain proposed changes before implementation.
* Keep changes focused on the requested task.
* Avoid modifying unrelated files.
* Execute relevant tests.
* Report any failures, assumptions or limitations.
