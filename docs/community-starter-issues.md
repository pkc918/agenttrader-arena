# Community Starter Issues

These starter issues are designed for contributors who want to help improve the public AgentTrader experience without touching core trading, trust, risk, data, or protocol logic.

They are safe first contributions because they focus on public documentation, onboarding copy, helper surfaces, and non-core UI polish. Maintainers can copy each issue body into GitHub Issues as-is, use the matching templates under `.github/ISSUE_TEMPLATE/`, or contributors can use them to shape a focused pull request.

## Contribution Boundaries

Good starter work:

- Improve public-facing explanations.
- Clarify how first-time users should read the product.
- Make glossary, methodology, rules, and helper surfaces easier to understand.
- Keep copy aligned with the current product direction: public agent accounts, trade replay, trust summaries, risk and reliability signals, and verifiable track records.

Please avoid in starter issues:

- Core trust or risk logic.
- Trading, settlement, provider, route, or contract behavior.
- Internal governance or release documentation.
- Large visual redesigns or product-scope changes.

## Issue 1

### Title

`docs: expand public glossary for core AgentTrader terms`

### Body

#### Goal

Expand the public-facing glossary for the core AgentTrader terms so first-time readers can understand the product language more quickly.

#### Why this matters

Right now, the main pages and docs already use a relatively stable vocabulary, but new readers can still get stuck on terms like Trust Kernel, Passport, Replay, Trust Rating, Risk, Reliability, and Market Scope. A clearer glossary lowers onboarding friction and makes the product easier to explain externally.

#### Scope

- Add or expand short glossary entries for the core public terms.
- Keep wording user-facing, not internal or implementation-heavy.
- Make terminology consistent with the current public pages and user-facing docs.

#### Inputs

- Existing public-facing docs in the project.
- Current terminology alignment notes.
- Homepage, methodology, rules, and detail page language.

#### Expected output

- A cleaner glossary section or standalone glossary doc.
- Consistent definitions for the main user-facing terms.
- Wording that a non-technical reader can follow.

#### Please do not change

- Core trust/risk logic.
- Contracts, providers, or route behavior.
- Internal release or governance documentation.

#### Completion standard

- Core terms are covered.
- Wording is externally understandable.
- Terminology matches current user-facing product language.

## Issue 2

### Title

`docs: improve onboarding helper copy for first-time users`

### Body

#### Goal

Improve onboarding helper copy for users who are seeing AgentTrader for the first time.

#### Why this matters

The product now has enough structure that first-time readers need clearer guidance on what to look at first, why it matters, and how the major surfaces relate to each other.

#### Scope

- Improve helper copy that explains where a first-time user should start.
- Clarify the roles of homepage, leaderboard, detail, methodology, and rules.
- Keep the copy short, friendly, and product-facing.

#### Inputs

- Existing onboarding notes.
- Buyer-facing short materials.
- Current public page structure.

#### Expected output

- Improved first-time-user helper copy.
- A clearer "what to look at first" narrative.
- Better alignment between page order and user understanding.

#### Please do not change

- Core product logic.
- Data fetching behavior.
- Public route structure.

#### Completion standard

- A first-time user can understand where to start.
- Helper copy is clearer and less technical.
- The onboarding flow matches the current product surfaces.

## Issue 3

### Title

`docs: add docs-facing explainer blocks for methodology and rules`

### Body

#### Goal

Add or improve docs-facing explainer blocks for the methodology and rules surfaces.

#### Why this matters

Methodology and rules are already structurally useful, but they still benefit from short explainer blocks that help a non-technical reader understand what each section is trying to communicate.

#### Scope

- Add short explanation-oriented blocks.
- Improve transitions between sections.
- Keep wording consistent with the current trust/risk/replay language.

#### Inputs

- Current methodology page.
- Current rules page.
- User-facing terminology notes.

#### Expected output

- Better explanation blocks for methodology and rules.
- More readable, less abrupt section flow.
- Language that helps external readers understand the purpose of the pages.

#### Please do not change

- Core scoring logic.
- Public API behavior.
- Internal release documentation.

#### Completion standard

- Methodology and rules are easier to read for non-technical users.
- Explainer blocks fit the current product language.
- Terminology stays aligned with existing docs.

## Issue 4

### Title

`ui: polish non-core helper surfaces and empty states`

### Body

#### Goal

Polish non-core helper surfaces and empty states so they feel more consistent with the rest of the public product.

#### Why this matters

The major public pages are already much stronger than before, but some helper surfaces and empty states still feel lighter, more temporary, or less finished than the main experience.

#### Scope

- Improve non-core helper surfaces.
- Improve empty-state wording and presentation.
- Keep changes light and low-risk.

#### Inputs

- Current public pages.
- Existing UI polish and localization work.
- Current empty-state wording.

#### Expected output

- Cleaner helper-surface presentation.
- Better empty states.
- Improved consistency with the polished public pages.

#### Please do not change

- Core layout architecture.
- Main trust/risk logic.
- Main routing behavior.

#### Completion standard

- Helper surfaces look more intentional.
- Empty states read like product copy, not placeholders.
- No disruption to the main product flow.
