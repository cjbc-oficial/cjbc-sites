# CJBC Sites — Cloudflare Pages

Repositório com os sites da CJBC prontos para deploy no Cloudflare Pages.

## Estrutura

```
cjbc-cloudflare-pages/
  cjbc-institucional/     → cjbc.com.br
    index.html
    robots.txt
    sitemap.xml
    _redirects
    _headers

  cjbc-digital/           → digital.cjbc.com.br
    index.html
    robots.txt
    sitemap.xml
    _redirects
    _headers
    googlesiteexpress/
      index.html
    catalogodigital/
      index.html
    kitdivulgacao/
      index.html
    cartaodigital/
      index.html
```

## Deploy no Cloudflare Pages

### Projeto 1 — cjbc-institucional
1. Cloudflare Pages → Create a project → Connect to Git
2. Selecionar este repositório
3. **Root directory:** `cjbc-institucional`
4. Framework: None
5. Build: deixar em branco
6. Deploy!

### Projeto 2 — cjbc-digital
1. Cloudflare Pages → Create a project → Connect to Git
2. Selecionar este repositório
3. **Root directory:** `cjbc-digital`
4. Framework: None
5. Build: deixar em branco
6. Deploy!

## Domínios customizados

Após deploy, adicionar os domínios em cada projeto:
- Projeto 1: `cjbc.com.br`
- Projeto 2: `digital.cjbc.com.br`

O Cloudflare vai gerar os registros DNS automaticamente.

---

CJBC · Migração Hostinger → Cloudflare Pages · Março 2026
