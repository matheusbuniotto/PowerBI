
### DAX

#### Categorias de funções Dax

-SUMX()
cria contexto e retorna uma soma
Contexto; 

SUMX é uma função iterante, vai realizar o cálcula para cada linha dentro da expressão e contexto.

Melhor prática é utilizar medidas calculadas ao invés de colunas quando temos essa opção.

Criar tabela parâmetro

-RELATED

Tabela parâmetro
- Novo parâmetro (cria tabela virtual do Dax)

- Medidas dinâmicas


#### Inteligência de Tempo
- SAMEPERIODLASTYEAR
Retorna um valor do mesmo período do ano anterior

- DATEADD
  Permite personalizar periodo e quantidade nos argumentos

- TOTALYTD 
Acumula valores dos meses de acordo com o contexto de filtro (não precisa do calculate)
- TOTALQTD (trimestre)
- TOTALMTD (month to date)