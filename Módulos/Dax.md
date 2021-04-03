
### DAX

#### Categorias de funções Dax

- Matemática
- Filtro
- Lógica
- Texto
- Estatística
- Hierarquia
- Informação
- Data e tempo
- Inteligência de tempo (calculos complexos para compara períodos)

Documentação DAX

https://docs.microsoft.com/pt-br/dax/

#### operadores
= (igual)
\> (maior)
< (menor)
 \>= 
 <> (diferente)

 #### Sintaxe

  "=" para iniciar todas as funções
  - Nome da função não é case sensitive
  - Abertura de parênteses
  - Argumentos divididos por vbírgula
  - Fechamento dos parênteses

#### Locais de aplicação 
- Medidas:
- Colunas calculadas: materializam o calculo das tabelas
- Tabelas:

#### Agregações
Guia modelagem
(medida, colunas ou tabelas)
- SUM()
- AVERAGE()
- DIVIDE
- ALL
- ALLSELECTED
- CALCULATE
  
#### Lógica de calculos
- Contextos, o cenário utilizado para realizar os cálculos
- Filtros (visual ou linhas)

<b>1. Medidas calculadas: utilizam o contexto visual, ou seja, são calculadas de acordo com os campos e filtros inseridos em um visual. 
Calcula todas os valores das colunas sem identificar individualmente as suas linhas </b>


#### CALCULATE
Avalia uma expressão e faz uma avaliação em um contexto modificado por filtros

- ALL (retira os filtros sejam internos ou externos)
- ALLSELECTED (igual all, mas deixa os filtros externos)