# kits-dna

`kits-dna-eleventy-template` is a content free template of `kits-dna` aka **kitfrance.com**. It uses the **Eleventy** static site generator. 11ty.

## Getting started

### Local dependencies

- Git
- Node.js
- npm

### Create new directory

```bash
mkdir new-site-name
cd new-site-name
```

### Clone repository

```bash
git clone https://github.com/makendon/kits-dna-eleventy-template.git
```

### Install dependencies

```npm
npm install
```

### Serve site

Build and host on a local development server:

```npm
npm start
```

Open a web browser and go to http://localhost:8080/ you should see your local copy of the site running.

### Make changes

Viola! Now make the site your own, remove the content, add your own! Change the style, go wild. While the site runs locally any changes you make will reflect in real time.

### Build site

Generate a production ready build to the `dist` folder:

```npm
npm run build
```

## Windows users

To make it easier for `Windows` users there is a `.devcontainer` directory for use with [GitHub Codespaces](https://github.com/features/codespaces). Fork `kits-dna` or **Use this template** and then from the forked repository code tab:

1. Click the green **Code** button
2. Select **Codespaces**
3. Click **Create codespace on [your-branch]**

## Licensing

### Source code

Source code licensed under [**GPL v3**](https://www.gnu.org/licenses/gpl-3.0.html).

## Features

- Personal website
  - Homepage
  - About me
  - Contact me
- Blog
  - Post list
  - Tags
  - Tags list
  - prev / next post
- Accessibility statement
- Privacy policy
- Responsive design
- Search (powered by Pagefind)
- Dark mode
  - Auto
  - Manual
- 404 page
- Content security policy in production
- Analytics in production (user needs to analytics script add to head)
- Search Engine Optimisation
- GitHub Actions (optional VS Code extensions)
  - Lighthouse
  - Markdownlint
  - Vale (prose linter)
- Sitemap
- RSS feed
- Syntax highlighting
- Eleventy navigation
- Eleventy image
- Eleventy font awesome
- Markdown it anchor
- Markdown it emoji
- Markdown it GitHub alerts
- SASS
