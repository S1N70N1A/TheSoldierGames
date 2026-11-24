# TheSoldier Games

Site de mini-jogos em HTML, CSS e JavaScript puro. Não precisa de servidor, frameworks ou internet depois de baixar.

## Executar no Termux

1. Instale o Termux e, se necessário, um navegador.
2. Entre na pasta onde está `index.html`.
3. Abra o arquivo no navegador:

```bash
termux-open index.html
```

Se `termux-open` não estiver disponível, instale o complemento/API do Termux ou abra o arquivo pelo gerenciador de arquivos do Android.

## Opcional: servidor local

```bash
pkg update
pkg install python -y
cd /caminho/para/thesoldier_games
python -m http.server 8000
```

Depois, abra `http://127.0.0.1:8000` no navegador do celular.

## Jogos incluídos
- Neon Racer (corrida)
- Aventura na Caverna (aventura)
- Block Builder (construção de blocos)
- Space Defender (arcade espacial fictício)
- Memória Pixel (pares)
- Pênalti de Ouro (futebol)
- Snake Classic (clássico)

Os jogos são protótipos locais e não incluem contas, pagamentos, multiplayer ou backend.
