📊 Análise de Dados – Controle de Frota 🚗

📌 Como surgiu esse projeto

Durante o programa Capacita Brasil, tive a oportunidade de trabalhar com a Makro Engenharia Ltda num desafio bem concreto: a empresa precisava enxergar melhor o que estava acontecendo com a frota dela. Consumo de combustível, quilômetros rodados, horas de operação, orçamento e tudo isso espalhado em planilhas sem muita visibilidade.
A solução foi construir dashboards no Power BI que trouxessem essas informações de forma clara, com filtros por unidade, contrato e período.

📊 O que os dashboards mostram

💰 Orçamento: Apresenta a comparação entre valores planejados e valores realizados, permitindo identificar variações nos custos operacionais da frota.

<p align="center">
  <img src="imagens/orcamento.png" width="800">
</p>

Indicadores principais:
- Orçamento planejado
- Valor realizado
- Diferença entre previsto e executado

🛣️ KM Rodados: Permite acompanhar o volume de quilômetros percorridos pelos veículos ao longo do tempo, com filtros por unidade, contrato e período.

![Dashboard KM Rodados](imagens/kmrodados.png)

Esse painel auxilia na identificação de:
- Veículos subutilizados
- Rotas com maior utilização
- Padrões de uso da frota

⏱️ Horas Ligado: Apresenta o tempo de operação dos veículos ao longo do período analisado.
Esse indicador permite entender quanto tempo os veículos permanecem em funcionamento, auxiliando na identificação de possíveis ineficiências operacionais, como veículos ligados por longos períodos sem deslocamento.

![Dashboard Horas Ligadas](imagens/HorasLigadas.png)

Indicadores analisados:
- Total de horas de operação
- Comparação entre unidades ou contratos
- Evolução ao longo do tempo

⛽ Consumo (Litros): Visão mensal do consumo, com filtros dinâmicos por frota, unidade e contrato

![Dashboard Consumo Litros](imagens/ConsumoLitros.png)

Possui filtros por:
- Unidade
- Contrato
- Frota
- Período

🛠️ Ferramentas usadas

Power BI: para os dashboards e visualizações

Consolidação e estruturação dos dados brutos

Definição de KPIs junto com a equipe da Makro

⚠️ Desafios dos Dados

Durante o desenvolvimento do projeto, foram encontrados alguns desafios relacionados à qualidade dos dados, como:

- valores inconsistentes
- registros com valores negativos
- diferenças de padrão entre planilhas
- grande volume de dados não estruturados

Esses fatores exigiram um processo inicial de organização e validação dos dados antes da construção dos dashboards.

💡 Principais Insights

Algumas observações obtidas a partir da análise dos dados da frota:

- O consumo de combustível apresenta variações significativas entre diferentes unidades, indicando possíveis diferenças operacionais ou de utilização da frota.

- Em alguns períodos foi possível observar veículos com muitas horas de operação em comparação com a quilometragem rodada, o que pode indicar tempo elevado de motor ligado sem deslocamento.

- A comparação entre orçamento planejado e valores executados permite identificar períodos em que os custos ultrapassaram o previsto.

Essas análises ajudam a criar uma visão mais clara sobre o uso da frota e podem auxiliar na identificação de oportunidades de otimização operacional.


📚 Aprendizado

Esse projeto foi minha primeira experiência trabalhando com dados próximos de um contexto real de empresa.

Durante o desenvolvimento, precisei lidar com bases de dados extensas e com diferentes níveis de consistência, o que exigiu cuidado na organização, consolidação e interpretação das informações antes da construção dos dashboards.

Além da parte técnica no Power BI, o projeto reforçou a importância de transformar dados brutos em indicadores que realmente ajudem na tomada de decisão. Aprendi que um bom dashboard não é apenas visualmente organizado, mas precisa comunicar informações claras e úteis para quem utiliza no dia a dia.
