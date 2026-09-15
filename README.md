# SalesInsight PY

Mini projeto de análise de dados de vendas desenvolvido em Python, com foco em um fluxo completo de preparação, análise e geração de insights a partir de dados sintéticos.

## Sobre o projeto

O projeto demonstra um pipeline de análise de vendas que parte da geração de um conjunto de dados sintético com inconsistências e passa por etapas de inspeção, limpeza, transformação, cálculo de métricas, análise avançada e exportação de resultados.

O material está concentrado no notebook `salesinsight.ipynb`.

## Fluxo do projeto

1. **Geração dos dados**
   - Criação de um dataset sintético de vendas.
   - Inclusão proposital de dados inconsistentes para simular um cenário real de análise.

2. **Inspeção e limpeza**
   - Verificação da estrutura do DataFrame.
   - Identificação de valores nulos e dados inválidos.
   - Padronização de campos textuais.
   - Tratamento das datas.
   - Remoção de registros inadequados para a análise.

3. **Transformação dos dados**
   - Criação de variáveis derivadas.
   - Cálculo da receita total por venda.
   - Classificação das vendas por faixa de receita.
   - Criação de indicadores relacionados ao volume de vendas.

4. **Métricas de vendas**
   - Evolução das vendas por mês.
   - Produtos com maior receita.
   - Receita por categoria.
   - Desempenho por região.
   - Quantidade vendida e outras métricas agregadas.

5. **Análise avançada**
   - Uso de Programação Orientada a Objetos.
   - Extensão do analisador por meio de herança.
   - Projeções e análises adicionais.
   - Tabelas cruzadas, segmentação de clientes e estatísticas com NumPy.

6. **Visualização e exportação**
   - Geração de gráficos e um painel de resumo.
   - Exportação das métricas e resultados para formatos como CSV e JSON.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Arquivos

```text
salesinsight/
├── README.md
└── salesinsight.ipynb
```

## Como executar

### Google Colab

Envie o arquivo `salesinsight.ipynb` para o Google Colab e execute as células em sequência.

### Jupyter Notebook

Com Python e as dependências instaladas, abra o notebook:

```bash
jupyter notebook salesinsight.ipynb
```

## Dependências

As principais bibliotecas utilizadas pelo projeto são:

```bash
pip install pandas numpy matplotlib
```

## Objetivo

O objetivo do projeto é apresentar, de forma prática, um fluxo de análise de dados de vendas que contemple desde a preparação dos dados até a geração de métricas e insights para tomada de decisão.

## Observação

O notebook foi mantido sem alterações no código original. A organização do pacote foi ajustada apenas para melhorar a identificação dos arquivos e a documentação do projeto.
