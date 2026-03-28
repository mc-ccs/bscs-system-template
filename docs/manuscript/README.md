# System Evidence for Manuscript Support

This folder contains **system-repository evidence** that supports the manuscript in the separate documentation repository.

Use these files to preserve technical material that is easier to maintain close to the implementation, such as architecture snapshots, logic-flow references, and traceability between backlog items and implemented features.

This folder should support the manuscript, not replace it.

## Manual Alignment

The thesis manual expects the manuscript to explain:

* how the artifact was designed
* how the MVP was implemented
* how the system was validated

The files in this folder provide system-side evidence that can be cited in Chapter 3 and Chapter 4.

## Suggested Use

* Update `system-architecture.md` when component boundaries, integrations, or storage design change.
* Update `logic-flow.md` when a core business flow, algorithm, or request pipeline changes.
* Update `implementation-traceability.md` when a feature, story, or release should be mapped back to research objectives or manuscript claims.