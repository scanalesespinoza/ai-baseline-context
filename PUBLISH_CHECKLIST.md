# Publish Hygiene Checklist

- Secrets scrubbed: scan for keys/tokens/env vars; ensure `.env` or credentials are excluded.
- Links valid: external URLs reachable; internal paths updated if knowledge base moved.
- CRLF/encoding: normalize line endings (LF) and keep ASCII unless domain docs require otherwise.
- Versioning: update `CHANGELOG.md` and tag if applicable.
- Templates respected: new files follow `templates/` structure; folder READMEs list them.
- Knowledge separation: remove project-specific data if publishing a generic baseline; keep only what is intended to be shared.
