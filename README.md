# R36SPORTSBR-STORE-UPDATES
Port experimental do R36SPORTSBR STORE HUB  para R36S, com suporte a dArkOS, dArkOSRE, dArkOSen e dArkOS4Clone.

## Canal público de atualizações

Este repositório distribui **somente atualizações da R36SPORTSBR STORE**. O código de desenvolvimento continua separado em `JammesPark/R36SPORTSBR-STORE-HUB`.

- O `update.json` informa versão, URL, tamanho, SHA-256 e novidades.
- Cada Release conterá **dois ZIPs correspondentes**: instalação do console e código-fonte completo.
- O manifesto será publicado **após** a Release e a verificação dos arquivos.
- **Não** contém ROMs, BIOS proprietárias ou arquivos de jogos comerciais.
- O catálogo R36S BR e o catálogo do Lag do Lira permanecem separados.

**Estado:** aguardando a primeira Release verificada. Nenhuma atualização está ativa por enquanto.

### Autoria e licença

Baseado no **R36S PORT HUB, por Lag do Lira**, sob **GNU GPL-3.0**. O pacote de código-fonte de cada Release incluirá as licenças e os créditos originais.

## Canal separado — R36S ROMS STORE

Existe um canal independente de atualizações para **R36S ROMS STORE** em
[roms-store/update.json](roms-store/update.json). Ele só distribui Releases com
tags **roms-vX.Y.Z-beta**, com nomes e hashes próprios. O arquivo principal
[update.json](update.json) continua reservado ao **R36SPORTSBR STORE HUB**.

O canal da ROMS STORE começa com status aguardando publicação e só passa a
informar uma versão depois de todos os pacotes terem sido publicados e
verificados pelo workflow do repositório de desenvolvimento correspondente.
