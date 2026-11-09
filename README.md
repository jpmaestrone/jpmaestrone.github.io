# Juan Pedro Maestrone — personal website

A small static website for GitHub Pages. The content is in `index.html` and the styling is in `styles.css`; there are no dependencies or build steps.

## Preview locally

From this folder, run:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000> in a browser. Stop the server with Ctrl+C. You can also open `index.html` directly.

## Edit

Edit the text and links in `index.html` and the colors, spacing, and responsive styles in `styles.css`. The sections are marked with HTML IDs. Add a CV or personal photo only after reviewing and approving the file for public sharing; link to it with a relative path. No contact email or CV file is currently included.

## Publish when ready

1. Review the content and files for public release. Create a repository named `jpmaestrone.github.io` on GitHub, or use that repository if it already exists. GitHub Free requires a public repository for Pages.
2. Initialize and connect this folder to that repository if needed, then commit and push the reviewed files to a branch. If the remote already contains content, inspect it and reconcile histories first.
3. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select the branch and `/(root)` folder, and save. Wait for the deployment to finish.
4. Visit <https://jpmaestrone.github.io>. Later pushes to the selected source will update the site.

See [GitHub's Pages guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [publishing source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
