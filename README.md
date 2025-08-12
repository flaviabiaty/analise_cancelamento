# analise_cancelamento
Análise de uma base de dados de clientes para verificar o percentual de cancelamentos.

Utilizando uma base fictícia de clientes, foram realizadas análises para redução do percentual de cancelamentos de planos.  

Taxa inicial de cancelamento: 56,7%
primeiro problema identificado - planos mensais -> todos os clientes deste tipo de assinatura, acabaram cancelando.
segundo problema identificado - ligações no call center por mais de 5 vezes, levando ao cancelamento.
terceiro problema identificado - clientes com mais de 20 dias de atraso, acabaram cancelando.

*Possíveis soluções para redução da taxa de cancelamento*
Desconto nos planos trimestral e anual, uma vez que todos os clientes do contrato mensal cancelaram
Criação de um alerta quando o cliente ligar a 3ª vez pro callcenter
Criação de um alerta pro time de cobrança quando o cliente bater 10 dias de atraso.
Resolvendo esses fatores, pode ser obtida uma meta de cerca de 20% de cancelamento, muito melhor que os 50% iniciais

