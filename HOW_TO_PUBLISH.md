# Add a new article — no HTML editing

The site uses **Jekyll collections** on GitHub Pages. Each Markdown file inside `_articles/` becomes an individual Knowledge Hub article, and it appears automatically in the Knowledge Hub and (if among the first three) on the home page.

## Steps in GitHub (web browser)

1. Open the repository `smileoptimisticstudio/smileoptimisticstudio.org.uk`.
2. If using a new illustration, open `assets/` → **Add file** → **Upload files**, then commit it. Give the file a simple name, e.g. `emotional-containment.jpg`.
3. Open `_articles/`, click **Add file** → **Create new file**.
4. Enter a unique filename in English using lowercase and hyphens, e.g. `emotional-containment.md`.
5. Paste the example below, replace title, text, image and order, and click **Commit changes**.
6. GitHub Pages publishes automatically if Pages is configured to build from the `main` branch. Visit `https://smileoptimisticstudio.org.uk/knowledge/` after deployment completes.

```markdown
---
title: "Emotional containment: staying alongside a child's feelings"
description: "How adults can support children when feelings are overwhelming."
category: "Children's emotional wellbeing"
kind: Article
image: "/assets/emotional-containment.jpg"
image_alt: "Gentle illustration of a supportive adult and child"
order: 6
---

Write your first paragraph here.

Write your second paragraph here.

## A subheading

More text goes here.
```

**Tips:** Keep the three dashes before and after the metadata. Don't add a public article before approving its medical, privacy and evidence claims. For existing articles `order` is 1–5, so use 6, 7, 8 etc. The home page currently shows the first three by order (not newest). To display the newest automatically later, add an explicit publication date and sort by it instead. You can revise or unpublish an article by editing or deleting its `.md` file in GitHub.
