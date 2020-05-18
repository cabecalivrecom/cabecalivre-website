---
date: '2020-05-17 21:40:00 GMT-3'
layout: post
published: true
title: 'Covid-19: isolamento mais rígido não reduz óbitos'
image: '/files/2020/05/covid19-graficos-curva-obitos.png'
---

Chegamos a 2 meses de isolamento devido à Covid-19. Em alguns estados brasileiros, começou um pouco antes, em outros, um pouco depois, mas mais ou menos isso. No início, no calor do momento, com medo, ninguém sabia o que aconteceria a partir dali. Hoje, passados 2 meses, além de previsões, projeções, estimativas, etc umas mais pessimistas, outras mais otimistas, já dispomos de alguns dados que podemos analisar. Olhando em retrospectiva, é mais fácil analisar com mais calma e clareza. Difícil mesmo é tentar adivinhar o futuro. Embora ninguém tenha bola de cristal, alguns tentam.

Nesse texto, me proponho a analisar em retrospectiva números oficiais, traçar gráficos e apresentar uma interpretação alternativa ao que já se tornou meio que consenso.

## Motivação: o sensacionalismo da mídia

Para entender o que me motivou a fazer esse estudo, leia os textos anteriores:

- [Covid-19: o sensacionalismo da mídia]({% post_url 2020-05-17-covid-19-o-sensacionalismo-da-midia %})
- [Covid-19: será que tem relação com infarto e AVC?]({% post_url 2020-05-17-covid-19-sera-que-tem-relacao-com-infarto-e-avc %})

Perceber tudo isso me fez querer estudar e tentar criar minha própria visão da realidade.

## Índice de rigor do isolamento

A rápida disseminação da Covid-19 por todo o mundo fez com que governos adotassem diversas medidas para tentar conter seu avanço. Algumas das mais comuns incluem:

- fechamento de escolas
- fechamento do comércio
- limitações ou proibições de eventos públicos
- suspensão do transporte público
- restrições de viagens
- fechamento de fronteiras
- isolamento em casa
- auxílio financeiro emergencial
- refinanciamento de dívidas
- ampliação emergencial do sistema de saúde
- campanhas publicitárias

Contudo, nem todos os governos adotaram todas essas medidas ao mesmo tempo, gerando em todo o mundo um debate sobre quais medidas deveriam ser adotadas e quando.

Nesse sentido, eu encontrei um estudo da Universidade de Oxford chamado [Oxford COVID-19 Government Response Tracker (OxCGRT)][oxford], em que os pesquisadores monitoram quais ações os governos ao redor do mundo estão adotando e quando.

[oxford]: https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker

Todos os dias, para cada país, eles marcam em uma espécie de _checklist_ quais ações estão em andamento, somam uma pontuação para cada ação e produzem, ao final, um número entre 0% e 100%, indicando o quão rigorosa está sendo a atuação daquele país no combate à Covid-19. Nenhuma ação equivaleria a 0% e todas as ações possíveis, a 100%.

Note que essa medida é apenas para fins de comparação entre os países, em termos de ação mais rigorosa ou menos rigorosa. Não quer dizer que seja mais ou menos adequada, nem melhor ou pior, nem que mais ou menos pessoas estão aderindo ao isolamento.

Como esse estudo avalia o que já aconteceu e está acontecendo (e não tenta prever o futuro), considero-o confiável e decidi usá-lo como referência.

Ele disponibiliza em seu _site_ alguns mapas, gráficos e a planilha contendo todos os dados (país, data, medidas adotadas, casos confirmados, óbitos e índice) para _download_:

- [Coronavirus Government Response Tracker - Blavatnik School of Government - University of Oxford][oxford]

No final desse texto, eu também disponibilizo para _download_ todos os materiais que eu usei.

Esse mapa, disponível na página do estudo, mostra uma "foto" de como está o isolamento nos países hoje:

{% include image.html src="/files/2020/05/covid19-graficos-oxford-mapa.jpg" caption="Mapa das respostas dos governos à Covid-19. Dados de 12 de maio de 2020. Fonte: [Universidade de Oxford](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker)." %}

Também me chamou a atenção esse gráfico, que relaciona o total acumulado de casos de Covid-19 com o nível de isolamento nos diversos países:

{% include image.html src="/files/2020/05/covid19-graficos-oxford-pontos.jpg" caption="Relação entre número de casos de Covid-19 e índice de rigidez do isolamento. Dados de 10 de maio de 2020. Fonte: [Universidade de Oxford](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker)." %}

Perceba que 3 dos países com menor rigidez no isolamento (Nicarágua - 16%, Taiwan - 29% e Suécia - 47%) apresentam números de casos crescentes, mas eles são pontos fora da curva. Quase todos os países (próximos da reta tracejada) estão nesse momento adotando isolamento rígido (índice maior que 50%) e seus números totais de casos variam.

A princípio, se todos os países estão em isolamento rígido e os números de casos variam, pode-se pensar que essas variáveis não possuem correlação.

Porém, há que se observar que:

- esses países possuem diferentes populações (daí é razoável esperar que os Estados Unidos — USA — de fato apresentem mais casos que a Papua-Nova Guiné — PNG)
- esse gráfico mostra uma "foto" do momento em que ele foi feito, mas o número de casos, assim como a rigidez no isolamento, variou com o tempo
- em alguns países, o isolamento foi iniciado mais cedo, e em outros, mais tarde

Então, decidi olhar mais atentamente os números de alguns países. Selecionei alguns dos mais comentados na mídia, com diferentes níveis de isolamento:

{% include image.html src="/files/2020/05/covid19-graficos-paises-rigor-do-isolamento.png" caption="Países que considerei no meu estudo" %}

Padronizei as cores dos países adotando as cores do arco-íris, indicando a variação do que atualmente está em isolamento menos rigoroso ao mais rigoroso.

## Casos confirmados e óbitos

Como eu disse no início do texto que estamos há mais ou menos 2 meses em isolamento, decidi comparar os primeiros 2 meses de pandemia nos países selecionados.

No Brasil, o primeiro caso de coronavírus foi confirmado em São Paulo em [26 de fevereiro][saude-covid]. Dessa data, 2 meses (60 dias) haviam se passado em 26 de abril. Avancei um pouco e considerei até o 71º dia (06 de maio). Com o tempo, pretendo ir atualizando esse estudo.

[saude-covid]: https://www.saude.gov.br/noticias/agencia-saude/46435-brasil-confirma-primeiro-caso-de-novo-coronavirus

Produzi uma planilha do [LibreOffice Calc][libreoffice-calc], que você pode baixar clicando nesse _link_:

[libreoffice-calc]: https://pt-br.libreoffice.org/descubra/calc/

- [Planilha do estudo][planilha]

Essa planilha também pode ser aberta com o [Microsoft Excel][ms-excel], o [Planilhas Google][planilhas-google] ou qualquer outro programa capaz de abrir planilhas no formato ODS.

[ms-excel]: https://www.microsoft.com/pt-br/microsoft-365/excel
[planilhas-google]: https://docs.google.com/spreadsheets/

{% include image.html src="/files/2020/05/covid19-graficos-paises-confirmados-obitos.jpg" caption="Total acumulado de casos confirmados e óbitos para cada país" %}

Obtive os números totais acumulados de casos confirmados e óbitos para cada país e data do projeto [Our World in Data][ourworldindata] da Universidade de Oxford, que também disponibiliza todos os dados para _download_. Diariamente, o projeto atualiza sua planilha com base nos relatórios diários da [Organização Mundial da Saúde‎ (OMS)][oms]. Mais uma vez, usei um estudo que olha apenas para trás, para o que já aconteceu, não tenta prever o que vem pela frente.

[ourworldindata]: https://ourworldindata.org/coronavirus
[oms]: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports/

A população total de cada país, inclusive a do Brasil, foi obtida do [Banco Mundial][worldbank]. Ele também oferece uma planilha com os dados para _download_, contendo a população de cada país ano a ano. Os números considerados foram os mais recentes, de 2018.

Apenas a população de Taiwan, que não consta nessa planilha, foi obtida da [Wikipedia][wikipedia-taiwan].

[worldbank]: https://data.worldbank.org/indicator/sp.pop.totl
[wikipedia-taiwan]: https://pt.wikipedia.org/wiki/Taiwan

Nos gráficos, para comparar adequadamente a evolução da pandemia nos países, respeitando suas proporções e diferenças temporais, fiz as seguintes adaptações:

- em vez de comparar datas (por exemplo, em 01/02, já havia casos de coronavírus na Itália e nos EUA, mas não no Brasil), eu comparei **dias desde o primeiro caso confirmado** (o primeiro dia na Itália foi 31/01, nos EUA foi 21/01, e no Brasil, 26/02)
- em vez de comparar o número absoluto de casos e óbitos, eu comparei a **porcentagem da população** (ou seja, números relativos) confirmadamente contaminada ou morta pela doença (lembra da discussão sobre Brasil e Bélgica, né?)

Feitas essas adaptações, vejamos como ficaram as curvas:

{% include image.html src="/files/2020/05/covid19-graficos-curva-confirmados.png" caption="Evolução da porcentagem da população contaminada pela Covid-19" %}

{% include image.html src="/files/2020/05/covid19-graficos-curva-obitos.png" caption="Evolução da porcentagem da população que foi a óbito pela Covid-19" %}

Primeira coisa que se observa nitidamente é que as curvas são, sim, **exponenciais**, embora em alguns países elas se assemelhem mais a **retas próximas de zero**. É o caso, por exemplo, da Índia, cuja população (1,3 bilhões) é consideravelmente maior que a dos demais países, mas também é o caso do Japão (126 milhões) e da Nicarágua (6,4 milhões).

Notar também a **escala dos gráficos**: no país em que a maior parte da população foi contaminada, a Espanha, a fração da população contaminada, do primeiro caso confirmado (em 1º de fevereiro) até o 71º dia (em 11 de abril), não chegou a 0,4%.

Em ambas as curvas, é perceptível que o coronavírus teve maior impacto na Espanha e na Itália. Porém, nos demais países, respeitando as proporções das populações e os dias decorridos desde o primeiro caso, é possível afirmar que a evolução da doença foi semelhante, devido aos gráficos estarem bem próximos.

Daí é possível concluir que: **tanto em número de casos confirmados quanto em número de óbitos, a Covid-19 evoluiu de forma semelhante em países que adotaram medidas mais rígidas de isolamento e em países que adotaram medidas menos rígidas de isolamento**.

Repare no gráfico de casos confirmados, no 71º dia. Excluindo a Espanha e a Itália, olhando de cima para baixo, ou seja, dos países que proporcionalmente tiveram mais casos para os países que proporcionalmente tiveram menos casos, nessa ordem, temos:

- Alemanha (índice de isolamento no 71º dia = 81%, o que aparece na legenda é o índice do dia 12/05, mas você pode conferir o índice do 71º dia na planilha)
- França (89%, mais rigorosa que a Alemanha)
- Suécia (45%, menos rigorosa que a França)
- Brasil (75%, mais rigoroso que a Suécia)
- EUA (68%, menos rigoroso que o Brasil)
- Coreia do Sul (78%, mais rigoroso que os EUA)

Na Nicarágua, país que adotou o isolamento menos rigoroso do estudo, ainda não se passaram 71 dias desde o primeiro caso confirmado. Isso ocorrerá em 28 de maio. Por isso, a curva da Nicarágua não acompanha a dos outros países até o final do gráfico. Mas onde ela para, no 50º dia, é o país com proporcionalmente menos casos confirmados.

Da análise da curva de casos confirmados, conclui-se que **não há relação entre isolamento mais rigoroso e menor número de casos confirmados**.

Você pode fazer exercício semelhante para o gráfico de óbitos.

Vejamos outra coisa. Nos fixemos no 50º dia, último dia em que temos informação de todos os países. Vejamos como estava nesse dia o rigor do isolamento e os óbitos por milhão:

{% include image.html src="/files/2020/05/covid19-graficos-obitos-milhao-50-dia.png" caption="Óbitos por milhão no 50º dia após o primeiro caso confirmado de Covid-19" %}

Destaquei em negrito os países com isolamento mais rigoroso (maior que 50%).

Assim como na curva de casos confirmados, perceba que aqui **não há relação entre isolamento mais rigoroso e menor número de óbitos**. Se ordenamos os países pela quantidade de óbitos por milhão de habitantes, percebemos que países com isolamento mais e menos rigoroso se alternam.

É bem verdade que os isolamentos foram se tornando mais rigorosos conforme o tempo foi passando e o número de casos foi aumentando, como mostra esse gráfico:

{% include image.html src="/files/2020/05/covid19-graficos-oxford-evolucao.jpg" caption="Comparação do rigor da resposta à Covid-19 em 6 países. Dados até 10 de maio de 2020. Fonte: [Universidade de Oxford](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker)." %}

Mas você pode escolher o dia que você quiser. Verá que a lógica é a mesma: não há relação entre as variáveis "rigor do isolamento" e "óbitos por milhão".

Vejamos o 64º dia, ou seja, duas semanas depois:

{% include image.html src="/files/2020/05/covid19-graficos-obitos-milhao-64-dia.png" caption="Óbitos por milhão no 64º dia após o primeiro caso confirmado de Covid-19" %}

## E os países que começaram antes?

Também é verdade que nem todos os países responderam igualmente rápido à Covid-19. Por exemplo, os EUA só começaram a adotar alguma medida para combater a Covid-19 (índice de rigor do isolamento maior que 0) passados 10 dias do primeiro caso confirmado. A Alemanha já havia começado a adotar medidas 4 dias antes do primeiro caso confirmado. Mesmo assim, em ambos os países, passados 71 dias após o primeiro caso confirmado, o total acumulado de casos confirmados de Covid-19 não chegava a 0,01% da população.

Outro exemplo é a Suécia: na janela de tempo considerada (do primeiro caso confirmado até 71 dias depois), adotou medidas bem menos restritivas que Itália e Espanha, e teve menos casos confirmados e óbitos relativamente ao total da população.

Dentre os países estudados, o Brasil foi o que começou a adotar um isolamento mais rigosoro (índice maior que 50%) mais cedo (em termos de dias após o primeiro caso confirmado). Mas, 71 dias depois, há países tanto melhores quanto piores do que ele em termos de casos confirmados ou óbitos proporcionais.

Daqui, tiramos outra conclusão: também **não há relação entre o momento em que o isolamento foi iniciado e a quantidade de óbitos**.

Também não se observa que o isolamento reduziu a velocidade do contágio: países que adotaram isolamentos mais ou menos rigorosos, assim como países que iniciaram antes ou depois, apresentaram uma evolução parecida da doença, relativamente aos dias decorridos e tamanhos de suas populações, tanto que suas curvas estão bem próximas.

## Então o isolamento foi inútil?

Não. Em nenhum momento eu disse isso. Perceba que mesmo no estudo de Oxford, que engloba todos os países do mundo, o país mais "liberal" em relação à Covid-19 foi a Nicarágua, que mesmo assim hoje possui um índice de rigorosidade do isolamento de 16%. Ou seja, **todos os países do mundo adotaram alguma forma de isolamento para tentar combater a Covid-19**. Não houve país que simplesmente ignorou a Covid-19.

Por outro lado, considerando que não temos estatísticas de um país que simplesmente ignorou a Covid-19 (porque esse país não existiu), não podemos afirmar nem que o isolamento foi inútil, nem que o isolamento foi indispensável. Não é possível afirmar nem um extremo, nem o outro.

A questão toda é que em uns países o isolamento foi mais rigoroso, em outros foi menos, e, no final das contas, não se percebe nas estatísticas grande diferença entre uns e outros.

Não fazer isolamento algum não parece ser uma opção.

Mas aumentar a rigorosidade do isolamento com medidas que, como efeito colateral, reduzem as liberdades individuais não é garantia de que menos pessoas morrerão.

## Onde estão os curados?

Sabe o que eu sinto mais falta em todas essas estatísticas, tabelas e gráficos? Informações diárias sobre o total acumulado de pessoas que já se curaram da Covid-19! Porque geralmente só se fala nos totais acumulados de casos confirmados e óbitos.

A impressão que dá, olhando para vários gráficos em várias notícias, é que o número de casos confirmados e óbitos só aumenta. Na verdade, as notícias mostram quase sempre o **total acumulado** (que, de fato, só aumenta). Seria interessante saber quantas pessoas estão de fato doentes naquele dia. Daria pra saber isso tendo uma estatística de quem já se curou.

Veja este gráfico:

{% include image.html src="/files/2020/05/covid19-graficos-brasil.png" caption="Acumulado de casos e óbitos de COVID-19 por data de confirmação no Brasil" %}

No dia 10 de maio, esse gráfico estava na [página do Governo Federal sobre a Covid-19][covid-saude]. De lá pra cá, mudaram os gráficos na página, mas você ainda pode conferir uma cópia histórica desse gráfico no [Internet Archive][archive].

[covid-saude]: https://covid.saude.gov.br/
[archive]: https://web.archive.org/web/20200510010219/https://covid.saude.gov.br/

Sabemos que [o primeiro caso brasileiro do coronavírus já se curou][primeiro-curado]. Imagino que ninguém fica 2 meses com esse vírus. Quem contraiu a doença no início da pandemia, pelo tempo, provavelmente ou já se curou, ou já morreu.

[primeiro-curado]: https://canaltech.com.br/saude/aos-61-anos-primeiro-infectado-com-novo-coronavirus-no-brasil-esta-curado-161842/

Fico feliz quando vejo umas notícias assim:

{% include image.html src="/files/2020/05/covid19-graficos-florianopolis.jpg" caption="Boletim do coronavírus em Florianópolis, 29 de abril de 2020. Fonte: [Prefeitura de Florianópolis](https://www.facebook.com/prefeituradeflorianopolis/photos/a.679599458815187/2745616002213512/)." style="max-width: 450px;" %}

Para uma seguidora que perguntou, a Prefeitura explicou que "os 3.390 casos notificados são os suspeitos e também os já descartados de Covid-19".

Na minha humilde opinião, o gráfico ficaria ainda mais interessante assim:

{% include image.html src="/files/2020/05/covid19-graficos-florianopolis2.png" caption="Boletim do coronavírus em Florianópolis. Dados de 29 de abril de 2020." %}

Fica a dica pra Prefeitura!

## Modelos matemáticos famosos...

Como eu disse no início do texto, é difícil adivinhar o futuro. Mesmo assim, algumas pessoas tentam. Inúmeros modelos matemáticos com complexidades as mais variadas tentaram prever a evolução da Covid-19, contaminados e óbitos, com e sem isolamento.

Na minha humilde opinião, por vezes, as melhores explicações são as mais simples (já ouviu falar do [princípio KISS][kiss]? _Keep it stupid simple_). Se um modelo é formado por tantas variáveis e é tão complexo, possivelmente está errado, ou não faz sentido mesmo.

[kiss]: https://pt.wikipedia.org/wiki/Princ%C3%ADpio_KISS

Nos textos anteriores, apresentei dois modelos: um defeituoso e um que não se confirmou.

Tem outro modelo que ficou bastante famoso aqui no Brasil que foi o do Imperial College, citado por Atila Iamarino em seu perfil do Twitter e canal do YouTube.

Esse modelo, em sua primeira versão, de [16 de março][ic-1], previa que a Covid-19 mataria 2 milhões nos EUA e 510 mil no Reino Unido até o fim de agosto, caso nenhuma medida de isolamento fosse adotada. Atila transpôs o modelo pra cá e projetou que 1,4 milhões de brasileiros seriam mortos até o fim de agosto, se aqui ocorressem as mesmas condições:

[ic-1]: https://www.imperial.ac.uk/medicine/departments/school-public-health/infectious-disease-epidemiology/mrc-global-infectious-disease-analysis/covid-19/report-9-impact-of-npis-on-covid-19/

{% include image.html src="/files/2020/05/covid19-graficos-atila1.jpg" caption="Fonte: [Atila Iamarino (@oatila) no Twitter](https://twitter.com/oatila/status/1240156474174734339?s=20)" %}

A segunda versão, de [26 de março][ic-2], revisou a previsão para o Reino Unido para cerca de 20 mil mortos esse ano. Essa versão traz números para o Brasil em sua tabela: em um cenário pessimista, se nenhuma estratégia de isolamento fosse adotada, o Brasil poderia ter mais de 1,15 milhões de mortes devido à Covid-19 esse ano. Já em um cenário otimista, com estratégias de supressão rígidas, esse número poderia ser reduzido para 44,2 mil.

[ic-2]: https://www.imperial.ac.uk/medicine/departments/school-public-health/infectious-disease-epidemiology/mrc-global-infectious-disease-analysis/covid-19/report-12-global-impact-covid-19/

A terceira versão, de [08 de maio][ic-3], não traz projeções de casos ou óbitos para o Brasil e afirma que o país se tornou o epicentro da epidemia na América Latina, que as medidas adotadas até então não reduziram a propagação da pandemia o suficiente, e prevê que o número de casos e óbitos vai continuar a crescer, a menos que mais ações sejam adotadas.

[ic-3]: https://www.imperial.ac.uk/medicine/departments/school-public-health/infectious-disease-epidemiology/mrc-global-infectious-disease-analysis/covid-19/report-21-brazil/

Diante de tudo que eu expus até aqui, na minha humilde opinião, embasada na minha humilde planilha do LibreOffice Calc, eu não poderia discordar mais desse estudo. Repito: aumentar o rigor do isolamento não necessariamente reduzirá o número de óbitos.

Outro estudo que Atila menciona em seu Twitter é um da Universidade de Harvard publicado na [Revista Science][science] em 14 de abril, que projeta que serão necessários períodos de isolamento prolongados e intermitentes até 2022, se não for descoberta vacina daqui pra lá.

[science]: https://science.sciencemag.org/content/early/2020/05/11/science.abb5793

{% include image.html src="/files/2020/05/covid19-graficos-atila2.jpg" caption="Fonte: [Atila Iamarino (@oatila) no Twitter](https://twitter.com/oatila/status/1250122514472357891?s=20)" %}

Próximo ano, poderemos ver em retrospectiva se esses modelos se confirmaram. Eu, sinceramente, torço pelo melhor: espero que nenhum deles se confirme, como aconteceu com o modelo supostamente produzido pela ABIN. Em outras palavras, espero que tenhamos menos óbitos que o previso por esses modelos matemáticos.

## Conclusão

Minha opinião (não sou dono da verdade, é tão somente minha opinião): em um primeiro momento, dado que a humanidade se deparou com uma doença nova, desconhecida, não sabia o que fazer, não era prudente pecar pelo otimismo. Portanto, iniciar o isolamento foi bastante razoável. Mas agora, passados 2 meses, temos dados para comparar o Brasil com outros países, que inclusive já estão lidando com o vírus há mais tempo. Diante de tudo o que expus aqui, não me parece razoável continuar com o isolamento no mesmo nível de rigorosidade com que foi iniciado, tampouco aumentá-lo. Até porque o remédio não pode ser pior que a doença. Muitas pessoas já estão sentindo os efeitos da quarentena na sua saúde e no seu bolso (não vou entrar no mérito dessa discussão aqui). Penso que é necessário traçar uma estratégia para voltarmos de forma gradual e inteligente à normalidade.

Perceba que não analisei nem critiquei aqui outras medidas que podem ajudar a se prevenir da Covid-19: lavar as mãos, usar máscara, evitar aglomerações, etc. Também não vou entrar nesse mérito. Meu objetivo com esse texto era mostrar que isolamento mais rigoroso não necessariamente significa menos óbitos. Creio que demonstrei isso.

Claro que **pessoas não são apenas números**. Eu imagino a dor de quem perdeu um familiar ou amigo para a Covid-19. Se você está nessa situação, provavelmente agora é totalmente a favor que tudo seja feito com a intenção de salvar tantas vidas quanto possível. Se você não está nessa situação, possivelmente deseja o quanto antes voltar à sua rotina anterior, ou está com medo de sair na rua. Sem dúvida alguma, cada vida humana tem um valor imensurável. Mas não podemos deixar que o medo e a emoção nos tirem da realidade.

Vamos vencer essa doença. Todos juntos. Com cautela, inteligência, racionalidade e sem medo.

{% include image.html src="/files/2020/05/renato-russo-monte-castelo.jpg" caption="É só o amor que conhece o que é verdade. (Renato Russo, imagem do _site_ [Pensador](https://www.pensador.com/frase/MTA4Mzk3/))" %}

## Continua...

Geralmente, as notícias comparam como a Covid-19 atinge os **países** e como eles respondem a ela. Eu também não concordo com isso. Penso que países como Estados Unidos, Brasil, Itália são muito grandes. Creio que o vírus não atinge todos os **estados** (nem todos os **municípios**) por igual. Portanto, se a doença não atinge todas as cidades com a mesma intensidade, as cidades não precisam adotar todas elas as mesmas medidas. Cada lugar deveria adotar as medidas mais condizentes com a sua realidade.

Pretendo fazer uma versão desse texto comparando alguns estados e municípios do Brasil e de outros países.

## Downloads

Minha planilha, assim como todas as planilhas de terceiros que embasam a minha, estão disponíveis para _download_ nesse repositório do GitHub:

- [https://github.com/cabecalivrecom/covid19](https://github.com/cabecalivrecom/covid19)

- [Minha planilha][planilha]

- [Baixar todos os arquivos como um só arquivo ZIP](https://github.com/cabecalivrecom/covid19/archive/c8dc582.zip)

Planilhas de terceiros:

- Índice de rigor do isolamento, da Universidade de Oxford: [OxCGRT_latest.csv](https://github.com/cabecalivrecom/covid19/raw/c8dc582/OxCGRT_latest.csv)

  Fonte: [Oxford COVID-19 Government Response Tracker (OxCGRT)][oxford]

  Acesso em: 12/05/2020

- População dos países, inclusive do Brasil (números de 2018): [API_SP.POP.TOTL_DS2_en_csv_v2_988606.csv](https://github.com/cabecalivrecom/covid19/raw/c8dc582/API_SP.POP.TOTL_DS2_en_csv_v2_988606.csv)

  Fonte: [Banco Mundial][worldbank]

  Acesso em: 12/05/2020

- Casos confirmados e óbitos por Covid-19 no mundo, inclusive no Brasil: [owid-covid-data.csv](https://github.com/cabecalivrecom/covid19/raw/c8dc582/owid-covid-data.csv)

  Fonte: [Our World in Data][ourworldindata]

  Acesso em: 12/05/2020

[planilha]: https://github.com/cabecalivrecom/covid19/raw/c8dc582/Covid-19.ods
