# Vocaler AI

**Cloud-native music-video rendering.** We build tools that turn audio into share-ready visual content.

## Products
- **Music Visualizer** — a SaaS at [musicvisualizer.pro](https://musicvisualizer.pro) for rendering downloadable MP4 music-visualizer videos (16:9 / 9:16, up to 4K·60fps) from your music, artwork, and lyrics.
- **Vocaler** — the render platform & API (`api.vocaler.ai`): a horizontally-scalable, serverless render farm (SQS → AWS Lambda) that also hosts partner render engines.

## Engineering
- Polyglot monorepos — TypeScript/Next.js (web), Python/FastAPI (render API), Node (Lambda render farm).
- Cloud-native & scalable by design: Cloudflare edge, object storage on R2, rendering on AWS Lambda.
- Every repo ships with security & quality baked in — CodeQL, Dependabot, branch protection, and a private vulnerability-disclosure policy.

## Security
Found a vulnerability? Please report it privately — see each repo's `SECURITY.md` (or email `security@vocaler.ai`). Do not open public issues for security reports.

---
<sub>© Vocaler AI — proprietary. All rights reserved.</sub>
