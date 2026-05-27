# Your Shirt MVP — Agent Instructions

## Project
Build “Your Shirt”, a Shopify-compatible AI football t-shirt customiser.

Users select:
- team/country
- player(s)
- shirt colour
- design style
- scene/action
- optional text

Then they:
- generate an AI preview;
- refine it up to 10 times;
- compare versions;
- approve one version;
- add the approved design to Shopify cart;
- pay through Shopify;
- after payment, the backend generates the final print-ready file;
- admin reviews the final file;
- only after admin approval is the order submitted to a supplier.

## Non-Negotiable Rules

1. Do not submit any supplier fulfilment order unless:
   - Shopify order is paid;
   - final print file exists;
   - admin has approved fulfilment.

2. Do not create paid supplier subscriptions.

3. Do not purchase samples or inventory.

4. Do not expose API keys in frontend code.

5. Do not commit secrets to the repository.

6. Do not make legal, pricing, refund, licence, brand or launch-market decisions without asking Miguel.

7. Use mock data where needed and mark it clearly as mock data.

8. If a decision is required from Miguel, stop and ask a clear question.

## Stack

- Next.js
- TypeScript
- Tailwind
- Supabase/PostgreSQL
- Shopify
- Vercel
- Cloudflare R2 or S3
- AI image provider: FLUX
- Printful/Gelato integration later

## MVP Scope

Build first:
1. customiser UI;
2. design database;
3. preview generation;
4. refinement flow with 10 free refinements;
5. version history;
6. approve version;
7. add approved design to Shopify cart;
8. paid-order webhook;
9. final print generation placeholder;
10. admin review dashboard.

Supplier fulfilment must remain mocked until Miguel explicitly approves real supplier integration.

## First Test Catalogue

Use mock/test catalogue:
- Team: Portugal
- Players: João Neves, Vitinha
- Styles: Premium Portrait, Retro Football Poster, Comic Hero, Cinematic Tunnel, Streetwear Gold
- Scenes: Standing Portrait, Goal Celebration, Trophy Pose, Tunnel Walkout, Back-to-Back Duo, Face-Off, Running Action, Team Trio, Victory Moment
- Shirt colours: black, white, navy
- Sizes: S, M, L, XL, XXL

## UX Requirements

The customiser must include:
- step-by-step selection flow;
- preview area;
- refinement panel;
- 10 free refinements counter;
- version history;
- approve-design button;
- add-to-cart button after approval.

## Ask Miguel Before

Ask Miguel before:
- choosing a paid tool;
- connecting real payment;
- submitting real fulfilment;
- selecting final domain;
- selecting final pricing;
- creating refund/returns rules;
- choosing supplier SKU;
- using real API credentials;
- changing the product flow.
