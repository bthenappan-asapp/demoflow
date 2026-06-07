# test

## How to Publish an HTML File to a Webpage Using GitHub Pages

Follow these steps to publish your HTML file as a live webpage using GitHub Pages:

### Step 1 – Create or add your HTML file

Add your HTML file to this repository. The main page should be named `index.html` and placed in the root of the repository (or in a `/docs` folder — see Step 3).

### Step 2 – Commit and push your changes

```bash
git add index.html
git commit -m "Add HTML file"
git push origin main
```

### Step 3 – Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click the **Settings** tab.
3. In the left sidebar, click **Pages**.
4. Under **Source**, select the branch you want to publish from (e.g. `main`).
5. Choose the folder: **/ (root)** if your `index.html` is in the root, or **/docs** if it is inside a `docs/` folder.
6. Click **Save**.

### Step 4 – Access your live webpage

After saving, GitHub will display a banner with your site's URL in the form:

```
https://<your-username>.github.io/<repository-name>/
```

It may take a minute or two for the site to become available after you first enable Pages.

### Step 5 – Update your page

Whenever you push new changes to the selected branch, GitHub Pages will automatically rebuild and republish your site within a few minutes.

---

A sample [`index.html`](index.html) is included in this repository as a starting point.