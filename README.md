# Pixel Plays

Jogos de navegador em pixel art isométrico. JavaScript puro com rasterizador próprio: sem build, sem dependências, sem sprites.

## Jogos
| Jogo | O que fazer | Controle |
|------|-------------|----------|
| [Pênalti](penalti/) | Disputa de pênaltis: bata 5 e defenda 5, depois alternadas | Mire, segure e solte; no gol, toque onde pular |
| [Quadra NY](quadra/) | 60 segundos numa quadra de rua em Nova York, com marcador | Arraste pra trás e solte; espaço |

## Rodar
Requer [Node.js](https://nodejs.org/).

```bash
node serve.mjs
```

Abra http://127.0.0.1:5300/. Qualquer servidor de arquivos estáticos serve.

## Créditos
- `engine.js` e `shell.js` vêm do [Pixel Plays](https://github.com/amirmushichge/pixel-plays) de Amir Mushich, sob licença MIT (ver [LICENSE](LICENSE)).
- `vendor/pixelfx/` vem do [pixelfx](https://github.com/patch-gg/pixelfx), sob licença MIT (ver [vendor/pixelfx/LICENSE](vendor/pixelfx/LICENSE)).
- Os jogos (`penalti/`, `quadra/`) foram feitos por Pedro.
