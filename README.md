# Aulas HTML - Site da Teté

Material didático de HTML/CSS baseado na *Apostila de Introdução à Linguagem HTML* (FACCAT),
adaptado em 40 aulas práticas de ~30 minutos, com tema único: **"Site da Teté"** — um bebê de 1 aninho.

Cada aula reaproveita classes CSS das aulas anteriores, sempre um pouco mais avançada que a anterior.

## Como abrir

Abra `index.html` no navegador. Ele lista as 40 aulas em cartões, cada um levando pra sua pasta.

## Estrutura

```
aulas-html/
├── index.html          # página inicial com link para todas as aulas
├── style.css            # estilo do index.html
├── 01-capa/ ... 39-proximos-passos-css-avancado/
│   └── paginaNN.html + paginaNN.css   # 1 conceito por aula, HTML e CSS sempre separados
└── 40-projeto-completo-loja-tete/     # projeto final, várias páginas
    ├── login.html / login.css
    ├── inicio.html / inicio.css       # vitrine com 6 produtos
    ├── sobre.html / sobre.css
    ├── contato.html / contato.css
    ├── cadastro.html / cadastro.css
    ├── recuperar-senha.html / recuperar-senha.css
    └── imagens/                       # SVGs locais (sem depender de internet)
```

## Aulas 1-37 — conceitos da apostila original

Uma pasta por página da apostila (`ESTRUTURA_APOSTILA.md`, na raiz do projeto, tem o resumo
completo de cada página do livreto original). Ordem gradativa:

| Aulas | Tema |
|---|---|
| 01-02 | Capa e sumário |
| 03-08 | Conceito de tag, editores, publicação, estrutura HTML básica (head/body) |
| 09-10 | Fontes: cor, tamanho, tipo |
| 11-14 | Cabeçalhos, alinhamento, parágrafos |
| 15 | Linha horizontal e comentários |
| 16-18 | Listas (marcadores, numeradas, sub-listas) |
| 19 | Formatação de frases (negrito, itálico...) |
| 20-22 | Links (ligações, caminhos, âncoras internas) |
| 23-26 | Imagens (inserção, dimensão, alinhamento, espaçamento) |
| 27-30 | Tabelas |
| 31-36 | Formulários (campos, botões, envio de dados) |
| 37 | Conclusão |

Cada `paginaNN.html`/`paginaNN.css` é independente — dá pra abrir isolado numa aula sem
precisar navegar pelas outras.

## Aula 38 — Projeto Final (revisão)

`38-projeto-final-site-tete/` junta **todas** as classes CSS criadas nas aulas 1-37 num único
site de 1 página (nav + álbum + tabela + formulário). Não introduz nada novo — é revisão.

## Aula 39 — Próximos Passos

`39-proximos-passos-css-avancado/` é o gancho pra CSS moderno que não estava na apostila
original: `flexbox`, `grid` e `@media` (responsividade).

## Aula 40 — Projeto Completo (Loja da Teté)

Projeto final de verdade: uma lojinha de produtos infantis com 6 páginas HTML navegáveis entre si.

- **login** (sem menu) → Entrar leva a `inicio.html`; links para `cadastro.html` e `recuperar-senha.html`
- **início** (com menu + botão Sair) → vitrine com 6 produtos em destaque; Sair volta ao login
- **sobre** (com menu) → texto sobre a loja
- **contato** (com menu) → formulário de contato
- **cadastro** (sem menu) → só volta ao login
- **recuperar-senha** (com menu) → só volta ao login

Todo HTML e CSS são separados por página; imagens são SVGs locais em `40-projeto-completo-loja-tete/imagens/`.

## Paleta de cores (tema bebê)

| Cor | Hex | Uso |
|---|---|---|
| Rosa bebê | `#ffd1dc` | destaques, botões primários |
| Azul bebê | `#bee3f8` | links, botões secundários |
| Menta | `#c8f4de` | fundos de destaque |
| Creme | `#fff8e7` | fundo geral das páginas |
| Lilás | `#e6d7f7` | fundo de formulários |
| Marrom texto | `#6b4f4f` | cor de texto padrão |
