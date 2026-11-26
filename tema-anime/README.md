# Tema Anime 🌸

Visual de anime e mangá: abertura de série, pétalas de sakura, linhas de velocidade, onomatopeias japonesas (ドーン！, キラキラ, ゴゴゴ), textos que trocam entre português e japonês, brilhos e corações que seguem o mouse — e sons **100% sintetizados ao vivo**.

Comece pelo [`index.html`](index.html): uma **abertura em estilo anime** (pétala caindo, amanhecer com 春 e créditos, cortes 夢 · 光 · 心 com ドーン！, logo ANIME montando letra por letra) e depois o hub com os 8 episódios.

## Mascote

O tema exibe a mascote configurada em [`mascote/mascote.png`](mascote/mascote.png) no fim da abertura e no hub, com animação de flutuação e balões de fala.

Para trocar a imagem, salve o novo arquivo em [`mascote/`](mascote/) e atualize o bloco `MASCOTE PERSONALIZADA` no `index.html` (arquivo, nome, fala e crédito). Se o campo `arquivo` ficar vazio ou o arquivo não for encontrado, o tema exibe a personagem reserva **Hana** em SVG. Veja mais detalhes e cuidados de direitos em [`mascote/LEIA-ME.md`](mascote/LEIA-ME.md).

## Episódios

| # | Página | O que tem | Controles |
|---|---|---|---|
| 00 | [`index.html`](index.html) | Abertura de anime + hub de episódios + mascote | PULAR, SOM, REVER ABERTURA |
| 01 | [`01-sakura-storm.html`](01-sakura-storm.html) | Cerejeira procedural, tempestade de pétalas, haicais originais na vertical, lanternas à noite | mouse = vento · clique = rajada · `N` noite/dia |
| 02 | [`02-speed-lines.html`](02-speed-lines.html) | Carregar a aura: linhas de concentração, rachaduras, pedras flutuando, quadro de impacto invertido | segurar clique ou `Espaço` · soltar = liberar |
| 03 | [`03-manga-panels.html`](03-manga-panels.html) | Página de mangá que se desenha (leitura da direita para a esquerda), retícula, olhos, balões, virada de página | clique = próximo quadro · `A` auto · `Espaço` virar |
| 04 | [`04-neon-tokyo.html`](04-neon-tokyo.html) | Cidade na chuva, letreiros neon em japonês, reflexo na rua molhada, trem, trovões, guarda-chuvas | controle de **intensidade da chuva** (0–100%) + mudo da chuva · clique no letreiro / no céu · `T` trem · `R` presets de chuva |
| 05 | [`05-magic-circle.html`](05-magic-circle.html) | Círculo mágico com runas, 6 elementos, encantamentos em japonês, pilar de luz e 変身 (transformação) | painel de elementos (canto superior direito) · segurar = conjurar · `1`–`6` · mouse ↕ inclina |
| 06 | [`06-lofi-room.html`](06-lofi-room.html) | Quarto à noite com chuva no vidro, relâmpagos, gato dormindo, chá, luminária e **rádio lofi gerado ao vivo** | **mixer**: chuva, raios e música com volume e mudo separados · rádio / `P` · luminária / `L` · `K` raio · gato |
| 07 | [`07-starfall.html`](07-starfall.html) | Céu com via láctea, aurora, constelações que se desenham, torii, vaga-lumes e pedidos | clique no céu = pedido · `A` aurora |
| 08 | [`08-koi-pond.html`](08-koi-pond.html) | Lago visto de cima: carpas que seguem o mouse, comida, ondulações, vitórias-régias e shishi-odoshi | clique = alimentar · `P` pétalas |

## Som

Tudo é sintetizado com **Web Audio** (nenhum arquivo de áudio): sininhos pentatônicos, jingle de eyecatch, sopros, impactos, vento, koto, sino de vento (fūrin), carga de energia, chuva, zumbido neon, trem "gatan-goton", trovão, pad mágico, música lofi (acordes, baixo, bateria e chiado de vinil), grilos, gotas e o bambu do shishi-odoshi.

- O som vem **ligado por padrão**. Desligue no botão **🔊 SOM** ou com a tecla **M** — a escolha fica salva.
- Navegadores bloqueiam áudio até o primeiro clique/tecla. Quando isso acontece, a abertura mostra **▶ ASSISTIR ABERTURA** e as páginas mostram um aviso para tocar na tela.

## Navegação

Toda página tem **⌂ INÍCIO** (portal), **◄ HUB** (hub do tema), **‹ ANT / PRÓX ›** e **🔊 SOM**. Cada episódio abre com um *eyecatch* (cartão de episódio).

## Paleta

| Cor | Uso |
|---|---|
| `#ff7eb6` | rosa sakura (principal) |
| `#a98bff` | lilás |
| `#ffe066` | dourado / destaque |
| `#7fe7ff` | ciano |
| `#1a0b2e` | noite |

Fontes: **Dela Gothic One** (títulos), **M PLUS Rounded 1c** (texto), **Bangers** (onomatopeias latinas) e **Shippori Mincho** (haicais e caligrafia).
