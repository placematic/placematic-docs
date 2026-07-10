# Placematic Developer Hub

> Practical implementation guidance for HERE Location Services.

This repository contains the source code for **https://docs.placematic.com**.

The goal is **not** to recreate the official HERE documentation.

Instead, this project explains **how to successfully design, build and operate production geospatial systems** using HERE Location Services.

---

# Philosophy

The official HERE documentation already explains:

- endpoints
- parameters
- schemas
- authentication

This documentation explains everything around the API:

- choosing the right HERE service
- architecture decisions
- migration from Google Maps
- production deployment
- cost optimization
- enterprise implementation
- common engineering mistakes
- real-world use cases

Think of it as the missing implementation guide between the HERE documentation and a production deployment.

---

# Repository Structure

```
getting-started/
    Platform overview
    Authentication
    Pricing
    Choosing APIs

guides/
    API implementation guides

use-cases/
    Business problems and solution architectures

architecture/
    Production architecture patterns

examples/
    Production-ready code examples

comparisons/
    HERE vs Google, Mapbox, TomTom...

faq/
    Frequently asked engineering questions
```

---

# Documentation Principles

Every page should follow these rules.

## Be practical

Write for engineers.

Avoid marketing language.

Show implementation guidance.

---

## Never duplicate HERE documentation

Do not rewrite parameter tables.

Do not copy response schemas.

Instead explain:

- why
- when
- architecture
- trade-offs

Always link to the official HERE documentation where appropriate.

---

## Never invent technical information

Do not invent:

- endpoints
- request parameters
- authentication methods
- response payloads
- pricing
- API limits
- SLAs
- benchmark numbers

When unsure:

- verify
- or omit

Accuracy is more important than completeness.

---

## Be honest

Recommend competitors when appropriate.

Examples:

- Google for consumer place search
- Mapbox for advanced map styling
- OpenStreetMap when infrastructure ownership is acceptable

Trust converts better than marketing.

---

# Audience

This documentation is written for:

- CTOs
- Software Architects
- Engineering Managers
- Senior Developers
- Product Teams
- SaaS founders

It is **not** beginner documentation.

---

# Documentation Sections

## 🚀 Getting Started

How HERE works.

How licensing works.

How to choose the right APIs.

---

## 📚 Guides

Implementation guides for individual HERE services.

Example:

- Routing
- Geocoding
- Matrix
- Truck Routing
- Tour Planning

---

## 🏗 Solutions

How complete products are built.

Examples:

- Fleet platforms
- Store locators
- Delivery zones
- Restaurant delivery
- Field service

---

## 🧠 Architecture

Production engineering guidance.

Examples:

- Routing vs Matrix
- Caching geocoding
- Cost optimization
- High-volume geocoding
- Multi-tenant SaaS

---

## 💻 Examples

Production-ready code examples.

Focus on complete workflows rather than isolated API calls.

---

## ⚖ Comparisons

Technical platform comparisons.

Examples:

- HERE vs Google Maps
- HERE vs Mapbox
- HERE vs TomTom

The goal is technical decision-making rather than marketing.

---

## 💬 FAQ

Answers to real engineering questions.

Questions should reflect what developers ask ChatGPT and search engines.

---

# Writing Style

Prefer:

- concise
- technical
- practical
- opinionated when supported by experience
- architecture-focused

Avoid:

- buzzwords
- marketing copy
- generic statements
- unsupported claims

---

# AI Contribution Guidelines

AI-generated content is welcome.

However, every generated page must satisfy the following requirements before being merged:

- Technical claims are verified.
- Official HERE endpoints are used.
- No fabricated APIs.
- No invented performance numbers.
- No invented pricing.
- No invented customer stories.
- No copied content from HERE documentation.

The goal is to create documentation that developers trust enough to reference in production systems.

---

# Internal Linking

Every page should link to related:

- Guides
- Use Cases
- Architecture
- Examples
- Comparisons
- FAQ

The documentation should behave as a connected knowledge graph rather than isolated articles.

---

# Sources

Primary source:

- Official HERE documentation

Secondary sources:

- Placematic implementation experience
- placematic.com
- Verified vendor documentation

Never rely on memory for technical details.

---

# Updating Documentation

Before publishing:

- Verify endpoints
- Verify parameters
- Verify authentication
- Verify pricing references
- Verify product names
- Verify API limits
- Verify internal links

If something cannot be verified:

Do not publish it.

---

# Goal

The objective of this project is to build the best public implementation resource for HERE Location Services.

Not the biggest.

Not the most verbose.

The most useful.

If an experienced software architect finishes reading a page and learns something they did not know before, the page has achieved its purpose.