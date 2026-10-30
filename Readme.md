# Awesome Free Dev Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of genuinely free tools, hosting, and utilities every developer should know about. No trials, no "free for 14 days" - actual free tiers you can build on.

Built and maintained by indie hackers, for indie hackers. PRs welcome, see the Contributing section below.

## Contents

- [Hosting & Deployment](#hosting--deployment)
- [Databases](#databases)
- [Developer Utilities (Browser-Based)](#developer-utilities-browser-based)
- [Backend / API Infrastructure](#backend--api-infrastructure)
- [Starter Kits & Boilerplates](#starter-kits--boilerplates)
- [Email & Transactional](#email--transactional)
- [Analytics](#analytics)
- [CI/CD](#cicd)
- [Design & Assets](#design--assets)
- [Monitoring & Error Tracking](#monitoring--error-tracking)
- [Domains & DNS](#domains--dns)
- [AI / LLM Dev Tools](#ai--llm-dev-tools)

---

## Hosting & Deployment

- [Vercel](https://vercel.com) - Zero-config hosting for Next.js and other frontend frameworks. Generous free tier, automatic preview deployments per PR.
- [Netlify](https://netlify.com) - Static site and Jamstack hosting with built-in forms, functions, and CI. Free tier covers most side projects comfortably.
- [Cloudflare Pages](https://pages.cloudflare.com) - Unlimited free static hosting with unlimited bandwidth, backed by Cloudflare's global CDN.
- [Cloudflare Workers](https://workers.cloudflare.com) - Serverless functions at the edge, extremely generous free request quota.
- [Railway](https://railway.app) - Deploy full backends, databases, and cron jobs from a Dockerfile or repo with minimal config. Free trial credits, then usage-based.
- [Render](https://render.com) - Free tier for web services, static sites, and cron jobs - good Heroku alternative.
- [Fly.io](https://fly.io) - Deploy containers close to your users globally, free allowance for small apps.
- [GitHub Pages](https://pages.github.com) - Free static hosting directly from a GitHub repo, good for docs and simple sites.

## Databases

- [Supabase](https://supabase.com) - PostgreSQL + auth + storage + realtime, generous free tier, open source Firebase alternative.
- [Neon](https://neon.tech) - Serverless PostgreSQL with branching and scale-to-zero, free tier is genuinely usable for small production apps.
- [PlanetScale](https://planetscale.com) - Serverless MySQL platform with schema branching.
- [Upstash](https://upstash.com) - Serverless Redis and Kafka, pay-per-request pricing with a real free tier - great for usage-tracking and rate limiting.
- [Turso](https://turso.tech) - Edge-hosted SQLite (libSQL), free tier suited for read-heavy small apps.
- [MongoDB Atlas](https://www.mongodb.com/atlas) - Free-forever shared cluster for MongoDB.

## Developer Utilities (Browser-Based)

Tools that run entirely client-side - nothing you paste gets uploaded anywhere.

- [Simple Dev Tools](https://simpledevtools.org) - Free, privacy-first browser-based developer utilities: JSON formatter/validator, JWT decoder, Base64/URL encoding, regex tester, hash & HMAC generators, UUID/NanoID/ULID generators, cron parser, and more, all client-side.
- [CyberChef](https://gchq.github.io/CyberChef/) - GCHQ's "cyber Swiss Army knife" for encoding, encryption, and data analysis, entirely in-browser.
- [DevDocs](https://devdocs.io) - Fast, searchable API documentation for dozens of languages and frameworks in one place.
- [Regex101](https://regex101.com) - Regex tester and debugger with a detailed explanation panel for each pattern.
- [JSON Crack](https://jsoncrack.com) - Visualize JSON/YAML data as an interactive graph.
- [Excalidraw](https://excalidraw.com) - Free, open-source virtual whiteboard for sketching diagrams with a hand-drawn feel.
- [tldraw](https://www.tldraw.com) - Infinite canvas whiteboard, good for quick architecture sketches.
- [RadarMakers Changelog Generator](https://radarmakers.com/tools/changelog-generator) - Turns change notes into a grouped changelog or release notes in Markdown or HTML, free and in the browser.

## Backend / API Infrastructure

- [Trigger.dev](https://trigger.dev) - Open-source background jobs and workflows for TypeScript, generous free tier.
- [Inngest](https://www.inngest.com) - Event-driven background jobs and durable workflows, free tier for small projects.
- [Resend](https://resend.com) - Developer-first transactional email API with a usable free tier (see [Email](#email--transactional) too).
- [Pinecone](https://www.pinecone.io) - Managed vector database for embeddings/RAG, free starter tier.
- [Cloudflare R2](https://www.cloudflare.com/products/r2/) - S3-compatible object storage with zero egress fees, free tier included.

## Starter Kits & Boilerplates

- [Shipindays](https://shipindays.nikhilsai.in) - Open-source Next.js SaaS starter CLI with a base + blocks pattern, so you scaffold only the pieces you need (auth, billing, etc) instead of a monolithic template.
- [create-t3-app](https://create.t3.gg) - Typed, minimal Next.js starter combining tRPC, Prisma, NextAuth, and Tailwind.
- [SaaS Starter (Vercel)](https://github.com/nextjs/saas-starter) - Official Vercel/Next.js SaaS starter with auth, Stripe billing, and dashboard boilerplate.

## Email & Transactional

- Resend - Clean API and React Email templates, 3,000 emails/month free.
- [AWS SES](https://aws.amazon.com/ses/) - Very cheap at scale, free tier when sending from an EC2-hosted app; a common choice once you outgrow other providers' free tiers.
- [Mailgun](https://www.mailgun.com) - API-based transactional email with a limited free tier.

## Analytics

- [PostHog](https://posthog.com) - Product analytics, session replay, feature flags, and A/B testing in one open-source platform, generous free tier.
- [Plausible](https://plausible.io) - Lightweight, privacy-friendly analytics (paid, but has an open-source self-hosted free option).
- [Umami](https://umami.is) - Open-source, privacy-focused Google Analytics alternative, free to self-host.
- [Vercel Analytics](https://vercel.com/analytics) - Basic free web analytics if you're already deployed on Vercel.

## CI/CD

- [GitHub Actions](https://github.com/features/actions) - Free CI/CD minutes for public repos, generous free tier for private ones too.
- [CircleCI](https://circleci.com) - Free tier of build credits per month.
- Vercel - Automatic CI/CD and preview deployments included with hosting, no separate setup needed.

## Design & Assets

- [Figma](https://www.figma.com) - Free tier covers solo indie hacker use comfortably.
- [Undraw](https://undraw.co) - Free, customizable open-source illustrations.
- [Lucide](https://lucide.dev) - Open-source icon set, consistent and free (used in this very list's source project).
- [Coolors](https://coolors.co) - Fast color palette generator.
- [Google Fonts](https://fonts.google.com) - Free, open-source web fonts.

## Monitoring & Error Tracking

- [Sentry](https://sentry.io) - Error tracking and performance monitoring, free tier suitable for small production apps.
- [Better Stack](https://betterstack.com) - Uptime monitoring and log management, free tier available.
- [UptimeRobot](https://uptimerobot.com) - Simple free uptime monitoring for up to 50 monitors.

## Domains & DNS

- [Cloudflare](https://www.cloudflare.com) - Free DNS, CDN, and basic DDoS protection for any domain.
- [Namecheap](https://www.namecheap.com) - Not free, but frequently cheapest for `.com`/`.org` registration - mentioned since domain cost is the one thing on this list you can't avoid entirely.

## AI / LLM Dev Tools

- [OpenAI Pricing Calculator (Simple Dev Tools)](https://simpledevtools.org/tools/openai-pricing-calculator) - Estimate OpenAI API costs by model and token usage.
- [LLM Token Counter (Simple Dev Tools)](https://simpledevtools.org/tools/token-counter) - Count tokens for GPT, Claude, and other LLMs before hitting context limits.
- [Ollama](https://ollama.com) - Run open-source LLMs locally, completely free.
- [Hugging Face](https://huggingface.co) - Free hosting and inference for a huge range of open models and datasets.

---

## Contributing

PRs are welcome. To add a tool:

1. Fork this repo
2. Add your entry to the relevant category, alphabetically where possible, using the existing format: `[Name](https://link) - One sentence, no marketing fluff.`
3. Only genuinely free (not just free-trial) tools, please
4. Open a pull request