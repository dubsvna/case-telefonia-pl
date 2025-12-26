# Case Técnico: Análise de Receita, Churn e Margem no segmento de Telecom

### Como fazer? 
Fica a critério da(o) candidata(o) escolher se sente mais confortável em fazer no Excel, Pyton, PBI e outra ferramenta.

### Anexos:
Como documento de apoio, segue a planilha com os dados fictícios para o case em excel, contendo 3 guias:
- CLIENTES: Lista de clientes com segmento e estado.
- FATURAMENTO: Receita e custo por cliente e mês.
- CHURN: Status do cliente (Ativo ou Cancelado) por mês.

### Contexto
Sua empresa fornece serviços de telefonia corporativa e soluções digitais para pequenas e médias empresas. O time de planejamento precisa entender melhor o
desempenho de sua base de clientes e propor ações estratégicas para crescimento e retenção.

Você recebeu um banco de dados com informações dos últimos 6 meses sobre os clientes, incluindo:

1. Tabela CLIENTES
* cliente_id (ID único do cliente)
* segmento (Pequena, Média, Grande empresa)
* estado (UF do cliente)

2. Tabela FATURAMENTO
* cliente_id
* mes_ano (Formato YYYY-MM)
* receita (Valor faturado em R$ no mês)
* custo (Custo associado ao cliente no mês)

3. Tabela CHURN
* cliente_id
* mes_ano
* status (Ativo, Cancelado) 

## Desafios Técnicos
1. Criar uma Tabela Dinâmica que mostre o faturamento mensal por segmento e por estado.
2. Liste os 10 clientes que tiveram maior faturamento no último mês.
3. Calcule a margem bruta por cliente no último mês (margem_bruta = (receita - custo) / receita).
4. Identifique a taxa de churn por segmento de empresa no último mês.
5. Criar uma fórmula (SE + PROCV ou ÍNDICE/CORRESP) para classificar os clientes conforme a margem bruta em:
* Alto valor (Margem > 50%)
* Médio valor (Margem entre 30% e 50%)
* Baixo valor (Margem < 30%)
6. Construir um gráfico de tendência da receita nos últimos 6 meses.
