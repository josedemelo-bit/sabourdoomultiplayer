# DOOM Multiplayer

## Teste local
`npm install` e depois `npm start`. Abra http://localhost:10000 em duas janelas.

## Render grátis
Envie esta pasta para um repositório GitHub. No Render: **New → Web Service**, conecte o repositório, Build Command `npm install`, Start Command `npm start` e plano **Free**.

O jogo escolhe automaticamente `ws://` ou `wss://`.

Esta primeira versão sincroniza presença, posição e direção dos jogadores. Inimigos, tiros e pontuação continuam locais; isso pode ser sincronizado numa segunda etapa.
