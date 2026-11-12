# ♻️ Recicla com os Play Bots

Jogo infantil sobre reciclagem. A criança escolhe um Play Bot, aprende as cores das lixeiras
e arrasta cada item (papel, plástico, vidro, metal, orgânico) até a lixeira certa.

🎮 **Jogar online:** `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Como funciona

- 10 itens por partida, sorteados aleatoriamente
- Arraste o item até a lixeira ou toque nela
- Pontuação: 10 pts (acerto de primeira), 5 (segunda tentativa), 2 (terceira) + bônus de sequência 🔥
- Dicas aparecem após 2 erros no mesmo item
- Narração por voz (Web Speech API, em pt-BR) e efeitos sonoros, com botão para silenciar
- Recorde salvo no navegador (`localStorage`)
- Suporta modo escuro e respeita `prefers-reduced-motion`

## Estrutura

```
.
├── index.html          # página principal
├── css/style.css       # estilos
├── js/game.js          # lógica do jogo
└── assets/img/         # personagens e logo
```

## Rodar localmente

Não precisa instalar nada. Abra o `index.html` no navegador, ou, se preferir um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Publicar no GitHub Pages

1. Envie os arquivos para um repositório no GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`
4. Salve e aguarde cerca de 1 minuto. O link do jogo aparece na própria tela

## Observações

- A fonte *Baloo 2* é carregada do Google Fonts (precisa de internet; sem ela, o jogo usa uma fonte padrão)
- Os personagens e o logo "It's Play" pertencem aos seus respectivos autores. Confirme que você
  tem autorização de uso antes de tornar o repositório público
