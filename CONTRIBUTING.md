# 🤝 Contributing

First off, thanks for taking the time to contribute! ❤️

Whether you're reporting a missing domain, fixing a mistake, or suggesting improvements, all types of contributions are encouraged and valued.

## 🪴 How To Contribute

> [!NOTE]
> If you don’t have a GitHub account or prefer to stay anonymous when reporting a domain, feel free to drop me an email at mail@codealdente.ovh. You’re also welcome to reach out if you have any questions about this project.

### ➕ Add Or Remove A Domain

You can either **create a new issue** to suggest adding or removing a domain, or if you're comfortable, **submit a pull request** with the changes yourself.

#### 📝 Option 1: Report A Domain Via Issue

To suggest adding or removing a domain, please follow these steps:

**Create an issue**: Create a [new issue](https://github.com/Bon-Appetit/porn-domains/issues) and include the following:

- **Domain name(s)** you want to add or remove (e.g. example.com)
- **Reason for inclusion/exclusion** (e.g. contains porn, false-positive, "family safe" etc.)
- **Supporting evidence** (such as URLs, screenshots or references)

#### 🔀 Option 2: Submit A Domain Via Pull Request

If you prefer to make the changes yourself, you can submit a pull request. Here's how:

1. **Fork the repository** and clone it to your local machine
2. **Edit the list**:
  - **To block a domain**: Add it to the `blacklist/bl-custom.txt` file
  - **To whitelist a domain**: Add it to the `whitelist/wl-custom.txt` file (this will also remove the domain from the blocklist)
3. **Commit your changes** and submit a pull request with a clear description of what you changed

### ➕ Add Or Remove A Source

Sources are URLs that point to files containing multiple domains. You can either **create a new issue** to suggest adding/removing a source, or **submit a pull request** with the changes yourself.

#### 📝 Option 1: Report A Source Via Issue

To suggest adding or removing a source, follow these steps:

**Create an issue**: Create a [new issue](https://github.com/Bon-Appetit/porn-domains/issues) with the following:

- **Source URL** you want to add or remove
- **Reason for inclusion/exclusion** (e.g. source contains too many false positives etc.)
- **Supporting evidence** (e.g. list some domains from the source that shouldn't be in there)

#### 🔀 Option 2: Submit A Source Via Pull Request

If you'd like to make the changes yourself, you can submit a pull request. Here's how:

1. **Fork the repository** and clone it to your local machine
2. **Edit the list**:
  - **To add a blacklist source**: Add the URL to `blacklist/bl-sources.txt` to include more domains in the blocklist
  - **To add a whitelist source**: Add the URL to `whitelist/wl-sources.txt` to minimize false positives by excluding domains in that source from the blocklist
3. **Commit your changes** and submit a pull request with a clear description of what you changed

### ➖ Removing A Source

You can also **remove** a source from the blocklist or whitelist if it's causing issues:

1. **To remove a blacklist source**: If a blacklist source is causing too many false positives, you can remove its URL from `blacklist/bl-sources.txt`
2. **To remove a whitelist source**: If a whitelist source is causing false positives (incorrectly marking safe domains as blocked), you can remove its URL from `whitelist/wl-sources.txt`

## 💡 Guidelines For Contributions

- **Accuracy**: Verify domains and sources before adding them to ensure their relevance
- **Evidence**: When possible, provide supporting references, such as URLs or screenshots
- **Format**:
  - Use **plain text** for domains and source URLs
  - Use **all lowercase** for domain names (e.g. example.com)
  - Keep entries in **alphabetical order**
- **Avoid Duplicates**: Before submitting a domain, please use the [Domain Search Tool](https://bon-appetit.github.io/domain-search/) to check if the domain is already in the list. This helps us avoid duplicates and ensures the list remains clean and accurate.
- **Respect**: Avoid submitting spammy or malicious domains or sources

## ℹ️ Important Notes

- **block.{FILE_HASH}.{RANDOM_HASH}.txt** and **allow.{FILE_HASH}.{RANDOM_HASH}.txt**: These files are automatically generated and should **never** be modified manually.
- **Custom files**: Only modify `blacklist/bl-custom.txt`, `whitelist/wl-custom.txt`, `blacklist/bl-sources.txt`, and `whitelist/wl-sources.txt`.

## 💝 Thank You!

Your contributions make this project stronger and help the community. Thank you for your time and effort!
