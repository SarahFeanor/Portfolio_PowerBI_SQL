# DAX

A linguagem DAX (Data Analysis Expressions) é amplamente usada no **Microsoft Power BI**, **Excel
Power Pivot** e **Analysis Services** para realizar cálculos 
e análises em dados tabulares. 

## Aqui estão alguns dos comandos e funções mais usados em DAX:

### **SUM**:
   ```
   SUM(column)
   ```
   Calcula a soma dos valores em uma coluna.

### **AVERAGE**:
   ```
   AVERAGE(column)
   ```
   Calcula a média dos valores em uma coluna.

### **COUNT**:
   ```
   COUNT(column)
   ```
   Conta o número de linhas com valores não vazios em uma coluna.

### **FILTER**:
   ```
   FILTER(table, condition)
   ```
   Filtra as linhas de uma tabela com base em uma condição especificada.

### **CALCULATE**:
   ```
   CALCULATE(expression, filter1, filter2, ...)
   ```
   Modifica o contexto de filtro de uma expressão, permitindo que você aplique filtros específicos a cálculos.

### **SUMX** e **AVERAGEX**:
   ```
   SUMX(table, expression)
   AVERAGEX(table, expression)
   ```
   Calcula a soma ou a média de uma expressão em uma tabela, aplicando um contexto de filtro.

### **RELATED**:
   ```
   RELATED(column)
   ```
   Recupera um valor de outra tabela relacionada com base em uma relação definida.

### **COUNTROWS**:
   ```
   COUNTROWS(table)
   ```
   Conta o número de linhas em uma tabela.

### **IF**:
   ```
   IF(condition, value_if_true, value_if_false)
   ```
   Executa uma avaliação condicional e retorna um valor com base na condição.

### **SWITCH**:
    ```
    SWITCH(expression, value1, result1, value2, result2, ...)
    ```
  Avalia várias condições e retorna um resultado com base na primeira condição verdadeira.

### **SUMMARIZE**:
    ```
    SUMMARIZE(table, column1, column2, ...)
    ```
 Cria uma tabela resumida com as colunas e agregações especificadas.

### **RANKX**:
    ```
    RANKX(table, expression, [value], [order], [ties])
    ```
  Calcula a posição de uma linha dentro de uma tabela classificada com base em uma expressão.

### **EARLIER**:
    ```
    EARLIER(column)
    ```
   Referencia o valor de uma coluna na linha anterior do contexto de filtro.

### **ALL**:
    ```
    ALL(table)
    ```
  Remove todos os filtros de contexto de uma tabela, retornando todas as linhas.

### **DATESYTD**:
    ```
    DATESYTD(date_column, [year_end_date])
    ```
  Retorna um conjunto de datas do ano até a data especificada.

