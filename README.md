# Modo Multiplayer

Ninguém zera tech no modo solo.

Fernanda dos Santos · [@masbahguriatech](https://www.instagram.com/masbahguriatech/)

## Sobre a talk

Todo mundo já pensou "isso não é pra mim". Na véspera da prova, no exercício
que não sai, no primeiro dia num lugar onde ninguém parece contigo. A boa
notícia: tecnologia não é jogo de um jogador só.

Essa talk é uma palestra-jogo pra galera do ensino médio e do técnico em TI.
A sala inteira vira um time: a gente cumpre missões juntos, enche uma barra de
XP e enfrenta o chefão mais difícil de qualquer carreira, o medo.

No caminho eu conto a minha história: de vender colchão no shopping aos 19
até coordenar o GDG Porto Alegre e subir em palco. A virada não veio sozinha.
Veio de uma professora que disse que eu podia mais, de um meetup na faculdade
(quando tecnologia ainda era quase tudo novidade pra mim) e de uma comunidade
inteira.

### As fases

- **Start:** regras do jogo e um "levanta a mão quem…" sobre estudo, desânimo
  e o famoso "isso não é pra mim".
- **Fase 1, a origem:** de onde eu vim e a frase que mudou a minha rota.
- **Fase 2, monta teu time:** rede de apoio, comunidade e networking não são a
  mesma coisa. Tem conversa de 60 segundos com quem tá do lado e quiz de mito
  ou verdade.
- **Fase 3, cuida do teu personagem:** organização de estudo, trabalho (pra
  quem procura vaga e pra quem já trabalha) e tempo pra si. E automotivação:
  começar pequeno, meta que dá pra riscar, registrar o progresso.
- **Fase 4, o chefão:** um papo reto pra quem sente que não pertence, com um
  carinho especial pras gurias. O medo vira chefão e cai com quatro power-ups:
  perguntar, levar alguém junto, aparecer e ajudar quem vem atrás.
- **Final:** cada pessoa monta o seu plano (ponto de apoio, comunidade, missão
  diária e recarga), a turma destrava o final secreto e sai com três itens no
  inventário pra segunda-feira.

A frase que fica: **tu pode mais. E não vai só.**

## Como apresentar

O deck é HTML puro, sem build. São 19 slides em 16:9. É só abrir o
`index.html` no navegador, ou subir um servidor local:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

Clica uma vez na tela logo no começo: é isso que libera o som no navegador.

| Tecla | Ação |
| --- | --- |
| `→` `↓` `espaço` `PageDown` | próximo passo / slide |
| `←` `↑` `PageUp` | volta |
| `M` | liga e desliga a música |
| `N` | mostra as notas de fala |
| `F` | tela cheia |
| `Home` / `End` | primeiro / último slide |

Passador de slide funciona direto (ele manda PageUp/PageDown).

### O que acontece na tela

- Barra de **XP da turma** no alto: enche a cada missão cumprida, com som e
  animação. Em 100 tem level up e o final secreto.
- **Cronômetros** de verdade nas missões 2 e 4, com tique-taque nos últimos
  segundos.
- O **chefão** perde vida a cada power-up.
- A trilha e os efeitos são gerados no próprio navegador, então não precisa de
  internet pra tocar. Só as fontes vêm do Google Fonts.

## Arquivos

```
index.html   o deck inteiro (HTML + CSS + JS)
npc.webp     a minha personagem
qr.png       QR code do último slide (meu Linktree)
```

## Quer editar?

Cada slide é uma `<section class="slide">`, na ordem, com o número comentado
em cima. As notas de fala ficam no `<aside class="notes">` de cada slide.
Cores ficam nas variáveis do `:root`, lá no topo do `<style>`.

Os passos que aparecem a cada clique têm a classe `step`. Quem dá XP leva
`data-xp`, quem tira vida do chefão leva `data-hit` e quem dispara cronômetro
leva `data-timer`.

O palco tem 1920×1080 fixo e é escalado pra caber em qualquer tela.

## Bora conversar

Se tu entrar numa comunidade depois dessa talk, eu quero saber 💜

- Instagram: [@masbahguriatech](https://www.instagram.com/masbahguriatech/)
- LinkedIn: [linkedin.com/in/fernanda-dossantos](https://www.linkedin.com/in/fernanda-dossantos)
- Linktree: [linktr.ee/masbahguriatech](https://linktr.ee/masbahguriatech)
