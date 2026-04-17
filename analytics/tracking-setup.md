# 🧭 AsyncKeel Tracking Setup Guide

A practical, indie-friendly setup to track growth, activation, and sales without a heavy analytics stack.

## 1) GitHub Insights Setup

Use **GitHub Insights** and repository traffic pages weekly:

- **Stars / Watchers / Forks**: monitor repository interest and retention proxies.
- **Traffic**: track unique visitors, views, and clone counts.
- **Top referrers**: identify where qualified visitors are coming from.

Weekly habit:
1. Open repository `Insights`.
2. Capture stars, watchers, clones, unique visitors.
3. Paste snapshot into the weekly tracker.

## 2) Sales Analytics (Gumroad or LemonSqueezy)

Track one-time license performance from your payment provider dashboard:

- Orders by product (Indie vs Studio)
- Revenue by day/week
- Refunds and net revenue
- Conversion by coupon (especially early-bird)

Minimum weekly snapshot:
- Indie sales count
- Studio sales count
- Gross revenue
- Early-bird coupon usage

## 3) Website Analytics (Plausible or Fathom)

For privacy-first analytics that fit indie workflows, use **Plausible** or **Fathom**:

- Unique visitors
- Top landing pages
- Goal conversions (README click, quick start completion, checkout click)
- Referrers and campaign performance

Recommendation:
- Define at least 3 goals before launch week:
  - `readme_click`
  - `quickstart_complete`
  - `pricing_checkout_click`

## 4) UTM Parameter Framework

Use consistent UTM parameters across all campaign links.

Core format:
- `utm_source`: twitter, linkedin, reddit, hn, email
- `utm_medium`: social, community, newsletter
- `utm_campaign`: month3_features, launch_warmup, producthunt_launch
- `utm_content`: post_type_variant (thread_a, teaser_b, email_launch_a)

Channel examples:

- **Twitter/X**
  - `...?utm_source=twitter&utm_medium=social&utm_campaign=month3_features&utm_content=thread_a`
- **LinkedIn**
  - `...?utm_source=linkedin&utm_medium=social&utm_campaign=month3_features&utm_content=post_a`
- **Reddit**
  - `...?utm_source=reddit&utm_medium=community&utm_campaign=launch_warmup&utm_content=subreddit_post_1`
- **Hacker News**
  - `...?utm_source=hn&utm_medium=community&utm_campaign=producthunt_launch&utm_content=show_hn`
- **Email**
  - `...?utm_source=email&utm_medium=newsletter&utm_campaign=producthunt_launch&utm_content=launch_announcement_a`

## 5) Weekly Spreadsheet Tracker Template

Use a simple spreadsheet (one row per week) with these columns:

| Week | Stars | Watchers | Clones | Website UV | Organic Visits | README→Repo CTR | Quick Start Completion | Indie Sales | Studio Sales | Revenue | Early-Bird CVR | Top Channel | Notes |
|------|-------|----------|--------|------------|----------------|------------------|------------------------|-------------|--------------|---------|----------------|-------------|-------|

## 6) Alerts: When to Worry, When to Celebrate

### Worry Signals (2 consecutive weeks)
- Clone rate drops by **30%+**
- Quick start completion below **15%**
- Newsletter retention below **75%**
- Early-bird conversion below **4%** during launch window

### Celebrate Signals
- 20+ stars in a week
- 10+ paid licenses in a week
- Quick start completion above **30%**
- Product Hunt day reaches **200+ upvotes**

## 7) Review Rhythm

- **Weekly (30 min):** snapshot metrics + identify one bottleneck.
- **Monthly (60 min):** compare against May/June/July targets.
- **Launch week (daily):** monitor traffic, conversions, and inbound comments.
