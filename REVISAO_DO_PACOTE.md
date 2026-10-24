# Registro de revisão

## Base de trabalho
O conteúdo foi organizado em pastas e recebeu documentação em português.

## Ajustes aplicados
- Criada estrutura de pastas por área e documentação principal.
- Mantido o notebook de crédito PJ recebido, sem gerar uma nova análise.
- Adicionadas introduções em Markdown aos notebooks de física e simulação.
- Removida a célula de upload exclusiva do Google Colab do notebook da lei de Brewster; adicionadas instruções para o arquivo `ANGLE-VOLTS.xlsx`.
- Corrigido o uso de `c_ops` no solucionador do notebook de squeezing com dissipação; os resultados antigos desse notebook foram removidos para evitar exibir saídas de uma execução que já não corresponde ao código.
- Organizado o EP3 usando a implementação mais recente, removendo versões intermediárias duplicadas e corrigindo a condição de execução principal.
- Preservado o EP2 em pasta de rascunhos, com indicação explícita de que contém erros e está incompleto.
- Criados `requirements.txt`, `.gitignore` e instruções de publicação.

## Limitações que permanecem
- Não foram fornecidos `ANGLE-VOLTS.xlsx`, `produtos.csv`, `clientes.csv`, `compras.csv`, `inventario.csv`, `operacoes.csv` ou `lojas.csv`. Os notebooks dependentes desses arquivos não foram executados integralmente.
- Não foi possível executar novamente as simulações QuTiP neste ambiente; o notebook de squeezing com dissipação precisa ser executado e conferido.
- O EP2 continua intencionalmente sem correção ampla: foi classificado como rascunho, em vez de se inventar uma implementação que poderia mudar o trabalho original.
- Nenhuma licença foi escolhida, e nenhum repositório remoto foi criado/publicado automaticamente.
