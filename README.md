# Graph Focus

Graph Focus is a planned DeLeon Labs plugin for narrowing a connected body of
material to the relationships that matter for the current task.

## Status

Foundation. The product charter is defined; implementation has not started.

## Product boundary

Graph Focus owns focused graph views, filters, paths, relationship emphasis, and
explanations of why nodes and edges are visible. It does not become the canonical
store for every plugin's data or silently mutate source relationships.

## Ecosystem relationship

Graph Focus consumes authorized graph context and returns user-selected nodes,
paths, and relationships to Lighthouse. The canonical charter and shared
contracts live in the [DeLeon Labs Manual](https://github.com/DeLeon-Labs/lab-manual).

## Next milestone

Define the minimum portable node-and-edge representation and prototype a focused
neighborhood handoff without importing an entire graph model.
