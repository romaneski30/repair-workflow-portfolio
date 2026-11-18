# Repair Workflow Portfolio

I worked on small tools to reduce repetitive repair preparation and make test results easier to understand and document. The goal was to help technicians get to the work, not tell them how to troubleshoot.

This documentation-only portfolio uses real screenshots from my work, with switch names, ticket numbers, people, locations and other identifying details covered, alongside clearly labeled illustrations. It contains no operational source code, internal system links, credentials or installation commands.

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
- [Multi-circuit evidence collection](docs/multi-circuit-evidence.md): check every circuit a ticket lists in one pass, see both ends, and leave one readable record.
- [Test evidence recorder](docs/test-evidence-recorder.md): make component-test findings easier to document.
- [Two-stage validation](docs/two-stage-validation.md): an earlier example joining a local test and a later circuit check.
- [Troubleshooting planner: lessons learned](docs/planner-lessons.md): why a planned integration was paused.

## My contribution

I identified workflow problems, shaped tool behavior and output, tried changes during real use, and gathered feedback. AI assisted with implementation and testing. Each page labels which images are real redacted screenshots and which are illustrations; neither proves productivity gains or diagnostic accuracy.

## Current scope

This is a project-description draft, not a runnable toolkit. It uses general descriptions instead of internal system names. Exact workloads, time estimates and supporting work records are kept out of this version while I check what I can share.
