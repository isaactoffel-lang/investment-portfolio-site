# Toffel Capital case study

[Project overview](README.md) · [Sample memo](INVESTMENT_MEMO.md)

## Why record the decision separately?

A research note can evolve as the company reports new information. If it also serves as the only record of a decision, a later edit can make the original choice look better informed than it was. I built and maintained Toffel Capital as a personal research project, with company research and a separate decision log alongside the portfolio views.

The decision record preserves the action and rationale as they stood at the time. The research can develop independently, and a later review can compare what changed with what was originally expected.

## Keep comparisons tied to their inputs

The application uses Next.js and TypeScript. Processing scripts prepare the inputs used by the portfolio and benchmark views. That separation gives a reviewer a way to trace an inconsistent chart back to the selection, the calculation, or the presentation.

| Failure to look for | Review question |
| --- | --- |
| The benchmark starts on a different observation | Do both series share the comparison window and a consistent starting point? |
| The selected period changes but a summary retains its previous label | Do the label and displayed calculations derive from the same selection? |
| A revised thesis obscures the reasoning for a prior action | Does the decision entry still preserve the reason and evidence available at the time? |

The comparison questions are review criteria. The [sample memo](INVESTMENT_MEMO.md) demonstrates how the decision record can be used. It was prepared with AI assistance for this publication. The public evidence covers the research structure and fictional walkthrough. [Publication scope](PUBLICATION.md)
