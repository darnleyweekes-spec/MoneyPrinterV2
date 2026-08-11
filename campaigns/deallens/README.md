# DealLens Growth Overlay

This directory configures MoneyPrinterV2 as the distribution layer for DealLens without coupling the DealLens product code to the AGPL automation repository.

## Revenue target

Primary offer: **DealLens Express — $1,500 per deal, no subscription.**

Primary conversion path:

1. Target qualified acquisition professionals.
2. Send concise outbound or publish educational content.
3. Route prospects to the DealLens landing page.
4. Route interested prospects to the redacted sample.
5. Close a paid Express engagement.

Landing page: https://darnleyweekes-spec.github.io/jarvis-workforce-hq/deallens/

Sample: https://darnleyweekes-spec.github.io/jarvis-workforce-hq/deallens/sample.html

## Existing MoneyPrinterV2 capabilities used

- `src/classes/Outreach.py`: prospect discovery and email outreach.
- `src/classes/Twitter.py`: niche-specific X content generation/posting.
- `src/classes/YouTube.py`: short-form video generation and upload.
- `src/classes/PostBridge.py`: optional short-form cross-posting.

## Setup

Start with the normal repository setup and preflight flow. Do not commit credentials.

Copy the DealLens HTML message into the outreach message path you configure locally. Configure the Google Maps scraper niche around one qualified buyer segment at a time, for example:

- independent sponsor
- private equity firm
- search fund
- family office acquisitions
- M&A advisory firm

For X, use a topic such as:

`lower middle market acquisition diligence, independent sponsors, search funds, CIM analysis, customer concentration, revenue quality, working capital, DealLens`

For YouTube Shorts, use the scripts in `content_bank.md` as the editorial queue. Keep claims educational and do not imply DealLens replaces professional diligence.

## Daily operating cadence

- 20 qualified outbound prospects.
- 3 X posts.
- 1 Short.
- Review replies and site/sample interest.
- Follow up on day 2 and day 5.
- Stop automated follow-up when a prospect replies; handle the conversation manually.

## Metrics

Track: prospects contacted, delivery failures, replies, positive replies, sample requests, calls/opportunities, paid Express deals, revenue.

At $1,500 per engagement, one closed Express deal produces $1,500 gross revenue. Do not optimize for follower count; optimize for qualified conversations and paid deals.

## Guardrails

Use public business contact information, honor opt-outs, avoid deceptive personalization, do not fabricate prospect facts, and keep investment conclusions human-reviewed.
