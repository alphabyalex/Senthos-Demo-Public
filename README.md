# Senthos — Demo

**Frontend Only Live:** https://lukres-o8z3.vercel.app

**1st Place, USC SCBC Hackathon 2026 — $7,000 prize, judged by the Solana Foundation.**

Senthos is a structured-products protocol built on Solana that tokenizes live prediction market positions into on-chain derivative instruments. It bundles 100+ Polymarket contracts into tradeable basket tokens with tranched risk slices and principal protected note structures backed by USDC vault yield, so a user can express a view with a clear risk profile instead of picking individual markets one at a time.

## About this demo

This is a **frontend-only preview** of the Senthos UI deployed to Vercel as a sneak peek ahead of the full release.

A few things to know:

- The **live backend is not connected here.** Anything that needs real pricing, live basket data, AI portfolio personalization, or on-chain state will render placeholders or not at all. The full version runs against a separate API and a Solana devnet deployment.
- Click through freely to portfolio, constellations, tranches, and PPN to see the interaction model and visual language.
- Nothing here is a financial product or investment advice.

## What I contributed

I led the frontend and product architecture: design system, landing page, portfolio and tranche surfaces, the PPN flow, tranche tokens, and interaction polish. The broader project is a team effort with separate backend, ML, and on-chain contributors.

## Stack

- Next.js 16, React 19, TypeScript
- Inline styles (no Tailwind)
- Solana wallet adapter (devnet in the full build)

## Status

Won. More coming.
