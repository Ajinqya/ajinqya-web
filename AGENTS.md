# AGENTS.md

Guidance for AI agents and human collaborators working in this repository.

## Project Identity

Workbench is the internal codename for Ajinkya Gajbhiye's long-term personal digital ecosystem.

The first product inside Workbench is `ajinqya.com`. It should not feel like a generic portfolio; it should feel like a living product and growing archive of what Ajinkya designs, builds, writes, thinks about, learns, creates, and shares.

Treat this repository like a long-term software product, not a disposable website scaffold. The public expression may be personal, but the engineering and documentation should be calm, durable, and intentional.

## Current Phase

The repository is in a documentation-first foundation phase.

- Do not add Next.js, React, frontend framework code, package managers, or build tooling unless explicitly requested.
- Prefer creating and refining product documentation before implementation.
- Use placeholders where decisions are not ready yet.

## Collaboration Style

- Preserve the user's wording and intent where it exists.
- Make small, coherent changes.
- Avoid broad refactors or speculative structure.
- Before significant architecture decisions, explain the options, tradeoffs, and recommendation.
- Challenge ideas when a simpler, clearer, or more maintainable approach is likely better.
- Keep docs readable to a future version of the project, not just the present task.

## File Conventions

- Use Markdown for product and architecture notes.
- Keep headings concise and scannable.
- Prefer plain language over process jargon.
- Use `TODO:` placeholders for intentionally unresolved decisions.
- Record notable changes in `docs/changelog.md`.

## Product Priorities

Workbench should eventually support:

- A personal homepage and identity surface.
- A living archive of product design, visual design, motion design, software, AI experiments, music, writing, resources, and personality.
- A design language that feels editorial, product-like, timeless, minimal, warm, interactive where appropriate, and carefully crafted.
- A maintainable technical foundation.

The goal is not self-promotion. The goal is to build something genuinely useful and enjoyable to explore.

## Engineering Philosophy

- Optimize for long-term maintainability.
- Build systems instead of isolated pages.
- Prefer composition over duplication.
- Make content structured, reusable, and indexable.
- Avoid over-engineering; tooling should earn its complexity.

## Guardrails

- Do not create application code until the user asks for it.
- Do not introduce external services or dependencies without a clear reason.
- Do not default to trendy portfolio layouts or generic SaaS aesthetics.
- Do not overwrite user-authored content casually.
- Do not treat temporary placeholders as final decisions.

## Verification

For documentation-only changes, verify by checking file presence and reviewing Markdown structure. When application code is introduced later, add appropriate build, lint, test, and preview steps here.
