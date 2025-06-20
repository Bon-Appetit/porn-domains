# 📝 Changelog

This changelog documents changes to the structure, file handling, and background processes related to the domain list. Changes to the lists themselves, such as added or removed domains, are not included here as they can be reviewed directly from the [commit history](https://github.com/search?q=repo%3ABon-Appetit%2Fporn-domains+%22%5BAUTO%5D+Update+list%22&type=commits&s=committer-date&o=desc).

**Format Of Date Is: YYYY-MM-DD**

## 2025-06-20

- The filenames for the allowlist and blocklist have been changed to `allow.{FILE_HASH}.{RANDOM_HASH}.txt` and `block.{FILE_HASH}.{RANDOM_HASH}.txt`.
  - `{FILE_HASH}` contains the first 10 characters of the SHA1 checksum of the file’s content.
  - `{RANDOM_HASH}` is a 6-character random alphanumeric string (`a–z`, `0–9`).
  - `{FILE_HASH}` can be used to detect content changes, while `{RANDOM_HASH}` ensures the filename always gets renamed.

## 2025-06-18

- Automatic updates of the domain lists have resumed.

## 2025-06-17

- The default branch has been renamed from `master` to `main`.
- The file `pass.txt` has been renamed to `allow.txt`.
- The files `block.txt` and `allow.txt` will no longer retain static names. On each update, they will be renamed to a format like `block-HASH.txt` or `allow-HASH.txt`, where `HASH` is a checksum of the file content. This change is intended to prevent direct use of raw URLs. Learn more here: 🔗 [Upcoming changes to prevent direct use of raw URLs](https://github.com/Bon-Appetit/porn-domains/discussions/75)
- A new file named `meta.json` has been introduced. It will be updated to reflect the current filenames for both the blocklist and allowlist.

## 2025-06-13

- Starting **June 14, 2025**, the CSV rebuild process will resume to ensure we continue collecting updated stats from the sources used to generate the blocklist. However, **auto-updating of the blocklist itself will remain paused** until a reliable and sustainable solution is in place to handle the recent surge in traffic.

## 2025-06-12

- To help reduce ongoing excessive traffic, the original `block.txt` file has been **removed**. A temporary replacement named `please-slow-down.txt` has been created, containing the most recent entries from the blocklist.
  - This is intended to break automated processes relying on the old file path, triggering 404 errors and encouraging proper handling like caching or adjusted fetch logic.
  - Until a long-term fix is in place, **auto-updates will stay disabled** as a precaution to avoid file conflicts and further action from GitHub, who have contacted me about the unusually high bandwidth usage.

## 2025-05-15

- The DNS checks have looked good for the past two months and still do. We're now writing the output directly to the main blocklist, `block.txt`. As mentioned earlier, the temporary file `block.txt.dns_ok` and its references have been removed.

## 2025-03-15

- DNS checks are now enforced again. They are performed directly after combining the domains across all sources. We will monitor the results to ensure everything works as expected. If you encounter any issues, please send an email to mail@codealdente.ovh.
- DNS checks will exclude whitelist sources. Until we can ensure the results are accurate, a new file named `block.txt.dns_ok` will be placed next to `block.txt`. The `block.txt.dns_ok` file will contain DNS-validated domains, while `block.txt` will include all combined and deduplicated domains from all blacklist sources. **Please note that `block.txt.dns_ok` is TEMPORARY and WILL BE REMOVED once we confirm the results are consistently correct.**

## 2025-03-03

- New whitelist source added to exclude more than 10,000 university domains ([fe30ee9](https://github.com/Bon-Appetit/porn-domains/commit/fe30ee9f677fdfa8f60b3ef3efd0499de9c29b44))

## 2025-03-01

Sources for blacklisting will be considered outdated if they have not been updated within three years. The condition for the archived state will be ignored from now on. [Read more here](https://github.com/Bon-Appetit/porn-domains/discussions/43#discussioncomment-12317915)

## 2025-02-03

- New whitelist source added to exclude common news sites ([9f4f9e4](https://github.com/Bon-Appetit/porn-domains/commit/9f4f9e44574dfd7e90cc8d97bba42cec8d3a315b))

## 2024-12-20

- 24 new blacklist sources added ([08e538a](https://github.com/Bon-Appetit/porn-domains/commit/08e538a211a326062ccdc789bbcac016f3003e38))
- Blacklist source "blocklistproject" updated ([ec41ce9](https://github.com/Bon-Appetit/porn-domains/commit/ec41ce9d25ccf8c1a4bb6d609237e591713308d2))

## 2024-11-21

- **"Outdated" sources are now excluded**: For more details, please [read this](https://github.com/Bon-Appetit/porn-domains/discussions/43#discussioncomment-11306946).
