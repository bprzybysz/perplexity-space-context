# Pattern Implementations

This directory contains serialized pattern implementations following the [meta framework](../meta/framework.md) specifications.

## Structure

```
patterns/
├── agentic/          # Agentic workflow patterns
│   ├── prp-driven-execution.yaml
│   ├── context-retrieval.yaml
│   └── validation-loop.yaml
├── architectural/    # System architecture patterns
│   ├── graph-based-storage.yaml
│   ├── layered-separation.yaml
│   └── migration-strategy.yaml
└── operational/      # Operational patterns
    ├── refinement-cycles.yaml
    ├── version-control.yaml
    └── progress-tracking.yaml
```

## Pattern Format

All patterns follow the [pattern-schema.json](https://github.com/bprzybysz/ce-framework-meta/blob/main/schemas/pattern-schema.json):

```yaml
id: pattern-unique-id
name: Pattern Name
description: Pattern description
version: 1.0.0
axioms:
  - Axiom references
relationships:
  - type: DEPENDS_ON
    target: other-pattern-id
constraints:
  - Constraint specifications
```

## Adding New Patterns

1. Follow meta framework [axioms](https://github.com/bprzybysz/ce-framework-meta/blob/main/patterns/axioms-v1.yaml)
2. Validate against schemas
3. Document relationships
4. Add to appropriate category

## Status

**Current**: Foundation structure  
**Next**: Serialize patterns during Cycle 2