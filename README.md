# Simulador de Financiamento

Simulador web para estimar financiamento pessoal com comparação entre os sistemas de amortização SAC e PRICE.

## Objetivo

O projeto ajuda a analisar:
- valor do empréstimo
- renda mensal
- prazo desejado
- taxa de juros anual
- limite de comprometimento de até 30% da renda

A partir desses dados, o simulador calcula e compara as parcelas, juros totais e custo final de cada modelo.

## Funcionalidades

- cálculo automático de parcela máxima com base em 30% da renda
- comparação entre SAC e PRICE
- sugestão de prazo mínimo para manter a parcela dentro do limite
- gráficos de evolução das parcelas
- tabela detalhada de amortização mensal
- busca da taxa Selic atual via API do Banco Central

## Como usar

1. Abra o arquivo `index.html` em um navegador.
2. Preencha os campos:
   - valor do empréstimo
   - renda mensal
   - prazo desejado (opcional)
   - taxa de juros anual
3. Clique em "SIMULAR FINANCIAMENTO".
4. Analise o resultado comparando os valores de SAC e PRICE.

## Tecnologias

- HTML
- CSS
- JavaScript
- Chart.js

## Observação

Este projeto é uma ferramenta de simulação educacional e não substitui análise financeira profissional.

## Estrutura do projeto

- `index.html` — interface e lógica do simulador
- `README.md` — documentação do projeto