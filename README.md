# Per4an — Website Redesign

A responsive Indonesian editorial homepage for Per4an.

## Deploy on Cloudflare Pages (GitHub integration)

1. Open https://dash.cloudflare.com/ and sign in.
2. Go to **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Select the GitHub repository **yusufads2026/per4an**.
4. Set the production branch to `main`.
5. This is a static HTML site: leave the build command empty and set the build output directory to `/` if accepted by the dashboard. If the dashboard rejects the repository root as an output directory, create a `public` folder and move `index.html` into it, then set the output directory to `public`.
6. Click **Save and Deploy**. Cloudflare will provide the actual `*.pages.dev` URL after the deployment succeeds.

## Domain later

When you own/configure `per4an.com`, open the Pages project → **Custom domains** → **Set up a custom domain** and follow Cloudflare's DNS instructions.

## Notes

- The redesign is a fresh homepage; old Per4an article links are linked as references and may change.
- Images currently use remote Unsplash image URLs.
- No domain has been configured by this repository.
