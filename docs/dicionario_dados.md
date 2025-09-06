# 📚 Dicionário de Dados

## Estrutura dos Dados

| Campo | Tipo de Dado | Formato/Exemplo | Descrição | Valores Possíveis |
|-------|-------------|----------------|-----------|------------------|
| **tipo_de_clientes** | Texto (String) | Governo, Pequenas Empresas | Segmentação do cliente por categoria | Governo, Médias Empresas, Vendas Online, Grandes Empresas, Pequenas Empresas |
| **pais** | Texto (String) | Alemanha, Canadá | País onde a venda foi realizada | Alemanha, Canadá, França, Chile, EUA |
| **produto** | Texto (String) | Produto 1, Produto 2 | Identificação do produto vendido | Produto 1, Produto 2, Produto 3, Produto 4, Produto 5, Produto 6 |
| **valor_total** | Numérico (Decimal) | 26420, 529550 | Valor bruto da venda em USD | Valores numéricos positivos |
| **desconto** | Numérico (Decimal) | 0, 18.41, 20762 | Valor do desconto concedido em USD | Valores numéricos ≥ 0 |
| **valor_total_desconto** | Numérico (Decimal) | 26420, 1822.59 | Valor líquido da venda (após desconto) | Valores numéricos positivos |
| **custo_total** | Numérico (Decimal) | 14531, 432718 | Custo total dos produtos vendidos em USD | Valores numéricos positivos |
| **lucro** | Numérico (Decimal) | 11889, 96832, -957 | Lucro da operação (valor líquido - custo) | Valores numéricos (pode ser negativo) |
| **data** | Data | 01/01/2019, 01/12/2019 | Data da transação | DD/MM/AAAA |
| **mes** | Texto (String) | Janeiro, Dezembro | Nome do mês da transação | Janeiro, Fevereiro, Março, Abril, Maio, Junho, Julho, Agosto, Setembro, Outubro, Novembro, Dezembro |
| **ano** | Numérico (Inteiro) | 2018, 2019 | Ano da transação | 2018, 2019 |
