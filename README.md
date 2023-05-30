# logistics company dashboard
- Painel de analise do desempenho de uma empresa de logistica na entregua de diversas unidades de um produto "A"

## Pontos focais da análise
* Indicar o desempenho de nossas North stars (pedidos entregues, pedidos não entregues e tempo de processamento de entrega).
* Mostrar a performance por Hubs.
* Análise dos motivos de pedidos não entregues.
* Acompanhamento de volume de pedidos por período. 

## Painel para analisarmos a performance por HUB.
![Painel 1](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Painel_1.png)
- Podemos acompanhar nossas North stars por Hub, grupos ou total
- Sempre trazendo o total de pedidos, os entregues, os não entregues é o TPE(tempo de processamento de entregue) médio.
- % entregues X % não entregues
- Barras de pesquisa para facilitar a localização por hub
- Tabela auxiliar com possível extração dos dados apresentados no painel

## Painel de ranking dos HUB.
![Painel_2](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Painel_2.png)
- Acumulado de pedidos por HUB x Quantidade de pedidos entregues ou % dos pedidos entregues.
- Painel interativo que possibilita a mudança do KPI no eixo y secundário.
- Também possui barra de pesquisa por nome  HUB.
- Permite mostras mais informações ao parar o cursos em cima da coluno do HUB.
- Insight : Está analise mostra que a performance de um HUB não pode ser mensurada apenas pelo Acumulo total de pedidos, necessário comparar o total de pedidos com o % de pedidos entregues

##Painel de análise dos motivos de pedidos não entregues.
![Painel_3](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Painel_3.png)
- Aqui olhamos o acumulo de pedidos não entregues divididos por seu Motivo.
- O Motivo é subdivisão da Situação, neste caso a subdivisão da Situação “Não Entregues’
- Insight : Quase 50% dos pedidos não entregues estão classificados como “0 – Em Andamento”, Indico ao time de operações uma reunião parar debatermos uma subdivisão deste motivo que no cenário atual acaba deixando o status da entregue muito genérico, visto que “Em andamento”  o pedido pode estar sendo coletado pelo HUB ou estar em rota final de entrega para o destino

## Painel de análise acumulados dos pedidos ao longo do mês.
![Painel_4](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Painel_4.png)
- Este gráfico nos traz o acumulo de pedidos ao longo do mês de análise , comparando entregues é não entregues.
- Insight : Mais de 50% dos nossos pedidos Não foram entregues em junho, isso fortalece a tese para subdividir a categoria “Em andamento” para termos uma visão mais clara desse número

## Painel auxiliar de Dados dos Pedidos por ordem de vendas.
![Painel_5](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Painel_5.png)
- Este painel tem a função de auxiliar, através de uma tabela com filtros, o olhar de todos os dados dos pedidos, separados por ordem de venda.
- Podemos pesquisar pedidos por HUB, ID do pedido e filtrar por situação.
- Também temos um cartão com a função de contar os pedidos da tabela de acordo com os filtros aplicados.
- Presente também um filtro de dará por ordem de venda ou data de entrega efetiva.

## Insights finais
- O mês em analise mostra que nosso numero de pedidos entregues é quase 3 vezes menor que nosso total de pedidos.
- Dos pedidos com Situação de “não entregues” um terço deles estão com a situação “em andamento”, ocultando assim informações que podem ser de suma importância para a melhora da performance dos HUB e do desempenho do negocio.
- Não podemos avaliar os HUB’s apenas por volume de pedidos, temos que olhar também o % dos pedidos entregues para assim definir um indicador que deixe claro o desempenho dos mesmos.

## Downloads do material
- [Painel completo em PBI](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Case%20An%C3%A1lise%20Logistica.pbix)
- [Base de dados em xlsx](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Base_dados_tratada_case.xlsx)
- [Apresentação em Power Point](https://github.com/ClaudioBarreira97/logistics_company_dashboard/blob/main/Analise%20Case%20Logistica%20.pptx)


