# 🍔 workers-bun-hono-template

> A template for creating a [Cloudflare Workers](https://workers.cloudflare.com/) project with [Bun](https://bun.sh/) and [Hono](https://honojs.dev).

## Usage

**Preqrequisites:**

1. [Wrangler](https://developers.cloudflare.com/workers/wrangler/get-started/#install)
2. Bun (Node.js runtime)

**Install and setup:**

```bash
git clone git@github.com:plibither8/workers-bun-hono-template
cd workers-bun-hono-template
bun install
```

**Development:** `wrangler dev`

**Production:** `wrangler publish`

## Development

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v0.1.10. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

> Note: The server was build to be hosted on Cloudflare Workers.

## License

[MIT](LICENSE)
