# **Análise de Crédito e Inadimplência**

### Projeto final do módulo ‘Python para Análise de Dados’, parte integrante do curso de Ciência de Dados da EBAC
---

O objetivo dessa análise é investigar os fatores que contribuem para a inadimplência de um cliente, com base em seu comportamento e outros atributos, como salário, escolaridade e movimentação financeira.
 
Para isso, vamos explorar os dados de crédito disponíveis no seguinte [link](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/develop/dataset/credito.csv). Esses dados estão em formato CSV e fornecem informações sobre os clientes de uma instituição financeira.

Especificamente, concentraremos nossa atenção na segunda coluna, denominada default, que indica se um cliente é adimplente (default = 0) ou inadimplente (default = 1).

Abaixo está uma descrição completa dos atributos presentes no  arquivo CSV:

| Coluna  | Descrição |
| ------- | --------- |
| id      | Número da conta |
| default | Indica se o cliente é adimplente (0) ou inadimplente (1) |
| idade   | Idade do cliente |
| sexo    | Gênero do cliente |
| depedentes | Número de dependentes financeiros |
| escolaridade | Nível de escolaridade |
| estado_civil | Estado civil |
| salario_anual | Faixa do salário mensal multiplicado por 12 |
| tipo_cartao | Categoria do cartão |
| meses_de_relacionamento | Quantidade de meses desde a abertura da conta |
| qtd_produtos | Quantidade de produtos contratados |
| iteracoes_12m | Quantidade de iterações com o cliente no último ano |
| meses_inatico_12m | Quantidade de meses que o cliente ficou inativo no último ano |
| limite_credito | Valor do limite do cartão de crédito |
| valor_transacoes_12m | Soma total do valor das transações no cartão de crédito no último ano |
| qtd_transacoes_12m | Quantidade total de transações no cartão de crédito no último ano |

