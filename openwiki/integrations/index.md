# Files

- [GitHub Actions and CI Automation](github-actions.md) - Explains the repository's read-only validation gates, bounded write-capable preview and publication handoffs, and scheduled review-PR automation. It also covers documentation version-claim checks and the credential boundary for untrusted pull requests.
- [Mintlify Integration](mintlify.md) - Mintlify renders the repository's generated documentation tree and creates selected deployment-time artifacts for docs.langchain.com. This page explains its configuration, generated-output boundary, local validation, OpenAPI behavior, previews, exports, and hosted checks.
- [NPM Snippet Components](npm-snippets.md) - How local JSX and TSX snippet components and allowlisted @langchain/docs-sandbox artifacts reach the built documentation site. Explains their distinct build, language-routing, and refresh behavior relative to MDX and generated code-sample snippets.
- [Reference Documentation Boundaries](reference-docs.md) - Distinguishes externally generated SDK reference documentation from Mintlify OpenAPI endpoint documentation, and explains ownership, refresh, validation, and issue-routing responsibilities.
