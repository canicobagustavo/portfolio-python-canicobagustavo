# Análise exploratória de crédito PJ

## Objetivo
Demonstrar um fluxo de análise exploratória em Python: geração de dados reproduzíveis, auditoria de qualidade, tratamento de valores ausentes, criação de indicadores, comparação entre grupos e comunicação de resultados.

## Dados
O notebook gera localmente 1.500 registros sintéticos com uma semente fixa. Nenhum dado de cliente ou carteira real é utilizado.

## Como executar
Instale as dependências da raiz do repositório e execute todas as células do notebook, de cima para baixo.

## Limitações
- O indicador `cliente_em_deterioracao` é um rótulo artificial criado a partir de regras explícitas no notebook.
- Parte das associações encontradas foi incorporada na própria simulação; os resultados não validam hipóteses sobre carteiras reais.
- As taxas por setor, porte e estado são apenas descrições da amostra sintética.
- O saldo devedor não deve ser interpretado como perda esperada. Uma estimativa de perda exigiria, entre outros elementos, probabilidade de inadimplência, exposição e severidade da perda.
