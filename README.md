# Desafio-Localiza

A taxa de Churn pode ser definida como:
(Número de clientes que cancelaram o serviço no período)/(Número de clientes no início do período)  x 100
Ele é um importante indicador de retenção.
A hipótese postula que:
 “O churn de novos clientes é maior do que o churn de clientes ativos”

Procurei entender um pouco mais do cenário e tentar me inteirar da utilidade prática.
Surgiram algumas dúvidas e busquei ser o mais assertivo possível. 
Os clientes (de acordo com o código único presente na base) que possuíam pelo menos 1 contrato ativo em dezembro de 2019 foram comparados com o cenário de dezembro de 2020.

O cálculo apontou que o churn dos clientes ativos considerando o período de 1 ano foi de 73,4% enquanto o dos novos clientes foi de 91,4%. 

Pelos dados, constata-se que os clientes novos - que fizeram seu primeiro contrato no início de 2020 - em geral, não estavam mais ativos no fim do mesmo ano. Nesse contexto, poderíamos conjecturar que os clientes antigos tem uma maior fidelidade e estão sempre utilizando os serviços de empresa.
Seria interessante um maior aprofundamento nesse cenário para entender a dinâmica e possivelmente inserir outras variáveis (quantidade de diárias, frequência de uso ...)

Os comentários adicionais sobre os desafios 1 e 2 estão presentes no código R.
