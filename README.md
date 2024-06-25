## Descrição do Projeto

Este projeto visa validar habilidades em SQL para uma vaga de estágio em Risco. Utilizando o DuckDB, os dados do arquivo "Teste SQL.xlsx" são importados e transformados em formato longo para análise. São ajustadas retas de regressão linear para as consultas, obtendo interceptos e inclinações. Além disso, é calculada a soma das observações das seis primeiras consultas. A análise inclui também uma visualização gráfica das retas ajustadas para as consultas de 1 a 11.

## Ferramentas Utilizadas

- **DuckDB**: Banco de dados utilizado para execução de comandos SQL.
- **Pandas**: Biblioteca para manipulação de dados, utilizada para ler a planilha original.
- **Google Colab**: Plataforma utilizada para executar o código.
- **Seaborn** e **Matplotlib**: Bibliotecas para visualização gráfica.

### Análise de Dados

- **Conexão e Criação de Tabelas**: Utilização do DuckDB para criar tabelas a partir dos dados e realizar operações SQL.
- **Transformação em Formato Longo**: Necessário para ajustar retas de regressão linear usando REGR_SLOPE e REGR_INTERCEPT.
- **Ajuste das Retas de Regressão**: Obtidos interceptos e inclinações para as consultas divididas em dois grupos.
- **Soma das Observações**: Cálculo das observações das seis primeiras consultas usando SUM no SQL.
- **Visualização Gráfica**: Plotagem das retas ajustadas para as consultas de 1 a 11 usando Seaborn e Matplotlib.

### Referências

- Análise estatística: Métodos de regressão linear e operações SQL para transformação e análise dos dados.
