# Whitelist

## Purpose

| **Filename** | **Description** |
|---|---|
| `wl-sources.txt` | Contains a list of website links to domains to be kept off the block list to avoid mistakenly blocking legitimate websites. |
| `wl-sources.csv` | User-friendly reference for `wl-sources.txt`, detailing each repository with the timestamp of the last update. Ordered by recent activity. |
| `wl-custom.txt` | Custom whitelist of domains to be excluded from the block list. |
| `/external_format` | Directory of specialized whitelist files for organizing external data or domains into a specific structure for background processes. |

The **CSV file** is automatically generated on a regular basis and should not be modified. It provides a "human-friendly" way to review sources, including additional metadata.

The **text file**, on the other hand, may be modified to add new source URLs. However, existing URLs should not be removed without a valid reason, such as excessive spam or the source becoming obsolete.