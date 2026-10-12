# Polytrack Timing Tower

This folder contains the static website for GitHub Pages.

## Publish it on GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `polytrack-timing-tower` (or another name you like).
2. On the repository page, choose **Add file → Upload files**.
3. Upload `index.html` from this folder and commit the changes.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Set the branch to `main` and folder to `/(root)`, then click **Save**.
7. Wait a minute or two. GitHub will show the published website URL in Settings → Pages.

If the repository is named `YOURNAME.github.io`, the URL is usually `https://YOURNAME.github.io/`.
For a repository named `polytrack-timing-tower`, the URL is usually `https://YOURNAME.github.io/polytrack-timing-tower/`.

## Important current limitation

This is the first, static prototype. It imports the track data and supports local submissions/review, but saves changes in the current browser's local storage. It does **not** yet synchronize times between people or devices, and the local review flow is not secure. GitHub Pages hosts static files; shared records require a separate database and proper authentication/permissions. Do not treat the prototype's review controls as a secure admin system.

## Updating the website

Edit `index.html`, then upload the updated file to the repository and commit the change. GitHub Pages will redeploy it automatically.
