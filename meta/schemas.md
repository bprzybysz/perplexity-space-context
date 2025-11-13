# Schema Quick Reference

## Pattern Node Schema

```json
{
  "id": "string (required)",
  "name": "string (required)",
  "description": "string (optional, should be required)",
  "axioms": ["string"],
  "version": "string (required)",
  "relationships": ["string"],
  "constraints": ["string"]
}
```

**Required Fields**: `id`, `name`, `axioms`, `version`

## Edge Schema

```json
{
  "source": "string (required)",
  "target": "string (required)",
  "type": "enum (required)",
  "meta": {}
}
```

**Relationship Types**:
- `DEPENDS_ON` - Dependency relationship
- `COMPOSES` - Composition relationship
- `EXTENDS` - Inheritance/extension
- `VALIDATES` - Validation rule
- `CONFLICTS_WITH` - Conflict declaration

## Validation Rules

1. All patterns must have unique IDs
2. Relationships must reference existing pattern nodes
3. COMPOSES relationships must be acyclic
4. CONFLICTS_WITH must be symmetric
5. Version must follow semantic versioning

## Full Schema Definitions

See: [ce-framework-meta/schemas](https://github.com/bprzybysz/ce-framework-meta/tree/main/schemas)