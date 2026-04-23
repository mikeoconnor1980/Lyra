# Lyra - Plan Structure

## Hierarchy

Lyra uses a hierarchical tree structure with flexibility built in at every level.

```
Enterprise
├── Portfolio A
│   ├── Programme 1
│   │   ├── Project x
│   │   ├── Project y
│   │   └── Project z
│   │       └── Workstream
│   │           └── Task
│   ├── Programme 2
│   └── Programme 3
├── Portfolio B
└── Portfolio C
    └── Programme C.1
        └── Project C1.1
            └── Workstream C1.1
```

## Principles

- Can have **unlimited numbers** of each horizontal level (e.g. unlimited portfolios, programmes, etc.)
- Flexibility in the structure is desirable and to be explored later (e.g. sub-programmes, sub-projects)
- No limit to the number of tasks or hierarchical depth

## Vertical Structure

| Level | Description |
|-------|-------------|
| Enterprise | Top-level organisational grouping |
| Portfolio | Collection of related programmes |
| Programme | Collection of related projects |
| Project | Individual delivery unit |
| Workstream | Logical grouping of tasks within a project |
| Task | Individual work item |
