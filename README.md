# kiarashminoo.com

Static personal portfolio website for GitHub Pages.

## Deploy to GitHub Pages

1. Create or use this repository:

```bash
KiarashMinoo/kiarashminoo.github.io
```

2. Copy all files from this folder into the repository root.

3. Commit and push:

```bash
git add .
git commit -m "Add personal portfolio website"
git push origin main
```

4. In GitHub:
   - Go to **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root

5. DNS for custom domain:

```txt
CNAME: kiarashminoo.com
```

For apex domain, configure these GitHub Pages A records at your DNS provider:

```txt
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

For www:

```txt
www CNAME KiarashMinoo.github.io
```

## Notes

- Replace `assets/profile.png` and `assets/profile.webp` with the final polished personal photo when needed.
- Add your actual CV as `assets/Ahmad-Kiarash-Minoo-CV.pdf` or change the Download CV links in `index.html`.
- The custom domain is stored in the `CNAME` file.
