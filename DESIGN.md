# DESIGN.md

# Profile Repository Design

## Boundary

This repository exists to publish the account profile README. It is deliberately a content artifact rather than an application. README.md is the rendered public surface.

## Core decisions

- Keep the repository minimal: GitHub renders the root README for the associated profile, so no site generator, deployment pipeline, or duplicate profile source is needed.
- Treat repository-list and profile content as public-facing claims. Changes should be concise and reviewable because this is an identity surface, not a development sandbox.

## Constraints

There is no runtime architecture to preserve. Add infrastructure only if the profile’s publishing mechanism genuinely changes.


