# Simulações quânticas com QuTiP

Os notebooks exploram a evolução temporal de dois modos em modelos de beam splitter e squeezing.

## Dependências
Instale as dependências listadas em `requirements.txt`. O código original utiliza sintaxe de notebook/IPython em algumas células.

## Observação de validação
O notebook `squeezing_dissipacao.ipynb` teve uma correção no argumento do solucionador para incluir `c_ops`, a lista de operadores de colapso definida no código. Os resultados anteriores foram removidos porque correspondiam à execução sem esses operadores. O notebook precisa ser executado novamente em um ambiente com QuTiP antes de os resultados serem considerados validados.
