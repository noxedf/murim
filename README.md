# Murim Login: Destinos e Sistema

Site estático (um único `index.html`, sem dependências nem build) com:

- **Destinos**: busca e filtros
- **Sistema**: cultivo, treinamento, **cultivo duplo** e **mantra duplo**, com calculadoras
- **Materiais**: metais e materiais do mundo murim

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (`murim`) e envie estes arquivos para a branch `main`.
2. Vá em **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Salve. Em cerca de 1 minuto o site fica em `https://noxedf.github.io/murim/`.

Links diretos para as abas: `#sistema` e `#materiais`.

## Atualizar

Edite o `index.html` e faça commit. O GitHub Pages republica sozinho.

## Compartilhamento e SEO

Arquivos extras (envie todos junto com o `index.html`): `404.html`, `og-image.png`, `sitemap.xml` e `robots.txt`.

Os endereços já apontam para `https://noxedf.github.io/murim/`. Se mudar o nome do repositório ou usar domínio próprio, troque esse endereço em `index.html` (tags `canonical`, `og:url`, `og:image`, `twitter:image` e o JSON-LD), em `sitemap.xml` e em `robots.txt`.

Para conferir a prévia do link depois de publicar, cole o endereço no depurador do Facebook (developers.facebook.com/tools/debug) ou no Card Validator do LinkedIn. O WhatsApp e o Discord guardam a prévia em cache, então pode ser preciso esperar ou usar um link novo.
