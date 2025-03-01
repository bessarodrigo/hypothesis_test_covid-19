# Teste de Hipóteses - Estratégia para Desenvolvimento de uma Vacina
Estudo realizado com base nos aprendizados do módulo de inferência estatística da [Escola Preditiva](https://www.preditiva.ai/). apliquei o conceito utilizado no Excel e repliquei no Python.

# Problema
Com todos os esforços para combater o COVID-19, surgiram diversas iniciativas para desenvolver uma vacina eficaz para reduzir o impacto dos sintomas. Um laboratório em suas pesquisas chegou a duasestratégias viáveis:

1. Vírus enfraquecido
2. RNA mensageiro

Para decidir por qual estratégia seguir, realizou um estudo clínico com 87 pessoas distribuídas aleatoriamente entre as duas estratégias. Com os resultados obtidos, como podemos responder: 
- Existe diferença na estratégia em relação à proporção de sintomas graves?

# Hipóteses
- H0: A proporção sintomas graves VE é igual a proporção sintomas graves RNA, ou: pVE = pRNA
- H1: A proporção sintomas graves VE é diferente da proporção sintomas graves RNA, ou: pVE ≠ pRNA

# Resultado
Como o p-valor de 18% é maior que o nível de significância de 5%, podemos concluir que não existem evidências estatísticas suficientes contra H0, ou seja, não rejeitamos H0.

Relembrando as hipóteses definidas:

H0: A proporção sintomas graves VE é igual a proporção sintomas graves RNA
H1: A proporção sintomas graves VE é diferente da proporção sintomas graves RNA
E como não rejeitamos H0, podemos dizer que não existem evidências estatísticas de que a proporção de pessoas com sintomas graves não é igual nos 2 tipos de vacinas.
