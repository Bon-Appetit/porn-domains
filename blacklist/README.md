# Blacklist

## Purpose

| **Filename** | **Description** |
|---|---|
| `bl-sources.txt` | Contains a list of website links to domains associated with adult websites. |
| `bl-sources.csv` | User-friendly reference for `bl-sources.txt`, detailing each repository with the timestamp of the last update. Ordered by recent activity. |
| `bl-custom.txt` | Custom blacklist of domains not listed in the sources but included in the block list. |
| `/external_format` | Directory of dedicated blacklist files for structuring external data or domains in a specific format for background processes. |

The **CSV file** is automatically generated on a regular basis and should not be modified. It provides a "human-friendly" way to review sources, including additional metadata. It is also used to identify outdated sources and exclude them during list updates.

The **text file**, on the other hand, may be modified to add new source URLs. However, existing URLs should not be removed without a valid reason, such as excessive spam or the source becoming obsolete.