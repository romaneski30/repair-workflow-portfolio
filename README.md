# Repair Workflow Portfolio

I built small tools to spend less time preparing repair tickets and documenting results, and more time getting the work done. This portfolio shows how those tools complement each other—and what I learned when an automation idea did not fit the team's workflow.

## How the work fits together

```text
Prepare the work                  Diagnose and repair
Autoatn: existing diagnosis       Technician judgment and physical work
         → preparation note                    ↕
Badger: badge-in requirements     Fab: readable evidence from both ends
        → grouped worklist

Validate and document
Checker: one-sided optic test → reviewed findings
    OR
Ofab: optic test → subsequent circuit comparison
```

These are complementary tools, not a requirement to run every script on every ticket. Fab can help during troubleshooting and when documenting a handoff. Checker and Ofab provide different testing paths.

## What this repository will contain

- Runnable, offline examples using fictional tickets and optical readings.
- Before-and-after reports showing the useful work and the cases held for missing evidence.
- Tests for validation, preserved notes and confirmed simulated saves.
- Short explanations of the workflow, my contribution and lessons learned.

The portfolio is being assembled. It does **not** contain the operational scripts, production connections or real ticket data.

## Ladder: a lesson learned

I planned to use Ladder to suggest troubleshooting steps for tickets without an existing diagnosis. After repeated trials, I found that the person assigned to a ticket was not always the person doing the work. Tailoring suggestions to that person's preferences was therefore unreliable. I paused the integration: I wanted to save technicians time, not tell them how to troubleshoot.

## My contribution

I identified the workflow problems, shaped the tools' behavior and output, reviewed trials, tested their use, and gathered feedback. AI assisted with implementation and automated testing. The portfolio will distinguish operational experience from fictional demo results.
