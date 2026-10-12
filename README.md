# gradnje.ai – spletna stran Atren gradnje d.o.o.

Statična predstavitvena stran, ena datoteka, brez zunanjih odvisnosti.

| Datoteka | Namen |
|---|---|
| `index.html` | celotna stran; pisava Archivo (OFL) in logotipi so vgrajeni, zato stran ne kliče nobenega tujega strežnika |
| `og-image.png` | slika ob deljenju povezave (WhatsApp, LinkedIn) |
| `favicon.ico` | ikona strani |
| `robots.txt`, `sitemap.xml` | za iskalnike |
| `CNAME` | domena za GitHub Pages |
| `.nojekyll` | GitHub Pages objavi datoteke brez obdelave |

## Objava
GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/ (root)`. Custom domain: `gradnje.ai`, Enforce HTTPS.

DNS pri registrarju domene:
- `gradnje.ai` A zapisi: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `www.gradnje.ai` CNAME: `<organizacija>.github.io`

## Obrazec
Obrazec za povpraševanje na GitHub Pages ne more pošiljati sam; obiskovalcu sestavi besedilo za kopiranje ali poštni program. Načrt: povezava na Supabase (app.gradnje.ai), da povpraševanja pridejo naravnost v sistem.

## Spremembe
Zamenjaj `index.html` in objavi commit; stran se posodobi v nekaj minutah.
