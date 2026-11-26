# Mascote personalizada

Esta pasta serve para trocar a mascote padrão do tema anime (a **Hana**) por uma imagem sua. A imagem aparece no fim da abertura e no hub, com as mesmas animações e o balão de fala.

## Como usar

1. Salve a imagem aqui nesta pasta. PNG, WebP ou GIF com fundo transparente fica melhor, e a pose em pé, de corpo inteiro, encaixa no espaço.
2. Abra `tema-anime/index.html`, procure o bloco `MASCOTE PERSONALIZADA` e preencha:

```js
const MASCOTE={
  arquivo:'mascote/nome-do-arquivo.png',
  nome:'Nome da personagem',
  credito:'Crédito e licença exigidos pelo dono da imagem'
};
```

3. Abra a página. Se o arquivo não for encontrado, a Hana continua aparecendo e o console avisa.

## Direitos e licença

- Use apenas imagens que você **tem o direito de usar** e coloque no campo `credito` exatamente o que o dono exige.
- Se a imagem tiver licença **não comercial** (por exemplo, CC BY-NC), ela **não** fica coberta pela licença MIT do projeto. Anote isso no `README.md` da raiz, com o nome do arquivo, o autor e a licença.
- Quem adiciona a imagem é responsável por conferir esses termos.
