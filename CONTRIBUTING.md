# Contributing

Thank you for helping improve Human Simple Frontstage.

## Before you begin

- Search existing issues before opening a new one.
- Keep suggestions grounded in a real user or product-writing problem.
- Preserve meaning, factual accuracy, privacy, dignity, and accessibility. Clear Persian must never come at the cost of truth.

## What makes a strong contribution

Useful contributions include:

- clearer or safer Persian frontstage wording;
- practical before-and-after examples;
- terminology improvements with context;
- documentation fixes; and
- validation or packaging improvements that keep the skill portable.

Please avoid broad rewrites without context. For language changes, include the original text, proposed wording, audience, and why the change is better.

## Local validation

From the repository root, install the validator dependency if needed:

```bash
python3 -m pip install pyyaml
```

Then validate the skill:

```bash
python3 .github/skill-tools/quick_validate.py skills/human-simple-frontstage
```

To produce a local package:

```bash
python3 .github/skill-tools/package_skill.py skills/human-simple-frontstage dist
```

## Pull requests

- Keep each pull request focused on one outcome.
- Explain the user impact and any trade-offs.
- Update relevant examples or references when behavior changes.
- Ensure the validation workflow passes before requesting review.

By contributing, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
