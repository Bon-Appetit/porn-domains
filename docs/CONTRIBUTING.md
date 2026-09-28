# Contributing

Thanks for taking the time to contribute! Whether you're reporting a missing domain, correcting an entry, or suggesting an improvement, your help is appreciated!

## How to contribute

> [!NOTE]
> If you don't have a GitHub account or prefer to report a domain privately, email [mail@codealdente.ovh](mailto:mail@codealdente.ovh). You can also use email to ask questions about the project.

### Add or remove a domain

You can request a change by opening an issue, or make the change yourself in a pull request. Please review the [policy](POLICY.md) before submitting a domain.

#### Option 1: Report a domain via issue

Open a [new issue](https://github.com/Bon-Appetit/porn-domains/issues) and include:

- The domain name(s) and whether you want them added or removed (for example, `example.com`).
- The reason for the request, such as adult content or a false positive.
- Supporting evidence, such as relevant URLs or references. Do not attach explicit images or videos; see the [policy](POLICY.md).

#### Option 2: Submit a domain via pull request

To make the change yourself, submit a pull request:

1. Fork the repository and clone it to your computer.
2. Add the domain to the appropriate file:
   - To block it, add it to `blacklist/bl-custom.txt`.
   - To keep it off the blocklist, add it to `whitelist/wl-custom.txt`.
3. Submit a pull request explaining the change.

### Add or remove a source

Sources are URLs to files containing multiple domains. You can request a source change in an issue or make it directly in a pull request.

#### Option 1: Report a source via issue

Open a [new issue](https://github.com/Bon-Appetit/porn-domains/issues) and include:

- The source URL and whether you want it added or removed.
- The reason for the request, such as outdated data or false positives.
- Examples or other evidence that help us review the source.

#### Option 2: Submit a source via pull request

To make the change yourself, submit a pull request:

1. Fork the repository and clone it to your computer.
2. Add or remove the source URL in the appropriate file:
   - `blacklist/bl-sources.txt` for sources whose domains should be blocked.
   - `whitelist/wl-sources.txt` for sources whose domains should be kept off the blocklist.
3. Submit a pull request explaining the change.

### Removing a source

If a source is causing problems or is no longer maintained, remove its URL from the relevant file:

- Remove a blocklist source from `blacklist/bl-sources.txt`.
- Remove a whitelist source from `whitelist/wl-sources.txt`.

## Guidelines for contributions

- **Accuracy:** Check that each domain or source is relevant before submitting it.
- **Evidence:** Include references that help reviewers verify the request. Do not attach explicit media.
- **Format:** Use plain text, lowercase domain names (for example, `example.com`), and keep entries in alphabetical order.
- **Duplicates:** Check the [Domain Search Tool](https://bon-appetit.github.io/domain-search/) before submitting a domain.
- **Submissions:** Do not submit spammy or malicious domains or sources.

## Important notes

- The generated `block.{FILE_HASH}.{RANDOM_HASH}.txt` and `allow.{FILE_HASH}.{RANDOM_HASH}.txt` files should not be edited manually.
- For domain or source changes, edit only `blacklist/bl-custom.txt`, `whitelist/wl-custom.txt`, `blacklist/bl-sources.txt`, or `whitelist/wl-sources.txt`.
