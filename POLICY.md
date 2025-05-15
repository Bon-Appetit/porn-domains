# 📜 Domain List Policy

This document outlines **why** and **how** we maintain domains in this repository, as well as the process for adding or removing domains. **The Goal** is to provide a **family-friendly** network environment by blocking access to pornographic or explicit sites at the DNS level.

## 🗂️ Repository Scope & Purpose

### 🎯 Primary Purpose

- We collect domains that are used for hosting, distributing, or facilitating pornographic or explicit sexual content.
- This includes both “traditional” adult content websites (e.g., porn tube sites, adult pay sites) and **user-generated content** platforms that allow unrestricted uploads of explicit material with no effective adult-only gating.

### ❓ Why A Dns-Based List?

- DNS-level blocking is a straightforward approach for home networks, schools, or organizations that want to prevent accidental (or intentional) access to adult content.
- This repository is offered as-is; it might not capture *all* adult domains. We welcome community contributions to keep it updated.

### 👥 Intended Audience

- Network administrators, parents, educators, or anyone else wanting to apply a “porn block” via DNS resolvers.
- It is **not** intended to be a censorship tool – it’s a resource for people seeking to enforce their own preferences or policies regarding adult content.

## ✅ Criteria For Inclusion (Block Criteria)

A domain **should** be added to the list if **one or more** of these conditions apply:

### 🔞 Primary Adult Content

- The domain’s **main purpose** is to distribute or promote explicit, pornographic, or highly sexualized content.
- Examples: Porn streaming sites, adult magazines, adult video chat services, etc.

### 📤 Unrestricted Uploads / Sharing

- The domain **hosts** user-generated content (images, videos, etc.) that **regularly includes** pornographic or explicit material **without** meaningful content filtering or age-gating.
- If explicit media can be uploaded and shared publicly at `example.com/<random-link>`, that domain belongs in the block list (especially if it is known to be regularly used for porn distribution).

### ⚖️ No Separation Between Adult & Non-Adult Content

- If a platform **mixes** adult and non-adult content under the **same domain** (i.e., no subdomain separation or robust filter), it may be considered effectively “adult.”
- For example, if `somesite.com` has both a “family-friendly” section **and** a “hardcore porn” section all on `somesite.com` (not `adult.somesite.com`), it is difficult to block one without blocking the other. Hence, it’s likely included here.

### 🔗 Domain Redirects Or Affiliates

- The domain **exists** primarily to redirect to porn/erotic content or adult affiliate programs.
- Example: If you go to `redirect-porn-ads.com`, and it immediately sends you to `pornsite.com`, it is effectively an adult domain.

### 🏷️ Known Porn “Brand”

- The domain is a recognized brand name in adult entertainment, used for marketing or distributing adult content, even if the homepage occasionally displays “PG” text.

### 📢 Consistent Community Reports

- Multiple credible user reports indicate the domain is hosting or significantly involved with explicit content.
- Submissions must have some form of evidence or reference.

## 🚫 Criteria For Exclusion Or Removal

A domain should **not** be added (or should be **removed**) if it **only** meets one or more of these conditions:

### ⚠️ Incidental Or Rare Adult Content

- The site is **not** primarily adult; it might have forums or discussions that occasionally include NSFW content, but that is not a major part of the site.
- Example: A mainstream news site that publishes one adult-themed article per year.

### 🛡️ Legitimate Hosting / Social Platforms With Strict Filters

- Large, mainstream platforms (e.g., Twitter, YouTube, Imgur, or others) that have robust policies, age gates, or adult filters are typically **excluded**, unless adult content is a central, unmoderated aspect of the site.
- For instance, **if** a major platform is known to have unfiltered or majority porn content, it may end up on the list – but that is quite rare. (We treat these on a case-by-case basis.)

### 🌐 Subdomain Separation

- The domain has a separate **adult-only subdomain** (e.g., `xxx.example.com`) which can be selectively blocked, and the rest of the domain is safe.
- In this scenario, we may add **only** the adult subdomain rather than the entire domain, if that effectively blocks explicit content.

### 🔄 Cleared / Changed Policies

- The site used to host explicit content but no longer does; or they implemented a robust gating mechanism that effectively keeps adult content behind a login or adult subdomain.
- If a domain owner demonstrates meaningful changes, we should remove it from the block list.
