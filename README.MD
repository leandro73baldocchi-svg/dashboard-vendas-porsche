Atue como um Desenvolvedor Front-End Sênior e Especialista em Data Visualization.
Crie uma Dashboard interativa em um arquivo único HTML (`index.html`), contendo HTML5, CSS3 (via TailwindCSS CDN) e JavaScript puro com a biblioteca Chart.js (via CDN).

1. Identidade Visual (Estilo Porsche Luxury Dark)
- Fundo principal em tom escuro profundo (#0d0d0f) e cards em cinza grafite (#16181d) com bordas sutis (#262930).
- Cor de destaque: Vermelho Porsche (#d5001c) e detalhes em Prata/Branco (#f3f4f6).
- Tipografia limpa e moderna (Inter ou Montserrat via Google Fonts).

2. Estrutura de Dados
- Embuta os dados da planilha diretamente em uma constante JavaScript `const salesData = [...]`.
- Ignore ou trate registros que contenham o valor "INVALID".

3. Filtros Interativos (No topo)
- Select para Modelo (Todos + lista dinâmica dos modelos).
- Select para Estado/Cidade (Todos + lista dinâmica).
- Select para Ano (Todos + lista dinâmica).
- Select para Método de Pagamento (Todos + lista dinâmica).
- Botão "Limpar Filtros".
- Todos os filtros devem recalcular os KPIs e atualizar os gráficos em tempo real.

4. Indicadores de Topo (KPIs)
- Receita Total (formatada em R$ BRL).
- Total de Veículos Vendidos (quantidade).
- Ticket Médio por Venda (R$ BRL).
- Modelo Mais Vendido (destaque dinâmico).

5. Gráficos (Respondendo às 3 Perguntas de Negócio)
- Gráfico 1 (Barras Horizontais): Receita Total por Modelo (Pergunta 1: Quais modelos puxam o faturamento?).
- Gráfico 2 (Colunas): Top 10 Cidades/Estados em Vendas (Pergunta 2: Onde estão os maiores mercados?).
- Gráfico 3 (Rosca/Donut): Distribuição por Método de Pagamento (Pergunta 3: Qual o perfil financeiro de compra?).
- Gráfico 4 (Linha): Evolução da Receita por Ano do Modelo/Venda.