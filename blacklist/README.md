# Blacklist

## Purpose

| **Filename** | **Description** |
|---|---|
| `bl-sources.txt` | Contains a list of website links to domains associated with adult websites and may be modified to add new source URLs. However, existing URLs should not be removed without a valid reason, such as excessive spam or the source becoming obsolete. |
| `bl-sources.csv` | It is automatically generated on a regular basis and should not be modified. It provides a "human-friendly" way to review sources, including additional metadata. It is also used to identify outdated sources and exclude them during list updates. |
| `bl-custom.txt` | Custom blacklist of domains not listed in the sources but included in the block list. |
| `/external_format` | Directory of dedicated blacklist files for structuring external data or domains in a specific format for background processes. |