# Interlúdio

**Gerador de atividades H5P para Moodle — tudo em um único arquivo HTML, sem instalação.**

Interlúdio é uma ferramenta do [INOVALAB](https://github.com/rgbittencourt) (Laboratório de Inovação e Mídias Digitais — IFSC, Campus Continente) para professores montarem atividades interativas e exportá-las prontas para uso, sem depender de servidor, backend ou conta em serviço externo.

## O que faz

Você monta o conteúdo em formulários simples (cartões, perguntas, slides, pontos de um vídeo, etc.) e o Interlúdio gera o pacote da atividade pronto para importar — com uma prévia que roda o player H5P de verdade, direto no navegador, antes de você baixar qualquer coisa.

### Tipos de atividade

| Atividade | Biblioteca H5P |
|---|---|
| Flashcards | H5P.Flashcards |
| Question Set | H5P.QuestionSet |
| Apresentação (com importação de PPTX) | H5P.CoursePresentation |
| Vídeo Interativo (YouTube ou upload, com interações em pontos de pausa) | H5P.InteractiveVideo |
| Trilha de decisões | H5P.BranchingScenario |
| Hotspots de Imagem | H5P.ImageHotspots |
| Dialog Cards | H5P.Dialogcards |
| Arrastar e Soltar | H5P.DragQuestion |
| Linha do Tempo | H5P.Timeline |
| Tour Virtual 360° | H5P.360 |
| Palavras Cruzadas | H5P.Crossword |
| AR Scavenger | H5P.ARScavenger |

Todas usam bibliotecas que já vêm no núcleo do Moodle desde a versão 3.9 — nenhum plugin extra é necessário.

## Como usar

1. Baixe `Interlúdio by INOVALAB.html` e abra no navegador (funciona offline, inclusive como PWA instalável).
2. Escolha o tipo de atividade na barra lateral e monte o conteúdo.
3. Use **▶ Testar antes de baixar** para rodar a atividade de verdade antes de exportar.
4. Exporte no formato que combina com o seu fluxo:

   - **⬇ Gerar .h5p** — pacote padrão, para subir direto no Moodle (Banco de conteúdo → Adicionar → H5P, ou dentro de uma atividade H5P).
   - **📦 Gerar .ilat** — mesma estrutura do pacote (`h5p.json` + `content/` + `libraries/`), mas com extensão própria (**I**nterlúdio + **AT**ividade), pensada para quem publica aulas como HTML estático (ex.: GitHub Pages) e embute o H5P direto na página via [h5p-standalone](https://www.npmjs.com/package/h5p-standalone), em vez de subir a atividade no Moodle nativamente.

## Características técnicas

- **Zero dependências**: um único arquivo `.html`, sem build, sem servidor, sem chamadas de rede em tempo de execução (fontes e logos embutidos como base64).
- **PWA**: pode ser instalado e usado offline.
- **Prévia real**: o player H5P roda embutido no próprio app, para testar a atividade antes de exportar.
- **Sem dados enviados a terceiros**: tudo roda localmente no navegador; nada do conteúdo que você monta sai da sua máquina até você decidir exportar.

## Identidade visual

- Paleta de cores: [`assets/brand/palette.md`](assets/brand/palette.md) (e [`palette.css`](assets/brand/palette.css) com as variáveis prontas)
- Marca "IL": [`assets/brand/il-mark.png`](assets/brand/il-mark.png)
- Ícones do app (favicon / PWA): [`assets/icons`](assets/icons)
- Logos institucionais (INOVALAB / IFSC): [`assets/logos`](assets/logos)

## Créditos

Projeto do **INOVALAB** — Laboratório de Inovação e Mídias Digitais, **IFSC – Campus Continente**.
Contato: inovalab.cte@ifsc.edu.br
