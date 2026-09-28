# Projeto Flamengo — Site em HTML puro

Site acadêmico sobre o **Clube de Regatas do Flamengo**, feito apenas com HTML (sem nenhum CSS), para a avaliação da disciplina.

## Páginas

| Página | Arquivo | Conteúdo |
|---|---|---|
| Início | `index.html` | Apresentação do clube, temporada 2025, vídeo, perguntas rápidas e "Sobre este trabalho" |
| História | `html/historia.html` | Fundação no remo (1895), chegada do futebol (1911), Maracanã (com mapa) e a geração de 1981 |
| Títulos | `html/titulos.html` | Tabela das finais de 2025, números do Brasileirão, `meter` e `progress` |
| Ídolos | `html/idolos.html` | Zico, Júnior, Leandro, Adílio, Arrascaeta, Gabigol, Bruno Henrique, Danilo e áudio |
| Final de 2019 | `html/final-2019.html` | A virada sobre o River Plate em Lima e o formulário "Onde você estava na virada?" |

Todas as páginas têm o mesmo menu (`nav`), então dá para navegar de qualquer página para qualquer outra.

## Organização das pastas

```
projeto-flamengo/
├── index.html
├── README.md
├── html/    → historia.html, titulos.html, idolos.html, final-2019.html
├── img/     → imagens usadas nas figuras
├── audio/   → batucada-arquibancada.mp3
└── video/   → LEIA-ME.txt (o vídeo do projeto está no YouTube, na página inicial)
```

## Requisitos atendidos

- **Estrutura semântica:** `header`, `nav`, `main`, `section`, `article`, `aside` e `footer` em todas as páginas.
- **Meta tags:** `author`, `keywords` e `description` em todas as páginas.
- **Listas:** `ul`, `ol` e `li`.
- **Tags isoladas:** `hr`, `br`, `b`, `i`, `u`.
- **Tabela 3x3** com dados reais das finais de 2025, usando `thead`, `tbody`, `th`, `td` e `rowspan` (página Títulos).
- **Formulário avançado:** `type="date"`, `type="file"`, `type="range"`, `type="color"`, `datalist`, `select`, radio, checkbox, `textarea`, `required`, `placeholder`, `label`, `fieldset` e `legend` (página Final de 2019).
- **`details` e `summary`:** em todas as páginas.
- **`figure` e `figcaption`:** nas páginas Início, História, Títulos, Ídolos e Final de 2019.
- **Multimídia:** vídeo do YouTube em `iframe` (página Início), áudio local em `audio/` (página Ídolos) e um `iframe` com o mapa do Maracanã (página História).
- **Marcação avançada:** `abbr`, `mark`, `del`, `ins`, `blockquote`, `cite`, `progress` e `meter`.
- **Sem CSS:** nenhum `style=`, `<style>`, `<center>`, `cellpadding` ou `align`.

## Requisitos de autoria

- **Data da prova:** `<time datetime="2026-09-28">` na seção "Sobre este trabalho" da página inicial.
- **Frase do professor sobre HTML:** dentro de um `blockquote` na página inicial.
- **Comentário sobre dificuldade:** na tabela da página Títulos (rowspan e centralização) e no campo `range` da página Final de 2019.

## Como abrir

Basta abrir o arquivo `index.html` no navegador. O vídeo do YouTube (Início) e o mapa (História) precisam de internet; o resto funciona offline.

## Fontes dos dados

- CONMEBOL — final da Libertadores 2025 (Palmeiras 0 x 1 Flamengo, 29/11/2025, Lima)
- CBF — título do Brasileirão 2025 (Flamengo 1 x 0 Ceará, 03/12/2025, Maracanã)
