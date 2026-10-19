# @mel.englishfortech — página de links

Página de links do meu Instagram [@mel.englishfortech](https://www.instagram.com/mel.englishfortech/), com um guia gratuito de inglês para vagas de dados.

Feita em **HTML e CSS puros**, sem framework, e publicada na **Vercel**.

## Estrutura

```
├── index.html        → a página (textos, links, formulário)
├── style.css         → o visual (cores e fontes nas variáveis do topo)
├── privacidade.html  → política de privacidade (LGPD)
└── assets/
    ├── favicon.svg   → ícone da aba do navegador
    └── foto.jpg      → minha foto (adicionar)
```

## O que falta preencher

Procure por `[` nos arquivos (Ctrl+F). Cada ponto tem um comentário `TROCAR` explicando o que fazer.

| Onde | O quê |
|---|---|
| `index.html` | `[SUA FOTO]` → salvar `assets/foto.jpg` e trocar o `<div>` pela `<img>` do comentário |
| `index.html` | `[URL DO FORMULÁRIO]` → URL do formulário da ferramenta de e-mail |
| `index.html` | `[Nº DE PÁGINAS]` → número de páginas do guia |
| `index.html` | `[SEU LINK]` → link do Tech Word of the Week |
| `index.html` e `privacidade.html` | `[SEU EMAIL]` → e-mail para contato |
| `privacidade.html` | `[DATA]` e `[MAILERLITE OU BREVO]` |
| `index.html` (opcional) | `[URL DA IMAGEM DE COMPARTILHAMENTO]` → imagem 1200x630 para a prévia do link |

## Como editar

- **Textos e links:** direto no `index.html`.
- **Cores:** nas variáveis do topo do `style.css` (ex.: `--accent`).

## Como publicar

1. Suba esta pasta para um repositório no GitHub.
2. Na [Vercel](https://vercel.com), clique em **Add New → Project** e escolha o repositório.
3. Não precisa configurar nada: é um site estático. Clique em **Deploy**.
4. Cada alteração enviada ao GitHub atualiza o site sozinha.
