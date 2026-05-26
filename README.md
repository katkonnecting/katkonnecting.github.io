# KatKonnecting - Blog

A minimal, free blog hosted on GitHub Pages using Hugo.

## Features

- ✅ Free hosting (GitHub Pages)
- ✅ Automatic deployment (GitHub Actions)
- ✅ Clean, minimal design
- ✅ Write in Markdown
- ✅ Fast static site generation

## Quick Start

### 1. Install Hugo

Download from: https://gohugo.io/installation/

### 2. Test Locally

```bash
cd C:\Users\hamma\OneDrive\Documents\GitHub\katkonnecting.github.io
hugo server
```

Visit `http://localhost:1313` to preview your site.

### 3. Create New Posts

```bash
hugo new blog/my-post.md
```

Edit the file, then:

```bash
git add content/blog/my-post.md
git commit -m "Add: my-post"
git push
```

**Automatic deployment!** GitHub Actions builds and deploys on every push.

## Directory Structure

```
katkonnecting.github.io/
├── config.toml              # Site configuration
├── .github/workflows/
│   └── deploy.yml           # GitHub Actions workflow
├── content/
│   ├── blog/                # Blog posts
│   └── about/               # About page
├── layouts/                 # HTML templates
└── README.md                # This file
```

## Customization

- **Title/Author**: Edit `config.toml`
- **Colors**: Edit `layouts/_default/baseof.html` → `<style>` section
- **About page**: Edit `content/about/_index.md`

## Site Goes Live At

https://katkonnecting.github.io

## Custom Domain (Optional)

To use a free domain (e.g., `myblog.tk` from Freenom):

1. Register domain on https://freenom.com
2. Set Freenom nameservers to GitHub Pages IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Create file `static/CNAME` with your domain:
   ```
   myblog.tk
   ```
4. In GitHub repo → Settings → Pages → Custom domain: `myblog.tk`

## Resources

- Hugo Docs: https://gohugo.io/documentation/
- GitHub Pages: https://pages.github.com/
- Markdown Guide: https://www.markdownguide.org/

## License

Free to use and modify.
