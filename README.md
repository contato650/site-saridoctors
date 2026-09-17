# Site institucional — Dra. Sarina

Site no ar em https://drasarina.com.br (projeto Vercel `site-saridoctors`, team contato-9590s-projects).

## Origem deste repositório

Estes arquivos foram **recuperados do deploy publicado na Vercel** em 29/07/2026
(deployment `dpl_6drdyBD82egDBe8KxsY6oobeqsPw`, commit local `a538032`
"feat(nav): logo do nav mostra apenas o simbolo S", branch `feat/animations`).

O repositório original `contato650/site-saridoctors` nunca chegou ao GitHub
(os deploys foram feitos via Vercel CLI a partir de uma pasta local em outra
máquina, com commits de ENRICO ROLIM <enricorolimcouto@gmail.com>).
Este repo é um backup fiel do que está em produção; o histórico git original
permanece apenas na máquina onde o site foi desenvolvido — se ela for
localizada, prefira fazer push do repositório original por cima deste.

## Estrutura

- `index.html` — página única do site (CSS embutido)
- `support.js` — runtime JS do site
- `uploads/` — imagens (fotos, logos)

Site 100% estático: basta servir a pasta (ex.: `vercel deploy` ou GitHub Pages).

## Blog em /blog (17/09/2026)

`vercel.json` reescreve `/blog`, `/blog/*`, `/_next/*` e `/brand/*` para o
projeto do blog (`blog-sarina`, repo `contato650/Blog-sarina`), então
drasarina.com.br/blog é o blog da Dra. Sarina sem trocar de domínio. O
`robots.txt` aponta o sitemap do blog e bloqueia `/blog/previa/` (prévias
internas do CRM). Menu e rodapé ligam ao blog, à SariDoctors
(saridoctors.com.br) e à Pós (pos.saridoctors.com.br).
