# TEPro OS

**[English](README.en.md)**

**Menu do Turbo EverDrive PRO (PC Engine / TurboGrafx-16) em português, com capas dos jogos, cheats prontos e plano de fundo personalizado — e um aplicativo que deixa o cartão SD pronto em poucos cliques.**

Um projeto do blog **[Maniaco Game Room](https://www.maniacogameroom.com.br/)**.

![Lista de jogos com a capa ao lado](imagens/menu-lista-capa.png)

## O que o TEPro OS traz

| | |
|---|---|
| ![Menu principal](imagens/menu-principal.png) | ![Editor de cheats](imagens/menu-cheats.png) |
| ![Detalhes do aparelho](imagens/menu-detalhes.png) | ![Tela Sobre](imagens/menu-sobre.png) |

- **Menu inteiro em português**, com acentos (á, ã, ç, é…). Também disponível com os textos originais em inglês.
- **Capa de cada jogo** ao lado da lista.
- **Cabeçalho** com o nome TEPro OS e a bandeira do Brasil; página à direita.
- **Lista limpa:** sem a extensão dos arquivos (`.pce`, `.sgx`, `.cue`).
- **Cheats prontos** para centenas de jogos de HuCard e CD, inclusive para **CD original** (testado num Turbo Duo).
- **Plano de fundo** com a imagem que você quiser e **temas** para trocar pelo próprio console.
- **Tensão da bateria** do relógio na tela de detalhes.

## O aplicativo: Gerenciador do SD

![Aplicativo](imagens/app-preparar.png)

Com o cartão no PC, poucos cliques:

1. instala o menu TEPro OS (baixa o firmware oficial do site da Krikzz e adapta no seu PC);
2. copia seus jogos, inclusive de `.zip`, com o **nome oficial** e organizados por **região e letra**;
3. **corrige ROMs americanas** que davam tela branca;
4. gera as **capas**;
5. grava os **cheats**;
6. copia a **BIOS do CD** que você tiver.

O aplicativo funciona em **português ou inglês** (menu Idioma / Language). Também organiza um cartão que já está pronto e troca o plano de fundo do menu. **Nada é apagado:** tudo o que é substituído vai para uma pasta de backup, e a organização pode ser desfeita.

| | |
|---|---|
| ![Organizar jogos](imagens/app-organizar.png) | ![Plano de fundo](imagens/app-fundo.png) |

## Como usar

1. Baixe o **`TEPro-OS-Gerenciador.exe`** na página de **[Releases](../../releases)**.
2. Coloque o cartão do EverDrive no PC (formatado em **FAT32**).
3. Abra o aplicativo, escolha o cartão e clique em **Preparar cartão**.
4. Coloque o cartão no EverDrive e ligue o console.

Passo a passo completo, com todas as opções: **[Manual do aplicativo](MANUAL.md)**.

## Requisitos

- **Turbo EverDrive PRO** original da Krikzz (firmware v26.0923). Cartuchos genéricos "Turbo EverDrive" vendidos em lojas on-line usam outro sistema e **não** são compatíveis.
- Windows 10 ou 11.
- Cartão microSD em FAT32.
- Internet na primeira vez (firmware, capas e cheats são baixados e ficam guardados no PC).

## Aviso

O TEPro OS **não distribui o firmware da Krikzz**: o aplicativo baixa o arquivo oficial de [krikzz.com](https://krikzz.com) e aplica as mudanças no seu computador. Turbo EverDrive PRO, seu firmware e seu menu original são de Igor Golubovskiy (Krikzz). Este projeto não é afiliado à Krikzz. ROMs e BIOS não são fornecidas.

## Créditos

- Turbo EverDrive PRO e firmware original: **Krikzz** — [krikzz.com](https://krikzz.com)
- Capas: [libretro-thumbnails](https://github.com/libretro-thumbnails)
- Cheats e bancos de jogos (No-Intro / Redump): [libretro-database](https://github.com/libretro/libretro-database)

## Licença

**Freeware — uso gratuito. © 2026 Maniaco Game Room. Todos os direitos reservados.** Veja a [licença](LICENCA.md) e os [componentes de terceiros](TERCEIROS.md).

Encontrou um problema? Abra uma [Issue](../../issues).
