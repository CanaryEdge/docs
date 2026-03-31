# Canary Edge Documentation

API documentation for [Canary Edge](https://canaryedge.com) -- anomaly detection powered by Learned World Models.

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
- `api-reference/` -- API endpoint documentation
  - `endpoint/detect.mdx` -- Azure-compatible entire series detection
  - `endpoint/detect-last.mdx` -- Azure-compatible last point detection
  - `endpoint/detect-changepoint.mdx` -- Azure-compatible changepoint detection
  - `endpoint/native-detect.mdx` -- Native detection with regime classification
  - `endpoint/baseline.mdx` -- Baseline management
  - `endpoint/status.mdx` -- Machine status
  - `endpoint/machines.mdx` -- Machine listing and deletion
  - `endpoint/usage.mdx` -- Usage statistics
  - `endpoint/health.mdx` -- Health check
- `guides/` -- Migration and advanced guides
