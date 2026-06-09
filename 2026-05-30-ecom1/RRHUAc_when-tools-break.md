---
source_code: https://github.com/Vialov/BitGN_ECOM1
run_ids:
  - run-22RxFQ7A6JRUNgBvsTgHB9XAR
  - run-22RxEsHmRaHw7dvTizdEYQLTV
model_names:
  - Gemini 3.5-flash
  - Qwen/Qwen3.5-397B-A17B
author: Viktor Vialov
author_linkedin: https://www.linkedin.com/in/vialov/
impact: One sentence explaining the main architectural idea and why it mattered for ECOM1.
challenge: ecom
---

# Your ECOM1 Architecture Name

Briefly introduce the system. Mention which ECOM1 leaderboard or submitted run this writeup belongs to, what score or placement it reached if you want to share it, and the core idea in plain English.

## How does it work?

Describe the main loop and components.

- What starts a task?
- What context does the agent receive?
- Which tools or APIs can it call?
- How does it inspect state before acting?
- How does it decide that the task is finished?

## Models

List the LLM models you used and where they were used.

- Main solver:
- Classifier/router/planner, if any:
- Evaluator or evolution loop, if any:
- Runtime settings that mattered:
- Were all listed models open-weight/local models?

## E-commerce OS Reasoning

Explain how your agent handled the ECOM1 business world.

- Catalogue and product matching:
- Inventory, warehouses, shipping, and store coverage:
- Customer records, baskets, orders, and payments:
- Merchant policies and policy addenda:
- Support tickets, returns, refunds, and escalations:
- Audit trails, logs, and evidence:

## Acting, Refusing, and Escalating

Describe the guardrails.

- When is the agent allowed to mutate state?
- How does it verify authorization, identity, roles, or policy constraints?
- How does it handle pressure to apply discounts, refunds, checkout actions, or customer-data access that may be unsafe?
- When does it refuse, ask for clarification, or escalate instead of acting?

## Problems

What went wrong while building or running the agent?

- Failure mode 1:
- Failure mode 2:
- Failure mode 3:

## Solutions

What changes improved reliability?

- Prompt or rule changes:
- Tooling or runtime changes:
- Evaluation, rerun, or debugging changes:
- Things you deliberately kept simple:

## What Would You Improve Next?

Describe the next version you would build if you had more time.

## Lessons From ECOM1

What did this benchmark teach you about building agents for commerce, business operations, or policy-constrained workflows?

## Optional: Diagram

Put images in `res/` and link them like this:

```md
![Architecture diagram](res/YOUR_DIAGRAM.png)
```
