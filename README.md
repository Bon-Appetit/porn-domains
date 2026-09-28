<div align="center">

[![Logo](https://bon-appetit.github.io/assets/images/ba-pd-logo.png)](https://github.com/Bon-Appetit/porn-domains)

[![Contributors](https://img.shields.io/github/contributors/Bon-Appetit/porn-domains?label=%F0%9F%91%A5%20Contributors&style=flat&labelColor=white&color=FA2549)](https://github.com/Bon-Appetit/porn-domains/blob/main/docs/CONTRIBUTORS.md) [![Sponsors](https://img.shields.io/badge/%F0%9F%92%8E-Sponsors-null?style=flat&labelColor=white&color=614986)](https://github.com/Bon-Appetit/porn-domains/blob/main/docs/SPONSORS.md)

[![Watchers](https://img.shields.io/github/watchers/Bon-Appetit/porn-domains?label=Watchers&style=flat-square&logo=github&cacheSeconds=43200)](https://github.com/Bon-Appetit/porn-domains/watchers) [![Forks](https://img.shields.io/github/forks/Bon-Appetit/porn-domains?label=Forks&style=flat-square&logo=github&cacheSeconds=43200)](https://github.com/Bon-Appetit/porn-domains/forks) [![Stars](https://img.shields.io/github/stars/Bon-Appetit/porn-domains?label=Stars&style=flat-square&logo=github&cacheSeconds=43200)](https://github.com/Bon-Appetit/porn-domains/stargazers) [![Commits](https://img.shields.io/github/commit-activity/m/Bon-Appetit/porn-domains?label=Commits&style=flat-square&logo=github&cacheSeconds=43200)](https://github.com/Bon-Appetit/porn-domains/commits/main/) [![License](https://img.shields.io/github/license/Bon-Appetit/porn-domains?label=License&style=flat-square&color=2481C0&cacheSeconds=43200)](https://github.com/Bon-Appetit/porn-domains/blob/main/LICENSE)

</div>

# Adult-content domain list

Bon-Appetit/porn-domains is a community-maintained domain list for DNS-based filtering of pornographic and explicit sexual content. It combines external sources with reviewed custom entries; it is not exhaustive and may contain errors.

DNS filtering works at the domain level, not at the page or URL level. Blocking a shared domain can affect unrelated content on that domain, and this list cannot prevent access through other DNS resolvers or services. Review the [policy](docs/POLICY.md) before using it.

## Support the project

[![Donate with Buy me a Coffee](https://bon-appetit.github.io/assets/images/bmc-orange-button@200x56.png)](https://buymeacoffee.com/CodeAlDente)

Contributions, feedback, and optional donations help maintain the list and its sources.

> [!IMPORTANT]
> **Using the list commercially?** Maintaining and reviewing a regularly updated dataset takes ongoing work. Commercial users are welcome to contribute improvements or support the project financially. [Click here to donate.](https://buymeacoffee.com/CodeAlDente)

## Live search

> [!TIP]
> This list is too large to view directly on GitHub. Use the search interface: <br> https://bon-appetit.github.io/domain-search/

## Files

| File | Description |
|---|---|
| `block.{FILE_HASH}.{RANDOM_HASH}.txt` | Generated blocklist, combined from sources and custom entries. <br><br> ![Blocklist Lines (Domains) in file](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=blocklist.lines_format&style=flat-square&label=Domains&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) ![Blocklist Last Update](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=blocklist.updated_format&style=flat-square&label=Last%20update&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) ![Blocklist Size of file](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=blocklist.size_format&style=flat-square&label=Filesize&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) |
| `allow.{FILE_HASH}.{RANDOM_HASH}.txt` | Generated allowlist for domains excluded from the blocklist. <br><br> ![Allowlist Lines (Domains) in file](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=allowlist.lines_format&style=flat-square&label=Domains&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) ![Allowlist Last Update](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=allowlist.updated_format&style=flat-square&label=Last%20update&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) ![Allowlist Size of file](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBon-Appetit%2Fporn-domains%2Frefs%2Fheads%2Fmain%2Fmeta.json&query=allowlist.size_format&style=flat-square&label=Filesize&labelColor=%23555555&color=%23007EC6&cacheSeconds=43200) |
| `meta.json` | Current filenames, raw URLs, update times, line counts, and file sizes. Use it to find the current list files; generated filenames can change. |

The generated filenames are intentionally changeable. Always read `meta.json` to resolve the current filenames instead of hardcoding a list URL. [For more information, please read this.](docs/CHANGELOG.md#2025-06-20)

## Resources

| Page | Description |
| [Policy](docs/POLICY.md) | What qualifies for inclusion or removal, including AI-generated content |
| [Contributing](docs/CONTRIBUTING.md) | Report a domain or propose a change |
| [Changelog](docs/CHANGELOG.md) | Changes to list structure and automation |
| [FAQ](docs/FAQ.md) | Common questions |
| [Support](docs/SUPPORT.md) | Help, issue reports, and contact |
| [Contributors](docs/CONTRIBUTORS.md) / [Sponsors](docs/SPONSORS.md) | Community and project support |

## License

[![CC BY-SA 4.0](https://bon-appetit.github.io/assets/images/cc-by-sa-pictogram.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This project is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). If you use or share this list, please credit it as:

```markdown
[Bon-Appetit/porn-domains](https://github.com/Bon-Appetit/porn-domains) is licensed under [CC BY-SA 4.0](https://github.com/Bon-Appetit/porn-domains/blob/main/LICENSE).
```

## Disclaimer

**No guarantee.** The list may be incomplete, out of date, or contain false positives. Review it before deployment and test it in your environment.

**Local laws and policies vary.** This project uses the criteria in its [policy](docs/POLICY.md); your organization is responsible for deciding whether and how to use the list.

**Use at your own risk.** DNS blocking can disrupt access to legitimate content on a shared domain. The maintainers are not responsible for decisions made using this list.
