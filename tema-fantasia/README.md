# Tema Fantasia ⚔

Fantasia medieval: reinos, elfos, anões, magos e dragões. Pergaminhos, runas do Futhark antigo que se transformam em português, brasas douradas que seguem o mouse e sons **100% sintetizados ao vivo** (harpa, trompas, sinos, bigorna, fogo e o rugido do dragão).

Comece pelo [`index.html`](index.html): um **prólogo cinematográfico** e depois o hub com o **Mapa dos Reinos**.

## Prólogo (abertura)

1. **A vela** — uma vela acesa no escuro e a lenda surgindo palavra por palavra.
2. **O mapa** — um pergaminho se desenrola e o Mapa dos Reinos se desenha sozinho: litoral, rios, florestas, montanhas e a rota vermelha da jornada passando pelos 8 lugares.
3. **Os quatro povos** — cortes diagonais com Humanos, Elfos, Anões e Magos, cada um com seu personagem.
4. **O dragão** — a silhueta de Ignaroth cruza a lua cheia, ruge e solta fogo.
5. **O título forjado** — as letras de FANTASIA são marteladas uma a uma, com faíscas, faixa "Crônicas dos Reinos" e os heróis subindo.

Controles: **PULAR** (ou `Esc`/`Espaço`/`Enter`), **🔊 SOM**, **⌂ INÍCIO** e **↺ REVER ABERTURA** no hub.

No hub: o **Mapa dos Reinos** é clicável (cada lugar abre o capítulo), os heróis falam quando você passa o mouse e os cartões dos 8 capítulos ficam logo abaixo.

## Personagens

Ilustrações originais em SVG animado (respiram, piscam, capas e cabelos balançam, armas brilham), na pasta [`personagens/`](personagens/). Dá para abrir cada arquivo direto no navegador ou usar como `<img>` em outro projeto.

Nos capítulos II e III, Lyria e Durgan ficam **embutidos na página com braços articulados**: a Lyria mira na direção do clique, encaixa a flecha, puxa a corda e solta; o Durgan ergue o martelo e golpeia a bigorna (as faíscas e o som saem no momento do impacto).

| Arquivo | Personagem | Povo · classe | Lar |
|---|---|---|---|
| [`humano-aldric.svg`](personagens/humano-aldric.svg) | Sir Aldric | Humano · cavaleiro | Valmor (cap. I) |
| [`elfa-lyria.svg`](personagens/elfa-lyria.svg) | Lyria | Elfa · arqueira | Sylvaren (cap. II) |
| [`anao-durgan.svg`](personagens/anao-durgan.svg) | Durgan Barba-de-Brasa | Anão · guerreiro | Durnhelm (cap. III) |
| [`mago-orvyn.svg`](personagens/mago-orvyn.svg) | Mestre Orvyn | Humano · mago | Torre Arcana (cap. VI) |

## Capítulos

| # | Página | O que tem | Controles |
|---|---|---|---|
| 00 | [`index.html`](index.html) | Prólogo + Mapa dos Reinos clicável + heróis que falam + cartões dos capítulos | PULAR, SOM, REVER ABERTURA |
| I | [`01-reino-humano.html`](01-reino-humano.html) | **A cidade de Valmor**: castelo com estandartes do sol, muralhas, casas com chaminés, moinho, guardas com lanternas à noite e Sir Aldric no caminho | clique no sino = badalar · clique no céu = fogos (noite) ou pombas (dia) · clique numa casa = acender a janela · `N` dia/noite · `F` festival |
| II | [`02-floresta-elfica.html`](02-floresta-elfica.html) | **O bosque de Sylvaren**: floresta em 4 camadas com paralaxe, árvores com runas, casas nas copas, pontes, cachoeira, coruja, vaga-lumes e espíritos de luz | clique = Lyria mira, puxa a corda e dispara uma flecha de luz (flores brotam onde cai) · segurar = espíritos seguem · `L` lanternas/luar · `S` canção élfica |
| III | [`03-montanhas-anas.html`](03-montanhas-anas.html) | **A forja de Durnhelm**: salão com pilares rúnicos, janela para os picos nevados, canal de lava, vagonetes, braseiros e Durgan na bigorna | clique na bigorna ou `Espaço` = Durgan ergue o martelo e golpeia (12 golpes forjam uma arma com nome) · `B` ou clique no fole = atiçar o fogo · clique no Durgan = conversar |
| IV | [`04-planaltos.html`](04-planaltos.html) | **Onde as pedras cantam**: mesas ao pôr do sol, torre em ruínas, ilhas flutuantes com cachoeiras, grifo, revoadas e centenas de folhas de grama ao vento | clique nas 7 pedras = cada uma toca uma nota (todas acesas = feixe de luz + aurora) · mouse = rajadas de vento · `W` tempestade · `D` dia/noite |
| V | [`05-masmorra.html`](05-masmorra.html) | **Os salões sem luz**: corredor em perspectiva no escuro, só a tocha ilumina — baús, esqueletos, olhos que fogem da luz, goteiras e 5 tipos de andar gerados ao acaso | mouse = tocha · clique = abrir baú / chacoalhar esqueleto / descer a escada · `T` tocha forte |
| VI | [`06-torre-do-mago.html`](06-torre-do-mago.html) | **O caldeirão de Orvyn**: janela redonda com a lua, estantes de poções, velas flutuantes, mapa celeste, coruja, bola de cristal e grimório | `1`–`6` ou clique = ingredientes (3 criam uma poção com nome e efeito na sala) · `P` virar página do grimório · `R` esvaziar o caldeirão |
| VII | [`07-covil-do-dragao.html`](07-covil-do-dragao.html) | **O tesouro de Ignaroth**: caverna com lava e montanhas de ouro e o dragão dormindo, que ronca, solta fumaça e às vezes abre um olho; ao acordar, abre a boca e cospe fogo | clique no ouro = pegar moedas · mouse rápido = barulho (100% acorda o dragão: rugido e fogo) · `S` andar furtivo |
| VIII | [`08-salao-dos-herois.html`](08-salao-dos-herois.html) | **Escolha seu campeão**: salão do trono com vitral, estandartes dos 4 povos, heróis em pedestais, atributos, habilidades e barra do grupo | `←`/`→`, `A`/`D`, `1`–`4` ou clique = trocar herói · `Enter`/`Espaço`/ESCOLHER = chamar para o grupo |

Os controles também aparecem no canto inferior direito de cada página.

## Som

Tudo é sintetizado com **Web Audio** (nenhum arquivo de áudio), com reverberação de salão de pedra: harpa em ré dórico, trompas e fanfarra, sinos de igreja, bigorna e espadas, tambores, fogo, vento, rios, magia cintilante, moedas, páginas virando e o rugido do dragão.

- O som vem **ligado por padrão**. Desligue no botão **🔊 SOM** ou com a tecla **M** — a escolha fica salva.
- Navegadores bloqueiam áudio até o primeiro clique/tecla. Quando isso acontece, o prólogo mostra **▶ INICIAR A LENDA** e os capítulos mostram um aviso para tocar na tela.

## Navegação

Toda página tem **⌂ INÍCIO** (portal), **◄ MAPA** (hub do tema), **‹ ANT / PRÓX ›** e **🔊 SOM**. Cada capítulo abre com um **pergaminho** com o número do capítulo e um selo de cera.

## Paleta

| Cor | Uso |
|---|---|
| `#e8b84a` | ouro (principal) |
| `#f1e2bf` | pergaminho |
| `#c8323c` | carmesim de Valmor |
| `#46d39a` | esmeralda élfica |
| `#ff8a3d` | brasa da forja |
| `#9a7bff` | arcano |
| `#0b0912` | noite |

Fontes: **Cinzel Decorative** (títulos), **Cinzel** (interface), **IM Fell English** (textos e lendas) e **Noto Sans Runic** (runas).
