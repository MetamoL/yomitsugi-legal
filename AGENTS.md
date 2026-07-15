# AGENTS.md — Yomitsugi public/legal site

This repository is the public Yomitsugi website, legal pages, support page and
SEO articles. It supports both Claude Code and Codex.

## Sources and boundaries

- Product behavior and policy facts come from the sibling `yomitsugi`
  repository, especially `REQUIREMENTS.md`, `BACKLOG.md`, relevant design docs
  and the actual implementation. Do not invent or infer legal claims.
- Keep the privacy policy consistent with shipped analytics, notifications,
  storage, deletion and third-party services.
- Store-registered URLs and existing legal/support paths are stable API-like
  contracts. Do not rename or remove them.
- Preserve the statement that Yomitsugi is unofficial, free and ad-free while
  monetization is disabled.

## Editing and verification

- Preserve YAML front matter and Jekyll/Liquid syntax.
- For articles, use polite Japanese and support factual claims with primary
  sources. Do not mass-produce low-value AI articles.
- Check internal links and rendered structure for affected pages. Use a local
  Jekyll build when the required runtime is available; otherwise report the
  limitation and perform static checks.
- Stage named paths only. A push can update the public site, so obtain explicit
  owner approval before pushing.
