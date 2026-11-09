# Two-stage validation

[Back to portfolio](../README.md)

## Why it is included

This is an earlier example of combining two related checks. I have not used it recently, and it is not a required stage of the current workflow.

## How the stages fit

```text
Local component test
    Missing or failing evidence → stop and review
    Valid pass → a separate circuit comparison after reconnection
```

The first stage checks the selected component under the appropriate local test setup. The later stage examines the circuit after it has been restored. Those stages answer different questions; passing a component test is not proof that the full circuit is repaired.

The operator controls physical work between the stages. The diagram is an explanatory illustration, not a record of an actual test or a claim of automatic reconnection.

## My contribution

I worked on bringing related steps into a more convenient workflow, with AI assistance in implementation and testing. A separate one-sided reporting path is useful when the later circuit comparison is not needed.

Exact commands, component thresholds and internal integrations are omitted from this review copy.
