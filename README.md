**Starting from 1st September, 2021 there won't be any further DNS checks anymore. A small virtual server was in place for this but it's getting too expensive now.**

---

# Porn Domains
This list is a collection of bunch of domains that relate to adult content, mainly porn websites.

## ![#ff0000](https://placehold.co/15/ff0000/ff0000) PLEASE NOTICE:
There have been a lot of effort put into this repository to make sure the domains are all valid. Also the DNS checks are run with caution to make sure to avoid false results as much as possible. But keep in mind that things change so quickly. **THERE IS NO WARRANTY GIVEN THAT THESE LISTS ARE 100% ACCURATE. USE THEM AT YOUR OWN RISK, ESPECIALLY IN PRODUCTION.**

### [block.txt](https://github.com/Bon-Appetit/porn-domains/blob/master/block.txt)
Contains all domains which are used for porn websites line by line. Domains from ignore.txt and white.txt are removed from here.

### [ignore.txt](https://github.com/Bon-Appetit/porn-domains/blob/master/ignore.txt)
A list of domains which have been tested for their availability. Those domains are no longer registered or do not have any valid DNS records which also makes them unable to access.

### [white.txt](https://github.com/Bon-Appetit/porn-domains/blob/master/white.txt)
Here you can find domains which are false listed or whose content has changed.

#### Something's missing?
Adding individual domains is no longer supported. Instead please submit a GitHub-Repository pointing to a list of domains.

Say you want to add the following source:
https://github.com/user/repository/blob/branch/file.txt

File an issue ticket and provide the new source as below. Or just add it to the sources ([sources.json](https://github.com/Bon-Appetit/porn-domains/blob/master/sources.json)) and send a pull request.

```json
{
    "id": "user@repository~nakedsite",
    "repo_url": "https://github.com/user/repository",
    "source_blob": "https://github.com/user/repository/blob/branch/file.txt",
    "source_raw": "https://raw.githubusercontent.com/user/repository/branch/file.txt"
}
```

Feel free to also report domains which are no longer used for such explicit content. You can file an issue ticket or send a pull request with your updated whitelist ([white.txt](https://github.com/Bon-Appetit/porn-domains/blob/master/white.txt)).

Thank you!