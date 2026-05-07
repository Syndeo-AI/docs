# Resyndeo docs

[Mintlify](https://mintlify.com) documentation site. Pages are MDX with YAML frontmatter; config in `docs.json`.

```bash
npm i -g mint
mint dev            # local preview at http://localhost:3000
mint broken-links   # link check
```

Changes deploy to production automatically on push to `main` (Mintlify GitHub app).

Design specs and execution plans live under `superpowers/`.
