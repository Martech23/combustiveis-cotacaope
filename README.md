# ⛽ Combustíveis Cotação • Recife

Protótipo premium de site de cotação de combustíveis em tempo real para Recife e Grande Recife.

## ✨ Funcionalidades

- **Preços médios** do dia com variação semanal
- **Tabela interativa** com 12+ postos de Recife e região
  - Busca por nome ou bairro
  - Ordenação por preço
  - Filtro em tempo real
- **Mapa interativo** com Leaflet (marcadores clicáveis)
- **Painel para donos de posto** — atualize preços em menos de 30 segundos
  - Atualização instantânea na tabela e no mapa
- Exportação do arquivo `data.js` para uso em produção
- Design premium dark mode com gradientes violeta/fúcsia
- Totalmente responsivo
- Funciona 100% offline (após carregamento inicial)

## 🚀 Deploy (Vercel + GitHub)

Este projeto é um site estático simples (apenas `index.html`).

### Passo a passo para colocar no ar:

1. **Crie um repositório no GitHub**
   ```bash
   git init
   git add .
   git commit -m "feat: site de cotação de combustíveis Recife"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/combustiveis-cotacao.git
   git push -u origin main
