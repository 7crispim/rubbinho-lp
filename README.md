# Cozinha do Rubbinho — cardápio digital

Landing page estática do cardápio da Cozinha do Rubbinho (Águas Claras, DF).

- `index.html` — página única (HTML + CSS + JS vanilla, sem build)
- `img/` — banners, fotos dos pratos, logo e mini-mapa (WebP)

Deploy automático na Vercel a cada push na `main`.

## Editar

- **Preços e pratos:** direto no `index.html`, nos blocos `<article class="card">`.
- **Link do grupo de marmitas:** procurar o comentário `<!-- TROCAR: link do grupo -->`.
- **Fotos:** substituir o arquivo em `img/` mantendo o mesmo nome.

O mini-mapa (`img/mapa.webp`) usa tiles do OpenStreetMap — a atribuição
"© OpenStreetMap contributors" impressa na imagem é obrigatória pela licença ODbL.
