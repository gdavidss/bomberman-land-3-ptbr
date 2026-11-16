# Bomberman Land 3 em Português (PS2)

Tradução de fã para português do Brasil de **Bomberman Land 3** (PlayStation 2, Japão, SLPM-62643), lançado só no Japão em 2005.

Estão traduzidos os diálogos de todos os personagens, os menus, os itens, os textos desenhados nas texturas, os mangás, as mensagens do modo batalha e o teclado de nome, que agora tem letras latinas com acento.

Este repositório não contém o jogo. Ele traz um patch que transforma a sua cópia japonesa na versão em português.

## Como aplicar

Você precisa da ISO japonesa original, com este SHA-1:

```
18b28c04356378540e71258fdbe4fd9564e733d8
```

Baixe o arquivo `Bomberman Land 3 PT-BR.xdelta` na página de [Releases](../../releases) e aplique de um destes jeitos.

- **No navegador**, pelo [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/). Escolha a ISO, escolha o patch e salve.
- **No Windows**, pelo [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher).
- **No terminal**, com o xdelta3:

```
xdelta3 -d -s "Bomberman Land 3 (Japan).iso" "Bomberman Land 3 PT-BR.xdelta" "Bomberman Land 3 PT-BR.iso"
```

Se tudo deu certo, a ISO traduzida tem este SHA-1:

```
0346ad1cf0461cd8b1e3e372cf4696cdee12b258
```

## Como jogar

Abra a ISO traduzida no [PCSX2](https://pcsx2.net) 2.x com a BIOS do seu próprio PS2.

Projeto de fã, sem fins lucrativos e sem ligação com a Hudson Soft ou a Konami.
