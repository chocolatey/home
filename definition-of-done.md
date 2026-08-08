# Definition of Done

The **Definition of Done** is all about the big picture, focusing on the overall quality and completeness of the project, feature, or [User Story](pathum25/user-story-and-acceptance-criteria.md#user-story). It’s a shared understanding among the team that sets the standard for what "done" means. The Definition of Done includes criteria like code quality, testing, documentation, and integration.

## The Outcome is Achieved

- [ ] The [Acceptance Criteria](./user-story-and-acceptance-criteria.md#acceptance-criteria) for the item are fully met.
- [ ] The work delivers the user or business value defined by the [User Story](./user-story-and-acceptance-criteria.md#user-story).
- [ ] Edge cases, error handling, and failure states are handled or explicitly documented.

## The Code Is Production-Ready

- [ ] Code follows team standards and linting rules.
- [ ] No new warnings, lint errors, or build failures are introduced.
- [ ] No leftover debug code, TODOs, or commented-out blocks without including the date, who made the change, and a clear reason for their presence.
- [ ] License information for product dependencies are correctly recorded in the `CREDITS.md`, `CREDITS.pdf`, and `CREDITS.json` files.

## It Is Tested and Verified

- [ ] Automated tests (unit, integration, Playwright, etc.) are added or updated as needed.
- [ ] All CI/CD checks pass.
- [ ] The change has been verified in the product's defined verification environment.

## It Is Accessible and Usable

- [ ] Keyboard navigation works.
- [ ] Semantic markup is used appropriately.
- [ ] No new accessibility violations are introduced.

## It Is Reviewed

- [ ] At least one human peer has reviewed and approved the work.
  - [ ] At least one Code Owner has reviewed and approved any dependencies that have been removed, added, or updated.
- [ ] All review comments are addressed or explicitly resolved.

## It Is Understandable

- [ ] Anyone can determine why the change was made and what it delivered.
- [ ] Any necessary documentation, screenshots, or notes have been added or updated.
- [ ] Future code maintainers can reason about the change without tribal knowledge.

## It Is Traceable

- [ ] The work is linked across systems:
  - [ ] Issue ↔ PR
  - [ ] Task ↔ Issue
  - [ ] Commit ↔ PR
- [ ] A clear trail from problem → solution exists.

## It Is Closed Cleanly

- [ ] The titles of all issues are clear and ready to be included in release notes.
- [ ] Status is set to Done and correct labels are applied.
- [ ] Final summary comment is added.
- [ ] No dangling or ambiguous state remains.
- [ ] Any follow-up work is captured and is visible.
