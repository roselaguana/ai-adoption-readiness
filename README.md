# AI Adoption Readiness

A self-contained diagnostic for leaders deciding whether their organization is actually ready to deploy AI agents: not whether the technology works, but whether the org will.

**Live:** https://ai-adoption-readiness.vercel.app

Built by [Rose Laguana](https://roselaguana.vercel.app).

## What it does

Score an organization 1 to 5 across six readiness dimensions, or load a demo company. The tool returns a readiness score and band, a per-dimension reading, and the single highest-leverage next move.

The six dimensions:

1. **Leadership & Sponsorship**: does an accountable executive own AI?
2. **Use-Case Clarity**: does the org know which problems to point AI at, and why those?
3. **Data & Tooling Foundation**: is there a substrate agents can actually run on?
4. **Workforce Capability & Literacy**: can the people, not just leadership, work alongside agents?
5. **Governance, Risk & Trust**: are boundaries, review, and autonomy rules defined?
6. **Change Capacity & Adoption**: will the change stick? The difference between a pilot and a habit.

The sixth dimension is the deliberate differentiator. Most readiness checklists stop at technology and governance; adoption is a people problem before it is a technical one.

## Honesty notes

- The demo companies are **fictional, illustrative profiles**, built to show the instrument. No real client data is represented.
- This is a diagnostic instrument I designed. It reflects my synthesis of adoption and change-management thinking, not a claim of past corporate AI rollouts.

## Implementation

One HTML file. No backend, no build step, no dependencies, no tracking. The rubric is deterministic: every score maps to a written reading and a next move. Visitor state persists in localStorage on the device only.

## License

Source-available under the [PolyForm Noncommercial License 1.0.0](LICENSE).
Free for noncommercial use.

For commercial licensing, contact
[rose.laguana@gmail.com](mailto:rose.laguana@gmail.com).

Versions published before 2026-08-09 were released under the MIT License. That
grant stands for those versions.
