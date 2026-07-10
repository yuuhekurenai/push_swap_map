# push_swap — Guia Visual

Guia interativo do projeto **push_swap** (42 School), com fluxogramas, quadrinhos animados de ponteiros e diagramas de decisão para cada arquivo do código-fonte.

**[→ Acessar o site](https://yuuhekurenai.github.io/push_swap_map/)**

---

## O que tem aqui

Um único arquivo HTML, sem dependências além de fontes do Google — abre em qualquer navegador, sem instalar nada.

| Aba | Conteúdo |
|---|---|
| **Visão geral** | Arquitetura do projeto: como main → parser → operations → sorting → utils se encaixam |
| **main.c** | Fluxograma da função principal, do parsing à limpeza de memória |
| **parser.c** | `ft_atoi`, `create_node`, `add_to_stack`, `check_duplicates`, `parse_args` — com quadrinhos passo a passo dos ponteiros |
| **operations.c** | As 11 operações (`sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, `rrr`), animadas nó por nó |
| **sorting.c** | `sort_three` (seletor interativo dos 6 casos), `sort_five` e `sort_big` (algoritmo Turk/chunks) |
| **utils.c** | `is_sorted`, `free_stack` e demais funções auxiliares |
| **benchmark** | Metas de operações para 100 e 500 números, com medidor visual |

## Como usar

Só abrir o link do GitHub Pages acima, ou baixar o `index.html` e abrir localmente no navegador.

## Rodando localmente

```bash
git clone https://github.com/yuuhekurenai/push_swap_map.git
cd push_swap_map
open index.html   # ou: xdg-open index.html
```

## Sobre o projeto push_swap

push_swap é um projeto da 42 School: ordenar uma lista de números usando apenas duas pilhas (A e B) e um conjunto fixo de 11 operações, minimizando o número de movimentos.

- **≤ 3 números** → `sort_three`
- **≤ 5 números** → `sort_five`
- **> 5 números** → `sort_big` (algoritmo Turk / chunks)

## Autor

Gabriel — 42 School, campus SP (`gcelesti`)

---

*Feito para compartilhar com a turma.*
