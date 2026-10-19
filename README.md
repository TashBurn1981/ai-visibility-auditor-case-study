# AI Visibility Auditor: case study

A web app I designed and built for [Hashtaggz Marketing](https://hashtaggzmarketing.com) that checks how visible a business website is to Google **and** to AI search engines such as ChatGPT, Gemini, Perplexity and Google AI Overviews.

**Live tool:** [hashtaggzaivis.onrender.com](https://hashtaggzaivis.onrender.com)

> This repo is a case study. The production code is private.

## The problem

Small businesses are being judged by AI answers now, not just Google rankings. Most have no idea whether AI engines can read their site, understand what they do, or recommend them. Traditional SEO tools don't measure this.

## What it does

- Audits any website for **SEO, GEO (Generative Engine Optimisation), AEO (Answer Engine Optimisation) and AI crawlability**
- Gives a **free visibility score** instantly
- Lets users add **competitors, target keywords and business context** for a sharper audit
- Produces a **full, AI-enriched report** with prioritised fixes as a paid upgrade
- Captures verified email leads before the audit runs, feeding the agency's sales pipeline

## How it's built

| Layer | Tools |
| --- | --- |
| Front end | React, Vite, TypeScript |
| Back end | Node.js API (lead capture, free audit, paid audit, payment verification) |
| AI analysis | Google Gemini API |
| Prototyping | Google AI Studio (Build mode) |
| Hosting | Render, auto-deploying from GitHub |
| Distribution | Linked from hashtaggzmarketing.com |

## Business model

Free score as a lead magnet, paid full report as an entry product, and the report findings lead into ongoing GEO and SEO services.

## What I learned

- AI-assisted building (AI Studio, Claude) means a marketer can ship a real, paid product without a dev team
- Gating the tool behind email capture turns a free audit into a qualified lead source
- The hard part isn't the code, it's deciding what a "visible to AI" score should actually measure

## About me

Tash Burn, founder of Hashtaggz Marketing, Marbella, Spain. AI-first marketing: GEO, SEO, Meta Ads and Google Ads.
