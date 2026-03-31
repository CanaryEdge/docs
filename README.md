# Canary Edge Documentation

API documentation for [Canary Edge](https://canaryedge.com) -- state-of-the-art anomaly detection API.

Published at [docs.canaryedge.com](https://docs.canaryedge.com) via Mintlify.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing

Changes pushed to the `main` branch are automatically deployed to production via the Mintlify GitHub app.

## Structure

- `docs.json` -- Mintlify configuration and navigation
- `index.mdx` -- Landing page
- `quickstart.mdx` -- Getting started guide
- `concepts.mdx` -- Core concepts
- `guides/` -- Migration and advanced guides
