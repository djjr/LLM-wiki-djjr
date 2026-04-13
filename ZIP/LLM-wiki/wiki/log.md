# Wiki Log
_Append-only. Newest entries at top. Format: `## [YYYY-MM-DD] operation | title`_

To see recent activity:
```bash
grep "^## \[" wiki/log.md | head -10
```

---

## [2026-04-10] init | Wiki initialized
- Schema written to CLAUDE.md
- Directory structure created: raw/, wiki/concepts/, wiki/entities/,
  wiki/sources/, wiki/queries/, wiki/overviews/
- Starter files created: index.md, log.md, overview.md
- Next step: drop a source file into raw/ and say "ingest [filename]"

## [2026-04-10] schema-update | Page taxonomy revised, project context added
- Renamed wiki/concepts/ → wiki/definitions/ (hover-link targets)
- Added wiki/findings/ (first-class claim pages)
- CLAUDE.md: added PROJECT CONTEXT section (customizable per project)
- CLAUDE.md: replaced generic page types with: definition, explanation,
  finding, source, query
- CLAUDE.md: added WIKI RUN as first-class operation (autonomous, multi-step)
- CLAUDE.md: added audience calibration (post-PhD, active researcher)
- CLAUDE.md: added two-domain framing (LLM ↔ sociology/philosophy) and
  domain tags
- overview.md: rewritten with project-specific framing and open questions
- index.md: updated table structure to match new page types
