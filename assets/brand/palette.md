# Paleta de cores — Interlúdio

## Paleta principal

| Cor | Hex | Uso |
|---|---|---|
| ![#1e3556](https://via.placeholder.com/14/1e3556/1e3556.png) Navy | `#1e3556` | texto, menu lateral, marca |
| ![#f76d5a](https://via.placeholder.com/14/f76d5a/f76d5a.png) Coral | `#f76d5a` | ação primária ("Gerar .h5p") |
| ![#bcabe3](https://via.placeholder.com/14/bcabe3/bcabe3.png) Roxo | `#bcabe3` | destaque (item ativo do menu) |
| ![#88ceb5](https://via.placeholder.com/14/88ceb5/88ceb5.png) Menta | `#88ceb5` | destaque (ação secundária, "Gerar .ilat") |
| ![#fdf9f5](https://via.placeholder.com/14/fdf9f5/fdf9f5.png) Creme | `#fdf9f5` | fundo da aplicação |

## Tons derivados (estados de hover/contraste)

| Cor | Hex | Uso |
|---|---|---|
| Navy escuro | `#15283f` | — |
| Navy claro | `#eef2f7` | fundos sutis |
| Coral hover | `#e85c49` | hover do botão coral |
| Menta hover | `#78b59f` | hover do botão menta |
| Menta escura | `#0f766e` | uso pontual de alto contraste |

## Observações de acessibilidade

Roxo e menta (paleta principal) são tons pastéis claros — com texto branco o contraste fica abaixo do recomendado (WCAG AA). Por isso, sempre que usados como fundo de botão ou destaque, o texto deve ser **navy** (`#1e3556`), não branco.

Ficheiro irmão: [`palette.css`](./palette.css) — as mesmas cores como variáveis CSS (`:root`), idênticas às usadas no `index.html` do app.

## Fontes

- **Poppins ExtraBold (800)** — wordmark "Interlúdio", embutida como `@font-face` em base64 (sem CDN).
- **-apple-system / Segoe UI / Roboto** (pilha de fontes do sistema) — restante da interface.

## Marca "IL"

A marca combina a barra navy + "L" menta com um quadrado coral contendo um dado branco (5 pips). Ver [`il-mark.png`](./il-mark.png) para o recorte oficial, extraído da prancha de referência original (não é uma recriação procedural).
