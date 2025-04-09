# Prefabs

## NPCs

### NPC Guia  
**Desc:** Principal NPC que acompanhará o usuário durante sua jornada.  
**Onde:** Pontos específicos durante a história, com o objetivo de guiar o jogador e contar a história do mundo.  
**Sprite:** Muda durante o jogo. Inicialmente como uma figura similar a um zumbi, e conforme o jogador consegue fragmentos do poder, ele vai recuperando sua forma humana.  
**Colisores:** Sem, personagem amigável.  
**Fontes de áudio:** Grunhido de zumbi.  
**Script:** Deve ser possível interagir com esse personagem. Ele aparece em pontos específicos do mapa para ensinar o jogador sobre mecânicas básicas e contar a história do mundo.

---

### NPC Comerciante  
**Desc:** Carroagem de cavalos esqueléticos que contém um personagem comerciante.  
**Onde:** Pontos específicos do mapa.  
**Sprite:** Carroagem levada por cavalos esqueléticos, guiada por um comerciante.  
**Colisores:** Sem.  
**Fontes de áudio:** Barulho de grunhido ao interagir com o NPC.  
**Script:** Interage com o jogador e troca moedas por itens que podem ajudar durante a jornada.

---

### NPC Mímico  
**Desc:** Uma sombra distorcida que repete os últimos movimentos do jogador quando interagida.  
**Onde:** Áreas específicas onde o jogador precisa dominar um movimento recente (como pulo duplo ou dash).  
**Sprite:** Sombra do jogador com glitch visual ou distorção, estilo pixel art.  
**Colisores:** Sem colisores de dano, personagem amigável.  
**Fontes de áudio:** Efeito sonoro etéreo, como um eco distante ou distorção de voz.  
**Script:** Ao interagir, o Eco reproduz os últimos 2–3 segundos de movimentos que o jogador fez ao chegar ali. Serve como dica indireta ou para mostrar como avançar na área.

---

## Inimigos

### Inimigo Esqueleto  
**Desc:** Presset de esqueleto que ataca o player usando uma espada. Desafio básico.  
**Onde:** Níveis iniciais, onde o player ainda é fraco.  
**Sprite:** Esqueleto pixelizado.  
**Colisores:** Corpo do esqueleto, espada do esqueleto.  
**Som:** Barulho de ossos e “swing” da espada.  
**Script:** Deve ir em direção ao player, brandindo a espada em um movimento para baixo quando chegar perto.

---

### Inimigo Demônio com Lança  
**Desc:** Demônio vermelho que tem uma lança.  
**Onde:** Antes da segunda fase.  
**Sprite:** Demônio vermelho com asas e lança pixelizado.  
**Colisores:** Corpo e ponta da lança.  
**Fontes de áudio:** Barulho do metal da lança, grunhidos de demônio.  
**Script:** Quando o player estiver distante, arremessa a lança em direção ao player, causando dano se entrar em contato. O jogador deve desviar pulando.

---

### Inimigo Vampiro Voador  
**Desc:** Vampiro que voa entre plataformas.  
**Onde:** Espalhados em meio aos níveis, após o jogador obter o dash.  
**Sprite:** Vampiro pixelizado.  
**Colisores:** Corpo.  
**Fontes:** Barulho de bater de asa, grunhido ao receber dano.  
**Script:** Voa para cima e para baixo, criando um obstáculo. O jogador precisará usar o dash da espada para passar.

---

## Projéteis

### Projétil Lança  
**Desc:** Lança arremessada pelo demônio.  
**Onde:** Onde se encontra o demônio.  
**Sprite:** Lança pixelizada.  
**Colisores:** Ponta e corpo da lança.  
**Fontes:** Barulho de metal ao entrar em contato.  
**Script:** Avança no eixo X em direção ao player.

---

## Itens

### Fragmento do Poder  
**Desc:** Fragmento obtido após matar um dos chefões principais.  
**Onde:** Dropado por chefes.  
**Sprite:** Uma estrela brilhante.  
**Colisores:** Corpo.  
**Fontes:** Barulho de estrela ao ser dropado.  
**Script:** Coletável que dá novas habilidades ao player (ex: pulo duplo, dash, etc.).

---

### Moeda Sombria  
**Desc:** Item coletável que representa a moeda do mundo de Solipsia.  
**Onde:** Espalhada pelos cenários, dropada por inimigos ou escondida.  
**Sprite:** Moeda escura com brilho suave.  
**Colisores:** Apenas corpo (trigger).  
**Fontes de áudio:** Som metálico leve ao ser coletada.  
**Script:** Ao tocar o player, desaparece e incrementa o contador de moedas.

---

### Poção de Vida  
**Desc:** Item que restaura parte da vida do jogador ao ser coletado.  
**Onde:** Dropada por alguns inimigos, encontrada em baús ou locais secretos.  
**Sprite:** Poção vermelha com aura fraca.  
**Colisores:** Apenas corpo (trigger).  
**Fontes:** Som líquido suave ou brilho mágico ao ser coletada.  
**Script:** Ao encostar, desaparece e adiciona vida ao jogador. Pode ser ignorada ou armazenada se a vida estiver cheia.

