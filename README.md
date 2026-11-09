# Repair Workflow Portfolio

I worked on small tools to reduce repetitive repair preparation and make test results easier to understand and document. The goal was to help technicians get to the work, not tell them how to troubleshoot.

This documentation-only draft uses generic project labels and made-up examples. It contains no operational source code, real records, internal system links or installation commands. The fuller project descriptions are being reviewed before publication.

## How the tools fit together

```text
Prepare the work          Troubleshoot and repair       Validate and document
Record an existing plan   Technician judgment           Test the selected component
Group related tasks       Readable circuit evidence     Review and record findings
```

The tools support different parts of the work. They are not one automatic pipeline, and not every repair uses every tool.

## Project pages

- [Note preparation](docs/note-preparation.md): turn existing repair instructions into useful preparation notes.
- [Batch work organizer](docs/batch-work-organizer.md): group tasks with the same prerequisite while preserving ownership.
- [Circuit evidence viewer](docs/circuit-evidence-viewer.md): show both ends of a circuit in a readable comparison.
- [Test evidence recorder](docs/test-evidence-recorder.md): make component-test findings easier to document.
- [Two-stage validation](docs/two-stage-validation.md): an earlier example joining a local test and a later circuit check.
- [Troubleshooting planner: lessons learned](docs/planner-lessons.md): why a planned integration was paused.

## My contribution

I identified workflow problems, shaped tool behavior and output, tried changes during real use, and gathered feedback. AI assisted with implementation and testing. These pages distinguish my experience from made-up illustrations; the illustrations do not prove productivity gains or diagnostic accuracy.

## Current scope

This is a project-description draft, not a runnable toolkit. It uses general descriptions instead of internal tool names and commands. Exact workloads, time estimates and supporting work records are kept out of this version while I check what I can share.
