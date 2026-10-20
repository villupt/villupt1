# Skill Commons

A free skill-sharing hub for newsletter readers. It includes mentor discovery, a skill swap board, learning sprints, community Q&A, and copy-ready Substack launch content.

## Try it

Open the live app at [https://villupt.github.io/villupt1/](https://villupt.github.io/villupt1/).

## Data and privacy

This is a static app. In this deployment, board posts and learning progress are stored in the visitor's own browser using local storage. They are not shared with other readers and do not sync across devices. A shared public board needs a backend with authentication and moderation.

## Deploy

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root to GitHub Pages on pushes to `main`. Enable **Settings → Pages → Build and deployment → GitHub Actions** if Pages is not already enabled.
