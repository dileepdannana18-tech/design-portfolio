# Design portfolio site

A responsive, static portfolio for the three public project demos. It uses plain HTML and CSS, has no paid dependencies, build step, analytics, or external image assets. The abstract project covers are original CSS illustrations, not screenshots of the deployed apps.

## Before publishing

Add the portfolio owner's preferred name and a direct public contact method when available. The current contact section refers fellowship readers to the contact details on the application, because no email address or profile link was supplied. The project descriptions intentionally stay within what is visible in the live demos.

## Publish with GitHub Pages (free)

1. Sign in to GitHub and create a new **public** repository, for example `design-portfolio`.
2. Upload `index.html` from this folder to the repository's top level (the file should be at `design-portfolio/index.html`, not inside another folder).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then save.
5. Wait for the Pages link to appear on that screen. Open it in a private/incognito window to confirm it is publicly accessible. The URL is usually `https://YOUR-GITHUB-NAME.github.io/design-portfolio/`.

## Publish with Vercel (free static site)

1. Create a GitHub repository and put `index.html` at its top level as above.
2. Sign in to Vercel and choose **Add New → Project**, then import that GitHub repository.
3. Select **Other** as the framework preset. Leave the build command empty and set the output directory to `.` if Vercel requests one.
4. Choose **Deploy**. Vercel will provide a public URL; open it in a private/incognito window to check it.

After editing the contact section or other details, upload the changed `index.html` to the same repository; GitHub Pages or Vercel will publish the update automatically.


