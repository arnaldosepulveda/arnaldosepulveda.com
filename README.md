# arnaldosepulveda.com

Personal site for [Arnaldo Sepulveda](https://arnaldosepulveda.com/). Single static HTML page deployed via Cloudflare Pages.

This repository maintains the canonical personal web presence for Arnaldo Sepulveda: engineer, builder, and public technical identity behind Keystone Applied Intelligence.

## Purpose

This site exists primarily as:

- a **search-result destination** for name-based queries,
- an **entity-consolidation target** that ties together LinkedIn, GitHub, and Keystone,
- a **canonical personal URL** for bios, profiles, and references,
- a **structured-data surface** that helps search systems understand the person behind the work.

The site is intentionally simple. Its job is not to be an app. Its job is to establish a stable, credible, machine-readable identity surface.

## What the site communicates

The site should communicate a small number of things very clearly:

- who Arnaldo Sepulveda is,
- what kind of engineering work he does,
- how Keystone Applied Intelligence fits into that work,
- where to find the primary public profiles and repositories,
- what technical domains he is associated with.

## Structured data

The page includes `Person` schema in JSON-LD so the site can act as the canonical identity node for Arnaldo Sepulveda and connect to external profiles through `sameAs` links.[web:133][web:139][web:142]

This structured data should consistently point to authoritative public profiles such as:

- LinkedIn,
- GitHub personal profile,
- Keystone organization or website,
- other durable professional profiles if added later.

A stable `@id`, consistent `sameAs` links, and accurate role/description fields help search systems connect the person entity across surfaces.[web:133][web:142]

## Stack

- Plain HTML
- Plain CSS
- No framework
- No build step
- Static JSON-LD embedded in `index.html`

## Deployment

The site is deployed with Cloudflare Pages. Pages supports Git-integrated automatic deployments, including production deployments from a configured branch.[web:128][web:129]

In the current setup:
- the production branch is `main`, [web:128]
- the site auto-deploys when changes are pushed, [web:129]
- no framework build pipeline is required for a plain static page.

## Editing workflow

Edit `index.html` directly, commit, and push to `main`. Cloudflare Pages will redeploy the site automatically from the connected repository.[web:128][web:129]

Because the site is intentionally minimal, changes should stay disciplined:
- update copy only when the public positioning has genuinely changed,
- keep links canonical and current,
- keep JSON-LD synchronized with the visible page,
- avoid adding unnecessary client-side complexity.

## Content rules

When editing the site:

- Keep the page focused on identity, not product-detail overload.
- Use the site to consolidate public references, not duplicate full project documentation.
- Keep role/title language aligned with LinkedIn, GitHub, and Keystone surfaces.
- Treat the JSON-LD block as part of the product, not as an afterthought.
- Prefer durable links over transient ones.

## Repository role

This repository exists to maintain the canonical personal identity surface for Arnaldo Sepulveda on the public web.

It should help both humans and search systems answer:
- who this person is,
- what work he is known for,
- what public projects are connected to him,
- and which external profiles are authoritative.

## Related links

- Personal LinkedIn: [linkedin.com/in/arnaldosepulveda](https://www.linkedin.com/in/arnaldosepulveda/)
- Personal GitHub: [github.com/arnaldosepulveda](https://github.com/arnaldosepulveda)
- Keystone Applied Intelligence: [getkeystone.ai](https://getkeystone.ai/)
- Keystone GitHub org: [github.com/getkeystone](https://github.com/getkeystone)

## License

Apache 2.0
