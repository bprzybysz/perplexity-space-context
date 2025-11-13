# Perplexity Space Context

**Context Engineering workspace for agentic pattern development**

## Architecture

This repository serves as the **orchestration layer** for Context Engineering v2.0, integrating:

- **Meta Framework**: [ce-framework-meta](https://github.com/bprzybysz/ce-framework-meta) - Pattern schemas, ontology, validation
- **Pattern Library**: Implementation patterns and templates
- **Work Execution**: Active cycles, PRPs, and progress tracking

## Repository Structure

```
perplexity-space-context/
├── meta/                    # Framework references
│   ├── framework.md         # Link to ce-framework-meta
│   └── schemas.md           # Quick schema reference
├── patterns/                # Pattern implementations
│   ├── agentic/            # Agentic workflow patterns
│   ├── architectural/      # System architecture patterns
│   └── operational/        # Operational patterns
└── work/                    # Active execution
    ├── cycle-1/            # Axiom Hardening (IN PROGRESS)
    ├── cycle-2/            # Pattern Serialization (PLANNED)
    ├── cycle-3/            # Complete Migration (PLANNED)
    └── README.md           # Work tracking guide
```

## Quick Start

### Current Work: Cycle 1 - Axiom Hardening

**Status:** Task 1 Complete ✅  
**Next:** Update axioms and schemas

See: [work/cycle-1/README.md](work/cycle-1/README.md)

### Using the Framework

1. **Review Meta Framework**
   - Schemas: [ce-framework-meta/schemas](https://github.com/bprzybysz/ce-framework-meta/tree/main/schemas)
   - Axioms: [ce-framework-meta/patterns/axioms-v1.yaml](https://github.com/bprzybysz/ce-framework-meta/blob/main/patterns/axioms-v1.yaml)

2. **Execute PRPs**
   - Current: [PRP-1: Axiom Hardening](https://github.com/bprzybysz/ce-framework-meta/blob/main/prps/PRP-1-axiom-hardening.md)
   - Next: [PRP-2: Pattern Serialization](https://github.com/bprzybysz/ce-framework-meta/blob/main/prps/PRP-2-pattern-serialization.md)

3. **Track Progress**
   - See [work/cycle-1/progress.md](work/cycle-1/progress.md)

## Principles

- **KISS**: Keep patterns simple and essential
- **SOLID**: Well-structured, composable patterns
- **YAGNI**: Build only what's needed

## Integration with Perplexity Space

This repository aligns with **Context Engineering v2.0** Space:

**Space Instructions:**
```
Context preprocessing agent.
SOURCE: GitHub perplexity-space-context repo (meta/, patterns/, work/)
PRINCIPLES: KISS, SOLID, YAGNI
PROCESS: Review repo state → Apply validation → Generate next steps
OUTPUT: Markdown with actionable tasks
VALIDATE: ≤3 sentences, requirements mapped, testable
```

## Links

- [Meta Framework Repository](https://github.com/bprzybysz/ce-framework-meta)
- [Current Cycle Progress](work/cycle-1/README.md)
- [Pattern Catalog](https://github.com/bprzybysz/ce-framework-meta/blob/main/patterns/catalog-draft.md)

---

**Version:** 0.1.0  
**Last Updated:** 2025-11-13