# Quarryline open-tooling catalog

Source content for the public Quarryline catalog site.

Every catalog entry is a Markdown file under `content/items/`.  Its YAML front
matter records the title, a short summary, the category, whether the entry is
published, and an optional `link` to the entry's companion code repository.

Published entries (`published: true`) are rendered on the site.  Draft entries
(`published: false`) are not rendered and are excluded from catalog maintenance.

The `link` field, when present, must point to a companion repository under our
own account whose implementation has actually shipped.  A repository that only
announces future work, or that still consists of planning material, does not
qualify.  Links to copies under other accounts are never acceptable.
