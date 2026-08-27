# Accessibility Audit Report

## Audited Website

National Internship Portal  
https://internship.aicte-india.org/

## Audit Method

The website was evaluated using:
- Google Lighthouse Accessibility audit
- Manual keyboard-only navigation

## Lighthouse Findings

| # | Issue | WCAG Reference | Severity | Recommended Fix |
|---|---|---|---|---|
| 1 | ARIA attributes do not match their roles | WCAG 4.1.2 | High | Use valid ARIA attributes that match the element role. |
| 2 | Required ARIA children are missing | WCAG 4.1.2 | High | Add the required child roles/elements for the ARIA component. |
| 3 | Buttons do not have an accessible name | WCAG 4.1.2 | High | Add visible text or an accessible label such as `aria-label`. |
| 4 | Images do not have `alt` attributes | WCAG 1.1.1 | High | Add meaningful alternative text to informative images. |
| 5 | Links do not have a discernible name | WCAG 2.4.4 | High | Give links meaningful visible text or an accessible name. |

## Keyboard-Only Navigation

**Result: PASS — No blocking issue observed.**

The website was tested using keyboard navigation without relying on a mouse. Interactive elements could be reached using the keyboard and no blocking keyboard trap was observed.

## Evidence

Lighthouse screenshots are stored in:

`docs/screenshots/`

The screenshots provide evidence for the accessibility issues identified above.

## Remediation Priority

1. Fix inaccessible buttons and links.
2. Add missing alternative text to images.
3. Correct invalid ARIA usage.
4. Fix missing required ARIA child elements.
5. Repeat Lighthouse and keyboard-only testing after remediation.

## Conclusion

The audit identified several accessibility improvements related to ARIA usage, accessible names, alternative text, and link semantics. Keyboard-only navigation did not reveal a blocking issue during the manual pass.
