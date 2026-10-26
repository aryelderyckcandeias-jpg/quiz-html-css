# Quiz para programadores (HTML e CSS)

Página estática de um quiz interativo, feita para estudar **HTML semântico**, **formulários** e **CSS** do zero, sem JavaScript nem frameworks.

> Projeto de estudo. A página mostra as perguntas, a tabela de pontuação e o gabarito, mas ainda não calcula a nota sozinha.

## O que a página tem

- **8 perguntas**, cada uma com um tipo diferente de campo: múltipla escolha (`radio`), texto, senha, data, seleção múltipla (`checkbox`), upload de arquivo, menu suspenso (`select`) e pergunta com imagem.
- **Tabela de pontuação** com `thead`, `tbody` e `tfoot`.
- **Gabarito** escondido em um `<details>`, que abre ao clicar.
- **Formulário de feedback** com `fieldset`, `legend`, e-mail e `textarea`.
- Rodapé com link externo (`target="_blank"`).

## Conceitos praticados

| Área | O que foi usado |
| --- | --- |
| HTML | `header`, `main`, `section`, `footer`, `abbr`, `details`/`summary`, `table`, `form`, `label for` |
| Tipos de `input` | `radio`, `checkbox`, `text`, `password`, `date`, `file`, `email` |
| CSS | Reset com `*`, `flexbox` (`gap`), fontes do Google Fonts (Cabin e Noto Serif), `accent-color` |

## Como abrir

Não precisa instalar nada. Abra o `index.html` no navegador.

Para servir como um site local:

```bash
python3 -m http.server 8080
# depois acesse http://localhost:8080
```

Para publicar de graça no **GitHub Pages**: em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`.

## Estrutura do projeto

```text
.
├── index.html   # estrutura e conteúdo do quiz
├── style.css    # estilos
└── README.md
```

## Próximos passos

- Adicionar JavaScript para corrigir as respostas e mostrar a pontuação.
- Tornar o layout responsivo com `@media` e testar a acessibilidade (contraste de cores e navegação por teclado).
- Validar a página com o [validador de HTML do W3C](https://validator.w3.org/).
