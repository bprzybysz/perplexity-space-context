# Meta Framework Reference

**Framework Repository**: [ce-framework-meta](https://github.com/bprzybysz/ce-framework-meta)

## Quick Links

### Core Components

- **Schemas**: [/schemas](https://github.com/bprzybysz/ce-framework-meta/tree/main/schemas)
  - [pattern-schema.json](https://github.com/bprzybysz/ce-framework-meta/blob/main/schemas/pattern-schema.json) - Pattern node structure
  - [edge-schema.json](https://github.com/bprzybysz/ce-framework-meta/blob/main/schemas/edge-schema.json) - Relationship edges

- **Axioms**: [/patterns/axioms-v1.yaml](https://github.com/bprzybysz/ce-framework-meta/blob/main/patterns/axioms-v1.yaml)
  - Pattern design principles
  - Serialization rules
  - Validation requirements

- **Ontology**: [/ontology](https://github.com/bprzybysz/ce-framework-meta/tree/main/ontology)
  - Pattern taxonomy
  - Relationship types
  - Validation rules

### Documentation

- **Quick Start**: [QUICKSTART.md](https://github.com/bprzybysz/ce-framework-meta/blob/main/QUICKSTART.md)
- **Execution Guide**: [docs/claude-code-execution-guide.md](https://github.com/bprzybysz/ce-framework-meta/blob/main/docs/claude-code-execution-guide.md)
- **Usage Examples**: [docs/framework-usage-examples.md](https://github.com/bprzybysz/ce-framework-meta/blob/main/docs/framework-usage-examples.md)

### PRPs (Product Requirements Prompts)

- **PRP-1**: [Axiom Hardening](https://github.com/bprzybysz/ce-framework-meta/blob/main/prps/PRP-1-axiom-hardening.md) - Cycle 1
- **PRP-2**: [Pattern Serialization](https://github.com/bprzybysz/ce-framework-meta/blob/main/prps/PRP-2-pattern-serialization.md) - Cycle 2

## Current Version

**Meta Framework**: v0.1.0  
**Status**: Foundation complete, Cycle 1 in progress

## Integration

This workspace uses the meta framework as the authoritative source for:
- Pattern structure definitions
- Validation rules
- Serialization schemas
- Migration strategies

All work in `/work` should conform to meta framework specifications.