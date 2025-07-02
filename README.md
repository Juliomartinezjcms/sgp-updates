# SGP Updates - Servidor de Atualizações

Este repositório serve como servidor de atualizações para o plugin **SGP Integrado**.

## Estrutura

- `sgp-integration.zip` - Arquivo do plugin compactado
- `update.json` - Informações de atualização para o WordPress

## Como funciona

O plugin WordPress verifica periodicamente este repositório para novas versões. Quando uma nova versão é detectada, o WordPress baixa automaticamente o arquivo ZIP e instala a atualização.

## URL de Acesso

Após configurar o GitHub Pages, a URL será:
`https://[seu-usuario].github.io/sgp-updates/`

## Atualizando o Plugin

1. Faça as alterações no código do plugin
2. Compacte a pasta do plugin em `sgp-integration.zip`
3. Atualize o `update.json` com a nova versão
4. Faça upload dos arquivos para este repositório
5. Os usuários receberão a atualização automaticamente 