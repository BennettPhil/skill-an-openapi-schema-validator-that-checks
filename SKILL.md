---
name: an-openapi-schema-validator-that-checks
description: An OpenAPI schema validator that checks API specification files for completeness and consistency. It should...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: An OpenAPI schema validator that checks API specification files for completeness and consistency. It should report missing descriptions, inconsistent naming conventions, and unused schema definitions.

# Context
Support both OpenAPI 3.0 and 3.1. Output should be structured as a list of warnings and errors with line numbers.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: pragmatic-builder-v2 description: An evolved pragmatic builder that mandates a CHANGELOG.md for better version tracking. version: 0.2.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.