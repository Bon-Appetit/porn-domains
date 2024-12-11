# Blacklist

## Purpose

| **Filename** | **Description** |
|---|---|
| `bl-sources.txt` | Contains a list of website links to domains associated with adult websites and may be modified to add new source URLs. However, existing URLs should not be removed without a valid reason, such as excessive spam or the source becoming obsolete. |
| `bl-sources.csv` | It is automatically generated on a regular basis and should not be modified. It provides a "human-friendly" way to review sources, including additional metadata. It is also used to identify outdated sources and exclude them during list updates. |
| `bl-custom.txt` | Custom blacklist of domains not listed in the sources but included in the block list. |
| `/external_format` | Directory of dedicated blacklist files for structuring external data or domains in a specific format for background processes. |

## Description of what the data inside the CSV file mean

| **Header** | **Description** |
|------------|-----------------|
| `last_update_to_file_at` | The timestamp of the last update to the specific file in the repository. |
| `repo_name` | The name of the repository. |
| `repo_owner` | The username or organization name that owns the repository. |
| `repo_branch` | The branch of the repository being referenced (e.g., `main`, `master`). |
| `raw_file_url` | The direct URL to access the raw file content from the repository. |
| `repo_html_url` | The URL to access the repository on GitHub. |
| `repo_is_fork` | A boolean indicating if the repository is a fork of another repository. |
| `parent_html_url` | The URL of the parent repository if the repository is a fork. |
| `repo_created_at` | The timestamp when the repository was initially created. |
| `repo_updated_at` | The timestamp when the repository metadata was last updated on GitHub. |
| `repo_last_commit_at` | The timestamp of the latest commit made to the repository. |
| `repo_is_archived` | A boolean indicating if the repository is archived (read-only). |
| `repo_issues_enabled` | A boolean indicating if issues are enabled for the repository. |
| `stars_count` | The number of stars the repository has received. |
| `forks_count` | The number of times the repository has been forked. |
| `watchers_count` | The number of users watching the repository for updates. |
| `last_check_at` | The timestamp of the last time this data was checked or fetched. |
