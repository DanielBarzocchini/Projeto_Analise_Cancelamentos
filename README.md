## Projeto_Analise_Cancelamentos

Neste projeto farei o tratamento dos dados para analisar e indentificar possíveis motivos de cancelamento dos clientes que usam um serviço de tv por assinatura.

Após finalizar as análises trarei propostas de solução para reduzir esse número.

Neste projeto usei as bibliotecas pandas e plotly para tratamento e visualização dos dados.

Apaguei algumas colunas irrelevantes para o projeto.

Verifiquei que haviam campos vazios em 5 linhas no universo de 50000, por isto removi as linhas. 

Gerei alguns gráficos comparando os campos da tabela com a coluna de cancelamentos para identificar algum padrão entre os dados. 

Após a analise dos gráfcos, identifiquei que:
- Todos os clientes do contrato mensal cencelaram.
- Clientes que ligam mais do que 4 vezes para o call center, cancelaram.
- Clientes que atrasaram mais de 20 dias, cancelaram.

Para os casos descritos acima, sugeri as seguintes propostas de solução:
- Verificar a possibilidade de ofercer desconto nos planos anuais e trimestrais.
- Criar um processo para resolver o problema do cliente em no máximo 3 ligações.
- Criar uma política com o time financeiro, para resolver atrasos em até 10 dias.

Caso estas propostas sejam colocadas em prárica teríamos uma redução de cancelamentos de aproximadamente 43% para 18%.
