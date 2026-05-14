# Recoveredd

Small TypeScript utilities for practical developer workflows.

I maintain 20 published packages for JSON rendering, table conversion, path inspection, file path validation, CSV exports, SVG parsing, front matter, data URLs, text matching, migration helpers, interactive hex grids, and other small pieces of developer tooling. A few additional packages are staged as GitHub previews before npm publication, including support-oriented tools for logs, reports and HAR cleanup.

The goal is simple: tiny APIs, predictable behavior, browser-friendly builds, and useful diagnostics instead of black-box helpers.

## Links

- Portfolio and interactive demos: [packages.wasta-wocket.fr](https://packages.wasta-wocket.fr/)
- npm packages: [npmjs.com/~recovered](https://www.npmjs.com/~recovered)
- Support maintenance: [Ko-fi](https://ko-fi.com/recovered)

## Published packages

| Package | What it does | Demo |
| --- | --- | --- |
| [`json-html-kit`](https://github.com/Recoveredd/json-html-kit) | Render JSON as safe, themed HTML with pagination support. | [Demo](https://packages.wasta-wocket.fr/json-html-kit/) |
| [`array-table-kit`](https://github.com/Recoveredd/array-table-kit) | Convert arrays of objects to Markdown or HTML tables. | [Demo](https://packages.wasta-wocket.fr/array-table-kit/) |
| [`json-csv-kit`](https://github.com/Recoveredd/json-csv-kit) | Export JSON records to CSV with safe escaping. | [Demo](https://packages.wasta-wocket.fr/json-csv-kit/) |
| [`object-path-kit`](https://github.com/Recoveredd/object-path-kit) | Parse, normalize, read and update object paths. | [Demo](https://packages.wasta-wocket.fr/object-path-kit/) |
| [`object-key-paths`](https://github.com/Recoveredd/object-key-paths) | List nested key paths from objects and arrays. | [Demo](https://packages.wasta-wocket.fr/object-key-paths/) |
| [`terminal-table-kit`](https://github.com/Recoveredd/terminal-table-kit) | Parse fixed-width terminal table output into rows. | [Demo](https://packages.wasta-wocket.fr/terminal-table-kit/) |
| [`text-similarity-kit`](https://github.com/Recoveredd/text-similarity-kit) | Compare and rank short strings with fuzzy matching helpers. | [Demo](https://packages.wasta-wocket.fr/text-similarity-kit/) |
| [`svg-ast-kit`](https://github.com/Recoveredd/svg-ast-kit) | Parse SVG markup into a typed JSON AST. | [Demo](https://packages.wasta-wocket.fr/svg-ast-kit/) |
| [`frontmatter-kit`](https://github.com/Recoveredd/frontmatter-kit) | Parse front matter with ranges and diagnostics. | [Demo](https://packages.wasta-wocket.fr/frontmatter-kit/) |
| [`data-url-kit`](https://github.com/Recoveredd/data-url-kit) | Parse and inspect data URLs with metadata and diagnostics. | [Demo](https://packages.wasta-wocket.fr/data-url-kit/) |
| [`hex-color-token-kit`](https://github.com/Recoveredd/hex-color-token-kit) | Extract and validate CSS hex color tokens. | [Demo](https://packages.wasta-wocket.fr/hex-color-token-kit/) |
| [`human-duration-parse-kit`](https://github.com/Recoveredd/human-duration-parse-kit) | Parse human duration strings into structured units. | [Demo](https://packages.wasta-wocket.fr/human-duration-parse-kit/) |
| [`import-specifier-scan-kit`](https://github.com/Recoveredd/import-specifier-scan-kit) | Scan JavaScript source for import and require specifiers. | [Demo](https://packages.wasta-wocket.fr/import-specifier-scan-kit/) |
| [`localized-price-parse-kit`](https://github.com/Recoveredd/localized-price-parse-kit) | Parse localized price strings into decimal values and currency hints. | [Demo](https://packages.wasta-wocket.fr/localized-price-parse-kit/) |
| [`css-font-shorthand-kit`](https://github.com/Recoveredd/css-font-shorthand-kit) | Parse and format CSS font shorthand values. | [Demo](https://packages.wasta-wocket.fr/css-font-shorthand-kit/) |
| [`jmx-k6-migration-kit`](https://github.com/Recoveredd/jmx-k6-migration-kit) | Audit JMeter JMX files and generate k6 migration scaffolds. | [Demo](https://packages.wasta-wocket.fr/jmx-k6-migration-kit/) |
| [`proto-form-kit`](https://github.com/Recoveredd/proto-form-kit) | Turn Protocol Buffer schemas into form-friendly metadata. | [Demo](https://packages.wasta-wocket.fr/proto-form-kit/) |
| [`number-range-list-kit`](https://github.com/Recoveredd/number-range-list-kit) | Parse integer range lists with diagnostics and bounded expansion. | [Demo](https://packages.wasta-wocket.fr/number-range-list-kit/) |
| [`hex-grid-kit`](https://github.com/Recoveredd/hex-grid-kit) | Build interactive SVG hex grids with cube coordinates and hit testing. | [Demo](https://packages.wasta-wocket.fr/hex-grid-kit/) |
| [`filepath-validator-kit`](https://github.com/Recoveredd/filepath-validator-kit) | Validate file paths with portable, POSIX and Windows diagnostics. | [Demo](https://packages.wasta-wocket.fr/filepath-validator-kit/) |

## GitHub previews

These packages are ready on GitHub while npm publication is pending. Some have interactive portfolio previews when a browser demo is useful.

| Package | What it does | Link |
| --- | --- | --- |
| [`numeric-unit-parse-kit`](https://github.com/Recoveredd/numeric-unit-parse-kit) | Parse numeric values with units into structured amounts, normalized strings and diagnostics. | [Preview](https://packages.wasta-wocket.fr/numeric-unit-parse-kit/) |
| [`file-extension-inspect-kit`](https://github.com/Recoveredd/file-extension-inspect-kit) | Inspect filename extensions with dotfile, extensionless and compound-extension policies. | [Preview](https://packages.wasta-wocket.fr/file-extension-inspect-kit/) |
| [`large-log-viewer-kit`](https://github.com/Recoveredd/large-log-viewer-kit) | Inspect and render large browser logs with virtual windows, chunked search and safe ANSI-aware HTML helpers. | [Preview](https://packages.wasta-wocket.fr/large-log-viewer-kit/) |
| [`junit-report-doctor-kit`](https://github.com/Recoveredd/junit-report-doctor-kit) | Normalize JUnit XML reports with stable CI diagnostics and a small CLI. | [Preview](https://packages.wasta-wocket.fr/junit-report-doctor-kit/) |
| [`har-redaction-kit`](https://github.com/Recoveredd/har-redaction-kit) | Redact sensitive fields from HAR files with deterministic reports for support handoffs. | [Preview](https://packages.wasta-wocket.fr/har-redaction-kit/) |

## Principles

- TypeScript-first public APIs.
- Browser-friendly core where the package domain allows it.
- No runtime dependencies unless they clearly earn their place.
- Structured results and diagnostic codes instead of ambiguous booleans.
- Small packages that are easy to inspect, test and replace.
