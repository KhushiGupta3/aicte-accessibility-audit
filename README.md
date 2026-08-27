# AICTE Accessibility Audit Project

## Project Overview

This project documents an accessibility audit of the AICTE Internship Portal and provides a maintainable monorepo-style project foundation.

## Audited Website

Website: https://internship.aicte-india.org/

## Accessibility Audit

The website was audited using Google Lighthouse and a manual keyboard-only navigation pass.

The audit identified issues related to:
- ARIA attributes and roles
- Missing required ARIA child elements
- Buttons without accessible names
- Images without alternative text
- Links without discernible names
- Colour contrast
- List structure

## Keyboard-only Navigation

**Result:** Pass — no blocking issue observed during the manual keyboard-only navigation pass.

The website was tested using keyboard navigation without relying on the mouse.

## Repository Structure

- `client/` - Frontend application and UI components
- `server/` - Backend/API layer
- `docs/` - Accessibility audit reports and supporting evidence
- `tests/` - Automated and accessibility tests

## Remediation Priority

The identified accessibility issues should be prioritised for remediation based on their impact on users of assistive technologies.

## Local Setup

Clone the repository and install the required dependencies for the client and server.

## First Vertical Feature Slice

The first feature slice will cover an accessible dashboard component from the user interface through the server/API layer, with accessibility tests included in the test directory.
