# InsightfulPipe E-commerce Skills

**23 free Claude skills for online stores and marketplaces: store reports, promotions, AOV, bundles, inventory, returns, profit on ad spend, Amazon Ads, TikTok Shop and Etsy.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/ecommerce-skills
/plugin install insightfulpipe-ecommerce@insightfulpipe-ecommerce
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/ecommerce-skills
```

Add `--skill amazon-ads-audit` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (23)

| Skill | What it does | |
|---|---|---|
| [Amazon Ads Audit](skills/amazon-ads-audit/) | Audits an Amazon Ads account (Sponsored Products, Brands, Display, DSP) from your exports against each product's break-even ACOS, with TACOS, brand split, wasted search… |  |
| [Amazon PPC Bid Optimizer](skills/amazon-ppc-bid-optimizer/) | Sets Amazon Sponsored Products keyword, product target and placement bids to hit a target ACOS or TACOS, in capped weekly steps with a bulk file to upload. |  |
| [Amazon PPC Campaign Builder](skills/amazon-ppc-campaign-builder/) | Builds the Amazon PPC structure for a new product or book, with exact, phrase, broad, auto, competitor ASIN and brand defense campaigns, bids from break-even ACOS and a… |  |
| [Amazon Search Term Harvester](skills/amazon-search-term-harvester/) | Runs the weekly Amazon search term harvest, moving converting terms into exact match, adding negative and cross-campaign negative keywords and spotting competitor… |  |
| [Average Order Value Optimizer](skills/aov-optimizer/) | Finds how to raise average order value from Shopify, WooCommerce or Magento orders, pricing shipping thresholds, gift with purchase, tiers, add-ons and code minimums in… |  |
| [Competitor Price Tracker](skills/competitor-price-tracker/) | Tracks a store's prices against named competitors and Amazon sellers by matched GTIN, compares landed prices and promotions, and sets match, beat, premium or hold… |  |
| [Cross-Border Store Setup Planner](skills/cross-border-store-expansion/) | Sets up a store to sell in countries already chosen, pricing each market on landed cost with duty, VAT and currency fees, plus shipping rates, local payments… |  |
| [Discount and Promotion Analyst](skills/discount-promo-analyst/) | Measures discount codes and sitewide sales from a store's own orders, showing margin given away, who used each code, codes leaked to coupon sites and whether a sale… |  |
| [Ecommerce Ads Playbook](skills/ecommerce-ads-playbook/) | Plans ecommerce ads across Google Shopping, Performance Max, Meta catalog and TikTok with budgets and margin-checked ROAS, and audits a Shopify, WooCommerce or Magento… | [Page](https://insightfulpipe.com/marketing-claude-skills/playbooks/ecommerce-ads-playbook) |
| [Ecommerce Store Report](skills/ecommerce-store-report/) | Builds the weekly or monthly sales report from a store's orders (Shopify, WooCommerce, Magento), with net sales, AOV, new and returning buyers, channels, countries and… |  |
| [Etsy SEO and Shop Audit](skills/etsy-shop-optimizer/) | Audits an Etsy shop from its listings CSV and Stats, ranking the listings that lose the most orders and checking tags, titles, photos, price, shipping and shop pages. |  |
| [Marketplace Expansion Planner](skills/marketplace-expansion-planner/) | Plans which marketplaces to sell on next (Amazon, Walmart, eBay, Etsy, TikTok Shop) from each product's margin after fees, channel rules, demand and MAP conflicts, with… |  |
| [Online Store Launch Checklist](skills/store-launch-checklist/) | Checks a new store before launch, marking each item pass, fail or unknown with evidence across domain, policies, payments, taxes, shipping, products, GA4, speed, email… |  |
| [Product Bundle and Cross-Sell Builder](skills/bundle-cross-sell-builder/) | Runs market basket analysis on a store's orders to find products bought together, then prices bundles against margin and plans pairs well with picks, post-purchase… |  |
| [Product Merchandising Analyst](skills/product-merchandising-analyst/) | Ranks a store's products and collections on GA4 item views, add-to-cart rate, purchase rate and margin, then picks home page products, sorts each collection and flags… |  |
| [Profit on Ad Spend (POAS) Report](skills/poas-profit-report/) | Calculates profit on ad spend (POAS) next to ROAS per campaign, product group and product for Google Ads, Meta, TikTok and Pinterest, from a store's own costs, fees and… |  |
| [Repeat Purchase and Subscribe-and-Save Planner](skills/repeat-purchase-planner/) | Plans how a store turns first-time buyers into repeat buyers from its own orders, finding gateway products, reorder intervals, subscribe and save candidates and refill… |  |
| [Retail Media Planner (Walmart, Instacart, Target)](skills/retail-media-planner/) | Compares retail media beyond Amazon (Walmart Connect, Instacart Ads, Target Roundel) by rebuilding every network's ROAS on one attribution scale against break-even… |  |
| [Returns and Refunds Analyst](skills/returns-refunds-analyst/) | Analyses a store's returns and refunds from Shopify, WooCommerce or Magento orders, finding which products, sizes, campaigns and discount codes return most and why, and… |  |
| [Stock-Out and Excess Inventory Planner](skills/inventory-planner/) | Plans marketing around stock, with days of cover and reorder-by dates per variant, holding low stock out of Shopping, Performance Max, Meta catalog ads and emails, and… |  |
| [Store Site Search Analyst](skills/store-site-search-analyst/) | Analyses a store's GA4 or Shopify site search terms against its catalogue, classing failed searches as misspellings, synonyms, sold out or not carried, and ranks fixes… |  |
| [TikTok Shop GMV Max Planner](skills/tiktok-shop-gmv-max-planner/) | Plans and reviews TikTok Shop GMV Max ads, setting ROI targets from product margins, grouping products into campaigns, ramping budgets and giving weekly scale, fix or… |  |
| [TikTok Shop Launch and Growth Planner](skills/tiktok-shop-planner/) | Plans a TikTok Shop launch or growth push, picking hero products and setting launch prices, affiliate commission, creator samples and a LIVE schedule from each… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
