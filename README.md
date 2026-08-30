# arnaldosepulveda.com

Personal site for [Arnaldo Sepulveda](https://arnaldosepulveda.com/), engineer and builder behind Keystone Applied Intelligence. It's the canonical personal page that links his primary public profiles (LinkedIn, GitHub, Keystone). A single static HTML page, deployed via Cloudflare Pages.

## Stack

- Plain HTML + CSS, no framework, no build step
- `Person` JSON-LD (schema.org) embedded in `index.html`, with `sameAs` links to external profiles

## Deployment

Hosted on Cloudflare Pages with Git integration. Production branch is `main`; pushes to `main` auto-deploy. There is no build pipeline; the static files are served as-is.

## Editing

Edit `index.html`, commit, and push to `main`; Cloudflare Pages redeploys automatically. Keep the JSON-LD in sync with the visible content and prefer durable, canonical links.

## Links

- LinkedIn: [linkedin.com/in/arnaldosepulveda](https://www.linkedin.com/in/arnaldosepulveda/)
- GitHub: [github.com/arnaldosepulveda](https://github.com/arnaldosepulveda)
- Keystone Applied Intelligence: [getkeystone.ai](https://getkeystone.ai/)
- Keystone GitHub org: [github.com/getkeystone](https://github.com/getkeystone)

## License

Apache 2.0
