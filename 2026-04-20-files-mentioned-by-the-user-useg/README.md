# Soymbo Site

GitHub дээр static site хэлбэрээр байршуулахад бэлэн багц.

Агуулга:
- `index.html`
- `robots.txt`
- `sitemap.xml`
- `manifest.webmanifest`
- `CNAME`

GitHub дээр оруулах:
1. Шинэ public repository үүсгэ.
2. Эдгээр файлуудаа repository руу upload хий.
3. `Settings` -> `Pages` руу ор.
4. `Deploy from a branch` сонго.
5. `main` болон `/root`-ийг сонго.

Домэйн:
- `soymbo.mn` ашиглах бол DNS-ээ GitHub Pages руу холбоно.
- `CNAME` файл аль хэдийн орсон.

Google:
- Site public болсны дараа Google Search Console дээр sitemap-аа submit хий:
- `https://soymbo.mn/sitemap.xml`
