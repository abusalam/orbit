# Orbit

Orbit is a self-contained, mobile-friendly spinner. Swipe up or down to spin the wheel; faster swipes give it more momentum. Use the fullscreen button for an immersive view. You can also use the up and down arrow keys or Space.

## Run locally

Open `index.html` in a browser. The page has no build step or external dependencies.

## Configure the wheel

Open the settings view by adding `?opt` to the page URL (for example, `index.html?opt`). Choose from 2 to 16 wheel colors and select **Save settings**. The choice is stored in that browser's local storage and is used the next time you open the wheel. The default is 8 colors. The chosen colors appear in a randomized order each time the page loads, with labels aligned along each segment's radius.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site whenever changes are pushed to `main`, and can also be started manually from the repository's **Actions** tab.

1. Push this project to a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set the source to **GitHub Actions**.
4. Push to `main` or run the **Deploy to GitHub Pages** workflow.

The workflow publishes `index.html` as a static site. If your default branch is not `main`, update the branch in the workflow trigger to match.
