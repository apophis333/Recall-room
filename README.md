# Recall Room

A focused, local-first memory practice app for turning notes into recallable knowledge. It is a dependency-free static site, so it can be published directly with GitHub Pages.

## Features

- Dashboard with due cards, learned cards, collections, streak, and recent activity
- Passage-first memorization records with title, language, description, and full text
- Nested folders with memorisations and unlimited child folders
- Three practice stages: Familiarize, Solidify, and Evaluate
- Ten practice games: Tap to Reveal, Slider, Listen, First Letter, Blanks, Scramble, Type It, Multiple Choice, Speak, and Run Scene
- Self-rating with real next-review timestamps for Needs work, Getting there, Solid, and Nailed it
- Progress dashboard with review history, mastery, and streak insights
- Reference-style How It Works method guide and three-column practice map
- Local study groups with shareable invite codes
- Free feature comparison with no locked modes or artificial limits
- Searchable library with JSON export and JSON, Markdown, or Q/A text import
- Keyboard shortcuts for reveal, rating, and help
- Local browser persistence through `localStorage`
- Local workspace sign-in profile with sign-out
- Light and dark appearance
- Responsive layout for mobile and desktop

## Run locally

Open `index.html` in a browser. No build step or package install is required.

## Publish with GitHub Pages

1. Create a GitHub repository and push these files to its default branch.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
4. GitHub will provide the published URL after the Pages deployment finishes.

This project is intentionally original and uses no paid service or account backend. Data stays in the browser unless you export it. It is a static GitHub Pages site, so there are no subscriptions, locked features, or server costs.

The account panel includes a Google OAuth connection point, but real Google authentication and cloud sync require a provider project such as Firebase or Supabase plus its public configuration. The local account profile works immediately without a backend.
