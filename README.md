# ermaocyber.github.io

This repository hosts my personal website via **GitHub Pages**.

Live site:  
https://ermaocyber.github.io

---

## About

This is a deployment repository containing the **production build** of the website.

The actual source code is developed in a separate React project:

https://github.com/ErmaoCyber/portfolio

After building the site, the generated static files are copied here so GitHub Pages can serve them publicly.

---

## How it works

1. Develop the website in the `portfolio` repository (React + Vite)
2. Run:

```bash
npm run build
```

3. Copy the contents of `dist/` into this repository
4. Push to GitHub → the website updates automatically

---

## Notes

This repository only contains static files (HTML, CSS, JS).  
For implementation details, please refer to the source repository above.