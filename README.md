# Espelho de Lugares — Ace Gaming

Mapa interativo de assentos do escritório da Ace Gaming (R. Olimpíadas, 134 — 3º andar).

Aplicação estática em um único arquivo (`index.html`), sem dependências externas — basta abrir no navegador ou publicar em qualquer hospedagem de arquivos estáticos.

## Funcionalidades

- **3 layouts de planta**: layout atual (49 lugares), **49 — Layout Aprovado** (planta Apostou sem as cadeiras de expansão) e **61 — Expansão** (planta Apostou com as 12 cadeiras laranjas do meio das mesas leste)
- **Alocação de pessoas**: clique na pessoa e depois na cadeira, ou arraste e solte
- **Auto-alocação** dos não alocados, com preferência de zona por área
- **Filtros por modelo de trabalho** (Presencial + Híbrido, Remoto, Remoto c/ cidade, Vagas) e busca por nome, cargo ou área
- **Importação e exportação de CSV** da lista de assentos
- **Impressão** do mapa com a lista de assentos
- As alocações ficam salvas no navegador (localStorage), separadas por layout
- **Espelho oficial fixado no arquivo** (`PRESET` no `index.html`): aplicado a quem abre o app
  sem estado salvo — assim a estrutura de alocação é preservada ao compartilhar o link.
  Para atualizar, use o botão **Exportar alocações** e substitua o objeto `PRESET` pelo código gerado
