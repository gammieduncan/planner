# Planner

A small, content-free web app shell. It holds no data of its own: on load it asks for a
GitHub personal access token and then reads/writes everything from a separate **private**
repository through the GitHub API. Without a valid token it shows only a locked screen.

This repo exists purely to host the static page on GitHub Pages. All actual content and data
live in the private data repo and are never exposed here.
