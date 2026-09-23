# omplay-pages — organização dos arquivos

Os arquivos, antes soltos na raiz, foram agrupados **por projeto/campanha**. A data de cada
arquivo (quando entrou no repositório) foi usada para identificar a que iniciativa pertence.

## Estrutura

| Pasta | Conteúdo | Período |
|-------|----------|---------|
| `site-base/` | Página inicial e utilitários (`index.html`, `design-brief.html`, `extrair-imagens.html`) + assets genéricos | mai/2026 |
| `forum-assinatura/` | Página de assinatura do Fórum + `background.png`, `elementos2.png` | mai/2026 |
| `email-desenrola-brasil/` | E-mail marketing "Desenrola Brasil" | mai/2026 |
| `forum-tarifa-zero/` | Landing pages da campanha Fórum Tarifa Zero (todas as versões) + imagens `ftzo-*` | mai/2026 |
| `dialogos-do-futuro/` | Página "Diálogos do Futuro" + imagens `dial-*` | mai/2026 |
| `logos-institucionais/` | Logos de instituições (CAUSP, CAU, BNDES, Maricá, UFRJ, Vale, Fórum) | jun/2026 |
| `branding-omplay/` | Identidade visual OMPlay (logos, headers de landing page) | jul/2026 |
| `capas-conteudo/` | Capas/thumbnails de conteúdo — série "O Pensamento de…" e temas (Trumpismo, Era Vargas, Racismo Estrutural etc.) | ago/2026 |
| `banners/` | Banners CAU/SP nas versões PC, mobile e tablet (5 cada) | ago/2026 |
| `diversos/` | Fotos e imagens avulsas (WhatsApp, painéis de evento, retratos) | jun–jul/2026 |

## ⚠️ Importante sobre os links das imagens

As páginas HTML referenciam as imagens por **URL absoluta** apontando para a branch `main`
(ex.: `https://raw.githubusercontent.com/.../main/ftzo-hero.png`). Ao mover as imagens para
pastas, esses links foram **atualizados** para os novos caminhos
(ex.: `.../main/forum-tarifa-zero/ftzo-hero.png`).

Como as URLs apontam para `main`, **as imagens só voltam a carregar depois que esta branch
for mesclada na `main`**. Até lá, ao pré-visualizar esta branch, algumas imagens podem não
aparecer — isso é esperado e se resolve no merge.

Referências a domínios externos (`revistaforum.com.br`, `mautic.revistaforum.com.br`) não foram
alteradas.

## Removido

- `banners` — arquivo vazio (1 byte), descartado.
