# Artifacts

This directory holds the authored schema artifacts of the Operational Context Graph (OCG) data schema.

There are three artifact kinds. Each kind has its own subdirectory.

| Directory | Kind | Purpose |
| --- | --- | --- |
| `schema/` | `schema` | JSON Schema documents for canonical types and source record structures. |
| `context/` | `context` | JSON-LD context documents that map properties to external vocabularies. |
| `source-mapping/` | `source-mapping` | Descriptors and transformation programs that map source records to canonical records. |

## Layout

An artifact lives under `<kind>/<logical-type>/`. The `<logical-type>` is the logical artifact type. It matches
`[a-z0-9]+(?:-[a-z0-9]+)*`.

An author edits one working file per artifact in place. An author does not create or name revisions. The release tooling
mints a revision from the final bytes when it builds a release. Revisions are recorded in release manifests under
`releases/`, not in authored filenames.

## Reference

The structure and formats are defined in the Schema Authoring Environment design document in the OCG documentation
repository. This directory structure is the first iteration and holds no artifacts yet.
