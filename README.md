# Perplexity Space Context Orchestration

## Project Goal
Provide a fast, modular orchestration layer for agentic pattern development, validation, migration, and collaborative context engineering using the ce-framework-meta as the foundation. Enable cyclic refinement, team-driven evolution, and seamless Perplexity Space integration.

## Key Features
- Wiring to meta framework for schemas, axioms, and validation
- Organized patterns workspace by type (agentic, architectural, operational)
- Work tracking by increment (cycles, PRP-based progress)
- Artifacts and progress logs per cycle for auditability
- Quick start and schema/axiom reference
- Dedicated directory structure for modular expansion
- Integration-ready for AI-powered test, validation, and release

## Architecture

This repository is the **orchestration layer** for Context Engineering v2.0, integrating:

- **Meta Framework:** [ce-framework-meta](https://github.com/bprzybysz/ce-framework-meta) — Pattern schemas, ontology, validation
- **Pattern Library:** Implementation patterns and templates
- **Work Execution:** Active cycles, PRPs, and progress tracking

## Recommendations from Cycle 1 Review
- Add meta framework as a submodule for live schema sync
- Automate progress and artifact logging (workflows)
- Expand test coverage during Cycle 2
- Document known limitations and troubleshooting

## Usage
1. Review meta framework, schemas, and axioms ([meta/](meta/), [ce-framework-meta](https://github.com/bprzybysz/ce-framework-meta))
2. Commit new patterns or PRP executions to patterns/ and work/
3. Validate using framework rules, track in cycle structure
4. Collaborate through issues, PRs, and cycle documentation

See [Current Progress](work/cycle-1/progress.md) for real-time updates and [IMPLEMENTATION-REVIEW-CYCLE-1.md](https://github.com/bprzybysz/ce-framework-meta/blob/main/docs/IMPLEMENTATION-REVIEW-CYCLE-1.md) for latest evaluation.

---
**Version:** 1.0.1  
**Last Updated:** 2025-11-13
