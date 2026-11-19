# GDE — Atualizações do aplicativo

Este repositório público é usado exclusivamente para distribuir versões do aplicativo desktop **GDE — Gestor de Operações Quero-Quero**.

- **Linux:** AppImage (atualização automática).
- **Windows:** instalador NSIS (atualização automática).
- Os releases também podem incluir RPM para instalação manual.
- Os arquivos `latest-linux.yml` e `latest.yml` são metadados necessários ao mecanismo de atualização do Electron.

## Código-fonte

O código-fonte do GDE não está neste repositório. Ele permanece no repositório privado [Estoque657/gde-quero-quero](https://github.com/Estoque657/gde-quero-quero).

Este repositório contém somente instaladores/binários, checksums e metadados de atualização gerados pelo processo de compilação. Não publique aqui código-fonte, frontend, configurações internas, credenciais ou dados operacionais.

## Downloads

Consulte a aba [Releases](https://github.com/Estoque657/gde-quero-quero-updates/releases) para baixar os instaladores disponíveis.

O atualizador consulta os releases públicos e valida os arquivos pelos metadados SHA-512 gerados no empacotamento. Nenhum token de acesso é distribuído com o aplicativo.
