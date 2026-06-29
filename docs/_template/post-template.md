---
blog:
  # Set to true to publish this doc to the blog. Leave false for drafts/notes.
  publish: false
  # URL slug + output filename. Lowercase letters, digits, single hyphens only
  # (must match ^[a-z0-9]+(?:-[a-z0-9]+)*$).
  slug: my-aws-post
  title: "My AWS Post Title"
  description: One-sentence summary used for the post preview and meta description.
  # Fallback date. The blog prefers the file's latest git commit date.
  date: 2026-06-29
  tags:
    - aws
    - cloud
---

# My AWS Post Title

Write the post here in Markdown. The leading H1 above is stripped on publish,
so it's fine to keep it for readability while editing locally.

Copy this file to `docs/<topic>/<your-slug>.md`, flip `publish` to `true`, and
the next blog sync will pick it up.
