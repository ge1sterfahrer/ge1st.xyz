# ge1st.xyz

Source for [www.ge1st.xyz](https://www.ge1st.xyz).

A static site with no build step. Everything under `public/` is the document root and can be uploaded to the host as-is.

```
public/
├── index.html
└── assets/
    ├── css/style.css
    └── fonts/
        ├── JetBrainsMono-Bold.woff2
        └── OFL.txt          # JetBrains Mono license (SIL OFL 1.1)
```

## Local preview

```sh
npx serve public
# or
python -m http.server -d public 8080
```
