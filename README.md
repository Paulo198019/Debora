# Debora Site

Site estático publicado via GitHub Pages com cache-busting em CSS/JS/Imagens.

## Estrutura
```
Novo_site/
├─ index.html
├─ style.css
├─ script.js
├─ assets/
│  └─ img/
│     ├─ banner.svg
│     ├─ perfil.svg
│     └─ favicon.svg
├─ update_version_all_html.py
└─ .github/workflows/deploy.yml
```

## Publicação
1. Configure **Settings → Pages → Source = GitHub Actions**.
2. Faça `git add -A && git commit && git push` na branch `main`.
3. O workflow fará o deploy e aplicará cache-busting com SHA do commit.
