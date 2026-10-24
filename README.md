# Portfólio de programação, análise de dados e física

Repositório de projetos acadêmicos e estudos desenvolvidos com Python. O objetivo é reunir os trabalhos em uma estrutura clara, documentar suas dependências e distinguir projetos prontos para exploração de exercícios que ainda precisam de dados ou revisão.

## Projetos em destaque

### 1. Análise exploratória de crédito PJ
Notebook de análise exploratória com geração reproduzível de uma base **inteiramente sintética** de 1.500 empresas fictícias. Inclui auditoria de dados, tratamento explícito de ausências, criação de indicadores, comparação entre grupos e visualizações.

- [Abrir o notebook](projetos/credito-pj/analise_credito_pj.ipynb)
- [Notas do projeto](projetos/credito-pj/README.md)

**Limitação importante:** o rótulo de deterioração é simulado por regras definidas no próprio notebook. Os resultados são didáticos e não representam uma carteira bancária real nem evidência sobre o mercado.

### 2. Física experimental
Análises de difração, lei de Brewster e polarização, com ajuste de curvas e visualizações.

- [Difração](projetos/fisica-experimental/difracao/difracao.ipynb)
- [Lei de Brewster](projetos/fisica-experimental/lei-de-brewster/lei_de_brewster.ipynb)
- [Polarização](projetos/fisica-experimental/polarizacao/polarizacao.ipynb)

**Atenção:** o notebook da lei de Brewster depende de `ANGLE-VOLTS.xlsx`, que não estava no ZIP recebido e, portanto, não foi incluído.

### 3. Simulações quânticas com QuTiP
Notebooks de beam splitter com dissipação e squeezing de dois modos.

- [Beam splitter com dissipação](projetos/simulacoes-quanticas/beamsplitter_dissipacao.ipynb)
- [Squeezing com dissipação](projetos/simulacoes-quanticas/squeezing_dissipacao.ipynb)
- [Two-mode squeezing](projetos/simulacoes-quanticas/two_mode_squeezing.ipynb)

O notebook de squeezing com dissipação foi ajustado para passar os operadores de colapso ao solucionador. Como essa alteração não foi reexecutada neste ambiente, execute todas as células antes de usar os resultados desse notebook.

### 4. Exercícios de programação
- [EP3 — gestão de estoque](projetos/programacao/ep3_gestao_estoque/ep3_gestao_estoque.ipynb): mantida a versão mais recente do código, removidas iterações duplicadas e corrigida a condição de execução principal.
- [EP2 — rascunho em desenvolvimento](projetos/programacao/rascunhos/EP2_em_desenvolvimento.ipynb): preservado para referência, mas **não está pronto para execução** e não deve ser apresentado como projeto concluído.

Os arquivos CSV usados por EP2 e EP3 não estavam no ZIP recebido. Eles não foram inventados nem adicionados ao repositório.

## Como executar

Recomenda-se Python 3.10 ou superior.

```bash
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências:

```bash
pip install -r requirements.txt
```

Abra os notebooks com Jupyter:

```bash
jupyter lab
```

Os notebooks que dependem de arquivos externos só poderão ser executados integralmente quando esses arquivos forem disponibilizados na pasta indicada no README do respectivo projeto.

## Estrutura

```text
projetos/
├── credito-pj/
├── fisica-experimental/
│   ├── difracao/
│   ├── lei-de-brewster/
│   └── polarizacao/
├── programacao/
│   ├── ep3_gestao_estoque/
│   └── rascunhos/
└── simulacoes-quanticas/
```

## Antes de publicar

- Confira se você tem autorização para compartilhar todos os dados experimentais e materiais acadêmicos.
- Não adicione dados pessoais, arquivos privados ou planilhas que não possam ser redistribuídas.
- Revise os READMEs específicos para saber quais notebooks dependem de arquivos externos.
- Nenhuma licença foi escolhida automaticamente. Se quiser permitir reutilização do código por terceiros, escolha uma licença antes de publicar.
