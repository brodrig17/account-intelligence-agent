# account-intelligence-agent
AI-assisted B2B account research that scores ICP fit, explains the evidence, and recommends relevant outreach angles.
# Account Intelligence Agent

## Purpose

Research B2B accounts and determine whether they match our ideal customer profile.

## Input

- Company name
- Company website
- Optional contact name

## Workflow

1. Validate the company domain.
2. Research the company.
3. Identify industry, size, technology and growth signals.
4. Score the account from 0–100.
5. Explain the score.
6. Create a short account brief.
7. Save the result to SQLite.

## Output

- Company summary
- ICP score
- Supporting evidence
- Potential pain points
- Recommended outreach angle

## Constraints

- Do not invent missing facts.
- Cite the source for every external claim.
- Require human approval before sending any message.
- Never store API keys in the repository.
