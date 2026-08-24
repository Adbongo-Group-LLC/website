# Adbongo website

Canonical marketing site: **https://adbongo.ai**

Repo: [Adbongo-Group-LLC/website](https://github.com/Adbongo-Group-LLC/website)  
GitHub Pages serves this folder. Custom domain file: `CNAME` → `adbongo.ai`.

This is HTML only. It is not the RSS3 node and not the Railway agent.

## adbongo.io

Do **not** put `adbongo.io` in this `CNAME`. GitHub Pages allows one custom domain; `.ai` is that domain.

To make **adbongo.io** show the same site, add a **301/URL forward** at the DNS host:

- `adbongo.io` (apex) → `https://adbongo.ai`
- Optional: `www.adbongo.io` → `https://adbongo.ai`

**Warning:** `www.adbongo.io` is currently **Substack** (essays, podcast embeds). Forwarding `www` replaces the blog with this Pages site. Keep `www` on Substack unless you mean to move the blog.

`web3.adbongo.io` stays on Linode (RSS3 + old static copy). Leave it unless you decide to retire that hostname.

## DNS for adbongo.ai (already verified)

Keep the GitHub Pages records GitHub showed when you verified the domain (A/AAAA or ALIAS for apex, CNAME for `www.adbongo.ai` if you use it).
