# Pênalti

Disputa de pênaltis em pixel art isométrico, no navegador. JavaScript puro com rasterizador próprio: sem build, sem dependências, sem sprites.

## Rodar
Requer [Node.js](https://nodejs.org/).

```bash
node serve.mjs
```

Abra http://127.0.0.1:5300/. Qualquer servidor de arquivos estáticos serve.

## Como jogar
- **Batendo:** mire no gol com o mouse ou o dedo, segure para encher a força e solte para chutar. Força demais manda a bola por cima. Teclado: setas miram, segure espaço.
- **No gol:** toque no ponto do gol para onde quer pular. Pular antes do chute deixa o batedor trocar de canto. Teclado: ← → ↑ ↓.
- 5 cobranças para cada lado, depois alternadas.

## Créditos
- `engine.js` e `shell.js` vêm do [Pixel Plays](https://github.com/amirmushichge/pixel-plays) de Amir Mushich, sob licença MIT (ver [LICENSE](LICENSE)).
- O jogo (`penalti/`) foi feito por Pedro.
