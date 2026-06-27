# Content Model

This document describes the provisional content model for Workbench.

The goal is to identify the kinds of things the ecosystem may contain before choosing a storage format or application framework.

The guiding philosophy is simple: everything is content. Projects, notes, experiments, music, resources, videos, visuals, and software should all be represented by structured, reusable, indexable models.

## Core Content Types

### Page

Stable evergreen surfaces such as home, about, contact, or now.

Possible fields:

- `title`
- `slug`
- `description`
- `body`
- `status`
- `updatedAt`

### Post

Longer-form writing such as essays, reflections, notes, or announcements.

Possible fields:

- `title`
- `slug`
- `subtitle`
- `description`
- `body`
- `publishedAt`
- `updatedAt`
- `status`
- `tags`

### Project

A structured record of a product, project, case study, tool, design exploration, software build, or AI experiment.

Possible fields:

- `title`
- `slug`
- `summary`
- `role`
- `timeline`
- `status`
- `links`
- `technologies`
- `disciplines`
- `body`

### Experiment

A smaller build, prototype, sketch, AI exploration, interaction study, or technical trial.

Possible fields:

- `title`
- `slug`
- `summary`
- `body`
- `status`
- `disciplines`
- `technologies`
- `links`
- `createdAt`
- `updatedAt`

### Resource

A useful reference, guide, link, tool, template, or recommendation.

Possible fields:

- `title`
- `slug`
- `description`
- `url`
- `body`
- `resourceType`
- `tags`
- `createdAt`
- `updatedAt`

### Media

A music track, video, visual artifact, motion study, image set, or other creative asset.

Possible fields:

- `title`
- `slug`
- `description`
- `mediaType`
- `assets`
- `credits`
- `links`
- `publishedAt`
- `tags`

### Note

Shorter fragments, observations, references, or working thoughts.

Possible fields:

- `title`
- `slug`
- `body`
- `createdAt`
- `updatedAt`
- `tags`
- `related`

### Collection

A curated grouping of posts, notes, projects, links, or other artifacts.

Possible fields:

- `title`
- `slug`
- `description`
- `items`
- `updatedAt`

## Shared Metadata

Potential shared fields:

- `title`
- `slug`
- `description`
- `status`
- `visibility`
- `createdAt`
- `updatedAt`
- `publishedAt`
- `tags`
- `canonicalUrl`
- `related`
- `disciplines`
- `format`

## Status Values

Potential status values:

- `draft`
- `published`
- `archived`
- `hidden`

TODO: Decide whether status and visibility should be separate concepts.

## Open Decisions

- TODO: Decide whether content starts as Markdown, MDX, CMS data, database records, or another format.
- TODO: Define URL patterns.
- TODO: Define tagging and collection rules.
- TODO: Decide whether notes and posts are distinct or a single content type.
- TODO: Decide how private or unpublished content is represented.
- TODO: Decide how disciplines such as product design, visual design, motion design, software, AI, music, writing, and resources should be modeled.
