# Angela Anderson — Portfolio

A clean black-and-white portfolio website for public relations, media relations, and storytelling. Built with plain HTML, CSS, and JavaScript: **no npm, build tools, Wix, or paid hosting required**.

## Publish with GitHub Pages (no coding required)

1. Sign in to [GitHub](https://github.com) and create a **new public repository**. Suggested name: `angela-portfolio` (or use `<your-username>.github.io` to publish at the root of your GitHub Pages domain).
2. Unzip `angela-anderson-github-pages.zip` on your computer. **Do not upload the ZIP itself**; GitHub needs the files inside.
3. Inside the new repository, choose **Add file → Upload files**. Upload the files and `samples` folder *contents with their folder structure intact*. The `index.html` file must be at the repository root, not inside an extra folder. Commit the upload to `main`.
   - For some browsers, dragging the entire unzipped folder into GitHub may create an extra nested folder. Check that your repository's first level shows `index.html`, `work.html`, `writing.html`, `experience.html`, `styles.css`, `script.js`, and `samples/`.
   - If the browser uploader doesn't preserve folder paths, use GitHub Desktop, which is easier for uploading a full website folder.
4. Go to **Settings → Pages → Build and deployment**. Set **Source** to **Deploy from a branch**, branch **main**, folder **/(root)**, and click **Save**.
5. When deployment completes, visit `https://<your-username>.github.io/angela-portfolio/` (or `https://<your-username>.github.io/` for a username.github.io repository).

GitHub's official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Pages

- `index.html`: Home / About / selected work
- `experience.html`: Experience / education
- `work.html`: Media campaigns, articles and TV coverage
- `writing.html`: Writing / pitch samples
- `styles.css`: Black-and-white visual design
- `script.js`: Navigation on smaller screens
- `samples/`: Portfolio previews and supplied PDFs

## Edit the website

- To change text: edit the corresponding `.html` file; GitHub's pencil icon works for small edits.
- To change colors, typography, or spacing: edit `styles.css`.
- To add a project: copy an `<article class="case">` section in `work.html`, change the title, description, image, and links.
- To add a writing sample: edit `writing.html` and upload the matching document in `samples/`.
- To link a file: use a **relative link**, such as `samples/your-file.pdf`, so it works under your repository name.
- To update the site after it's live: commit updates to `main` and GitHub Pages redeploys automatically.

## Privacy and publishing check — IMPORTANT

**This version retains user-provided PDF samples that may contain real email messages, personal email addresses, or other contact information. Everything committed to a public GitHub repository and published through GitHub Pages can be accessed by the public.** Before creating a public repository, review every PDF in `samples/`; redact private details, remove files that should not be public, and update any corresponding website links. Removing a file after publishing does not necessarily remove it from Git history. If you prefer, keep the original correspondence offline and publish only redacted versions or links to the resulting articles.

Article links point to independent publishers, whose headlines, images, and content belong to their respective owners. The portfolio describes Angela's PR and media outreach contribution rather than claiming authorship of journalists' stories.

## Troubleshooting

- **404?** Confirm `index.html` is in the root and Pages is publishing from `main` + `/(root)`.
- **No styling or missing samples?** Don't move files or add a folder around them; relative paths need to stay intact.
- **Updates not visible?** Check the repository **Actions** tab for the Pages deployment result, then reload.
- **Can I use my own domain?** Yes; set it in **Settings → Pages → Custom domain** and follow GitHub's DNS instructions.
