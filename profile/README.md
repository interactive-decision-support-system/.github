# Projects overview

This org builds the plumbing for AI shopping agents to transact with real e-commerce stores over Google's Universal Commerce Protocol (UCP): store-side connectors that open a shop to agents, a merchant dashboard for attribution and rule-based control over that agent traffic, and an agent-side server that shops those stores from inside Claude or ChatGPT.

The repositories below are grouped by the academic quarter in which their first commit landed.

## Spring 2026

- **[ucp-shopping-agent](https://github.com/interactive-decision-support-system/ucp-shopping-agent)** — Remote MCP server that turns a Claude or ChatGPT chat into a shopping agent for a UCP-enabled store. See [in-flight and backlog work](https://github.com/orgs/interactive-decision-support-system/projects/2/views/9) on the project board.
- **[ucp-woocommerce](https://github.com/interactive-decision-support-system/ucp-woocommerce)** — A monorepo in two parts: a **plugin** that brings Google's Universal Commerce Protocol to PHP-based e-commerce platforms (WooCommerce, PrestaShop, Magento), opening a store to AI-driven shopping on Google's surfaces (Gemini, Search AI Mode) with WooCommerce as the most mature prototype; and a **web app**, the hosted merchant dashboard giving attribution, analytics, and rule-based control over that agent traffic. See [in-flight and backlog work](https://github.com/orgs/interactive-decision-support-system/projects/2/views/3) on the project board.
- **[merchant-agent](https://github.com/interactive-decision-support-system/merchant-agent)** — Attempt to unify the idss-backend and idss-web work into a single merchant-agent platform, with some work toward automated enrichment of e-commerce catalogs; discontinued.

## Winter 2026

- [idss-web](https://github.com/interactive-decision-support-system/idss-web)
- [idss-mcp](https://github.com/interactive-decision-support-system/idss-mcp)
- [idss-backend](https://github.com/interactive-decision-support-system/idss-backend)
