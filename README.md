<!--
  This is the Virge.io GitHub organization profile README.
  To make it render on https://github.com/virge-io, place this file at:
      .github/profile/README.md
  inside a repository named `.github` in the virge-io organization.
-->

<h1 align="center">Virge.io</h1>

<p align="center">
  <strong>Software solutions that scale.</strong><br>
  Expert consulting and products across AI, Software Defined Networking, and eCommerce.
</p>

<p align="center">
  <a href="https://www.virge.io/en/">🌐 virge.io</a>
  &nbsp;·&nbsp;
  <a href="https://shopvirge.com/en/">🛒 shopvirge.com</a>
</p>

---

## About

Virge.io is a technology consulting and product company that helps businesses build
**resilient, future-proof technology**. We work across three core practices, and ship
open source along the way.

### 🤖 AI

Moving clients *beyond prototypes to production-ready AI systems that deliver measurable
results.*

- **Vector Database Search:** semantic search that finds meaning, not just keywords.
- **RAG Pipeline Development:** grounding LLMs in your data to reduce hallucinations and deliver accurate, context-aware answers.
- **AI Application Integration:** intelligent APIs and automation embedded into existing stacks, no full rebuild required.
- **Production-Ready Solutions:** proper evaluation and monitoring, not demo-ware.
- **OpenClaw:** custom AI assistants with deployment, hosting, security, and automation.

### 🌐 Software Defined Networking

Treat *your network like software.* Network automation built on the open-source
**Workflow Orchestrator (WFO)** and battle-tested tooling.

- **Network as code:** model products, services, subscriptions, and workflows declaratively.
- **Integration & implementation:** delivered WFO projects for large corporates and service providers, from architecture to production.
- **System connectivity:** the "glue" between WFO and Netbox (IPAM/DCIM), Ansible (device config), and proprietary APIs.
- **DevOps for networking:** version-controlled configs, repeatable deployments, automated provisioning.
- **Workshops:** hands-on training on WFO architecture, workflow development, and automation at scale.

### 🛒 eCommerce

*Modern, flexible eCommerce solutions* with speed-to-market that skips lengthy
development cycles.

- **ShopVirge:** an ad-hoc webshop system for launching fully operational stores fast; ideal for new brands, pop-ups, and market validation.
- **Content as a Service:** give us a product name and AI delivers rich descriptions, images, and metadata.
- **Integrations & APIs:** connect to ERP, CRM, order fulfillment, and marketing platforms.
- **eCommerce consultancy:** platform choices, system design, payments, and growth strategy.

---

## Open source: ShopVirge Backend

Our flagship open-source project is
[`shopvirge-backend`](https://github.com/virge-io/shopvirge-backend), the engine behind
**[ShopVirge](https://shopvirge.com/en/)**: a headless, multi-tenant eCommerce platform
for launching multilingual webshops in minutes. *Your webshop, in any language, in
minutes.*

The FastAPI backend exposes a REST API for managing shops, products, categories, orders,
pricing, and customer accounts, with no vendor lock-in. The hosted product adds automatic
catalog translation, Stripe checkout (iDEAL, PayPal, cards), Excel/manual product import,
a mobile-first storefront, and MCP support so AI agents can manage products and
translations.

🛒 **Product:** [shopvirge.com](https://shopvirge.com/en/)
&nbsp;·&nbsp; 📖 **Docs:** [shopvirge.readthedocs.io](https://shopvirge.readthedocs.io/en/latest/architecture/overview/)
&nbsp;·&nbsp; 📦 **Repo:** [github.com/virge-io/shopvirge-backend](https://github.com/virge-io/shopvirge-backend)
&nbsp;·&nbsp; ⚖️ **License:** Apache-2.0

### Highlights

- **Multi-tenant by design:** resources are shop-scoped via routes like `/shops/{shop_id}/products`, isolating each merchant's data.
- **Layered architecture:** clean separation across entry point, routing, CRUD, models, schemas, security, and settings.
- **Built-in translations:** per-language variants for products, categories, tags, and attributes.
- **Payments:** native Stripe integration for transaction processing.
- **Transactional email:** Jinja2-templated, multi-language messaging over SMTP.
- **Media storage:** AWS S3 for assets.
- **Auth:** AWS Cognito with JWT, plus API-key auth and an MCP endpoint (`/mcp`) for agents.
- **Observability:** Sentry error tracking; Alembic migrations run on startup.

---

<p align="center">
  Interested in working together? Visit <a href="https://www.virge.io/en/">virge.io</a>. 
  Or interested in a webshop visit  <a href="https://shopvirge.com/en/">shopvirge.com</a>
</p>
