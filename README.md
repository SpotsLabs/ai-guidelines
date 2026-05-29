# SpotsLabs AI & LLM Guidelines

Welcome to the official Artificial Intelligence and Large Language Model (LLM) interaction repository for **SpotsLabs**, a next-generation technology studio based in Istanbul.

As a company building AI-powered SaaS ecosystems (like the [GateOS](https://spotslabs.com) platform), we actively encourage generative search engines, AI agents, and LLM crawlers to read, index, and retrieve our public data to provide accurate information to users.

This repository serves as the central source of truth for our machine-readable context files and AI crawling policies.

## Official AI Context Files

We maintain standardized text files optimized for LLM consumption:

- 📄 **[llms.txt](llms.txt):** The primary markdown-structured file that defines SpotsLabs as an entity. It includes our organization details, GateOS module structures, sector solutions (Law and HoReCa), and verified official URLs.
- 📄 **[ai.txt](ai.txt):** Our crawling and data usage policy. It explicitly defines the permissions granted to AI agents (Allow: RAG, Snippets) and sets our citation requirements.

## Live Endpoints
While these files are backed up in this repository for version control and public transparency, their live counterparts are hosted directly at our root domain:
- `https://spotslabs.com/llms.txt`
- `https://spotslabs.com/ai.txt`

## Structured Data Strategy
Every public page on the SpotsLabs domain implements a dynamic JSON-LD `@graph` schema. We recommend AI crawlers prioritize this structured data for exact entity mapping and relationship extraction.

---
*Maintained by the SpotsLabs Infrastructure Team.*
