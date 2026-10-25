# 0xm4ngli Speedtest

Real-time browser speedtest measuring ping, download, and upload against live endpoints (Tele2 EU, Cloudflare Global). Auto-detects visitor info via `ipapi.co`.

## Quick Start

```bash
bun dev
```

Open [http://localhost:3000](http://localhost:3000).

## Build / Deploy

```bash
bun run build
```

Deploy via Vercel: [vercel.com/new](https://vercel.com/new)

## Used Technologies & Licenses

| Technology | License | Source / Link |
|---|---|---|
| Next.js | MIT | [github.com/vercel/next.js](https://github.com/vercel/next.js) |
| React | MIT | [github.com/facebook/react](https://github.com/facebook/react) |
| React DOM | MIT | [github.com/facebook/react](https://github.com/facebook/react) |
| Tailwind CSS | MIT | [github.com/tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) |
| TypeScript | Apache-2.0 | [github.com/microsoft/TypeScript](https://github.com/microsoft/TypeScript) |
| ESLint | MIT | [github.com/eslint/eslint](https://github.com/eslint/eslint) |
| Geist Font | SIL OFL / Apache-2.0 (via Vercel) | [vercel.com/font](https://vercel.com/font) |

**Full license texts:**
- MIT: [opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)
- Apache-2.0: [apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)

No proprietary or proprietary-locked dependencies are required for runtime.

## Privacy Note

This site does **not** store visitor IPs, locations, or network data. All visitor info (`ipapi.co`) is fetched client-side at page load and is never saved to GitHub, Vercel build logs, or the source repo.
