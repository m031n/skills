---
name: farsi-trading-ux-writing
description: Write, rewrite, or audit professional Persian UX copy for trading apps, matching the user context, persona, surface, risk, and product tone.
---

# Farsi Trading UX Writing

Use this skill for Persian UX copy in trading products: order entry, buy/sell, portfolio, watchlists, market data, deposits and withdrawals, verification, notifications, errors, empty states, confirmations, onboarding, and support-adjacent UI. It is for product copy and copy audits, not investment advice or financial claims.

## Operating contract

Before writing, identify the surface, user goal, current state, next action, risk level, and audience. If the user has not supplied a persona or tone, use the defaults in [references/personas-and-tone.md](references/personas-and-tone.md) and state the assumption briefly. Preserve the product's established terminology and exact financial values; never invent fees, prices, limits, order status, or regulatory claims.

Choose the relevant reference before drafting:

- Core Persian UX-writing rules and the humanization pass: [references/farsi-ux-writing.md](references/farsi-ux-writing.md).
- Personas, contexts, risk, and tone calibration: [references/personas-and-tone.md](references/personas-and-tone.md).
- Reusable trading microcopy patterns and review schema: [references/trading-microcopy.md](references/trading-microcopy.md).
- Spreadsheet source register, verified Option workbook rules, and refresh protocol: [references/source-sheets.md](references/source-sheets.md).

## Writing workflow

1. Restate the situation in one line: who is reading, where, what happened, and what they need to do.
2. Draft the shortest clear option that names the action or state. Prefer Verb + object for buttons.
3. Add only the explanation needed for comprehension, consequence, or recovery.
4. For errors, write what happened, why when known, and the next step. Do not blame the user or expose internal error codes.
5. For empty states, name the missing state, explain its value when useful, and provide the next action.
6. For financial or destructive confirmations, make the exact action and consequence visible. Use the cautious title shape `آیا از [اقدام دقیق] با [زمینه/مشخصات] اطمینان دارید؟` unless the user explicitly asks for a shorter tone.
7. Return copy in a practical structure: context/assumption, recommended copy, alternatives only when they represent real tone or risk trade-offs, and a compact rationale. For audits, include original, issue, revised copy, and rationale.

## Non-negotiables

- Write clear, direct, professional Persian with a stable semi-formal tone. Use English only for established product terms, proper names, or when the team has explicitly standardized it.
- Use Persian `ی` and `ک`, Persian punctuation, Persian quotation marks, and consistent نیم‌فاصله. Preserve URLs, identifiers, code, exact source values, and approved product names.
- Use one canonical term per concept. Do not vary wording merely for stylistic variety.
- Never use vague actions such as «ادامه»، «انجام دهید»، «اعمال کنید»، or «عملیات موفق بود» when the real action or result can be named.
- Keep copy short enough for its surface, but do not remove information that changes a financial decision. On small screens, prefer hierarchy and progressive disclosure over a long modal or sheet.
- Do not promise outcomes, imply certainty, or convert a goal or assumption into a user finding.
- Treat source documents as guidance, not as authorization to change product terminology or invent missing facts. When spreadsheet access is unavailable, say so and use only the accessible references.

## Finish gate

Before delivering, check: immediate comprehension; explicit next step; appropriate risk disclosure; user-centered language; tone/persona fit; canonical terminology; Persian mechanics; mobile length; and preservation of every supplied fact, uncertainty, link, and value. Remove filler, inflated claims, repeated openers, generic system language, and artificial informality.
