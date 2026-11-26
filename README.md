# DESIGNER // Temas Animados

Coleção aberta de páginas web animadas, feitas só com **HTML + CSS + JavaScript puro** — sem frameworks, sem dependências e sem etapa de build.

### 🌐 [Ver online → metrobeft.github.io/designer-temas-animados](https://metrobeft.github.io/designer-temas-animados/)

| Portal | Tema hacker | Tema anime |
|---|---|---|
| [abrir](https://metrobeft.github.io/designer-temas-animados/) | [abrir](https://metrobeft.github.io/designer-temas-animados/tema-hacker/) | [abrir](https://metrobeft.github.io/designer-temas-animados/tema-anime/) |

**Cada pasta deste repositório é um tema personalizado.** Um tema reúne várias páginas com a mesma identidade visual (cores, tipografia, efeitos e animações), uma página inicial própria (hub) e navegação entre todas elas.

## Temas

| Pasta | Tema | Status | Conteúdo |
|---|---|---|---|
| [`tema-hacker/`](tema-hacker/) | Hacker · glitch · matrix · HUD | ✅ pronto | Intro estilo vídeo + 8 módulos animados |
| [`tema-anime/`](tema-anime/) | Anime · sakura · mangá | 🚧 em construção | Página de prévia; módulos em breve |

## Como abrir

**Online:** acesse o [site no GitHub Pages](https://metrobeft.github.io/designer-temas-animados/).

**Direto no navegador:** baixe ou clone o repositório e abra o `index.html` da raiz. Ele é o portal que leva a todos os temas, e todas as páginas têm um botão **⌂ INÍCIO** para voltar a ele.

```bash
git clone https://github.com/metrobeft/designer-temas-animados.git
```

**Com servidor local (opcional):**

```bash
python -m http.server 8000
# depois acesse http://localhost:8000
```

> As fontes vêm do Google Fonts. Sem internet, as páginas usam fontes do sistema.

## Estrutura

```
.
├── index.html          ← portal: escolhe o tema e acessa qualquer página
├── tema-hacker/
│   ├── index.html      ← intro em vídeo + hub do tema
│   ├── 01-matrix-rain.html
│   ├── ...
│   ├── 08-digital-twin.html
│   └── README.md
└── tema-anime/
    ├── index.html      ← prévia "em breve"
    └── README.md
```

## Como criar um novo tema

1. Crie uma pasta `tema-<nome>/`.
2. Coloque um `index.html` como hub do tema e as páginas dele ao lado.
3. Em cada página, adicione um link `../index.html` (⌂ INÍCIO) para voltar ao portal.
4. Adicione um card do novo tema no `index.html` da raiz e uma linha na tabela acima.
5. Escreva um `README.md` dentro da pasta descrevendo as páginas.

Cada página é um arquivo único e independente (HTML, CSS e JS juntos), então dá para copiar uma página isolada para outro projeto sem levar mais nada.

## Licença

[MIT](LICENSE) — use, modifique e compartilhe à vontade.
