---
date: '2020-08-25 23:59:00 GMT-3'
layout: post
published: true
title: 'Linus Torvalds: o Linux foi bem-sucedido graças ao egoísmo e à confiança'
image: '/files/2020/08/linus1.jpg'
excerpt: 'O criador do Linux, Linus Torvalds, ganhou o Prêmio de Tecnologia do Milênio e um cheque de 600.000 euros da Academia de Tecnologia da Finlândia. Ele foi indicado para o prêmio em reconhecimento ao fato de ter criado o sistema operacional Linux original e ter continuado a decidir quais modificações deveriam ser feitas no kernel (núcleo) do Linux — o código que permite que software e hardware trabalhem juntos. Hoje, vários sistemas baseados em Linux são executados em muitos dos servidores, decodificadores STB, smartphones, tablets, roteadores de rede, PCs e supercomputadores ao redor do mundo.'
---

{% capture nota1 %}
O texto a seguir é uma tradução da matéria originalmente escrita por Leo Kelion em 13 de junho de 2012 para o jornal britânico BBC. O texto original, em inglês, pode ser conferido aqui:

- [Linus Torvalds: Linux succeeded thanks to selfishness and trust - BBC News](https://www.bbc.com/news/technology-18419231)
{% endcapture %}

{% include nota.html texto=nota1 %}

{% include image.html src="/files/2020/08/linus1.jpg" caption="Linus Torvalds desenvolveu o Linux em 1991 enquanto estava na Universidade de Helsinque, na Finlândia. Ele se tornou cidadão americano em 2010." %}

**O criador do Linux, Linus Torvalds, ganhou o Prêmio de Tecnologia do Milênio e um cheque de 600.000 euros da Academia de Tecnologia da Finlândia.**

Ele foi indicado para o prêmio em reconhecimento ao fato de ter criado o sistema operacional Linux original e ter continuado a decidir quais modificações deveriam ser feitas no _kernel_ (núcleo) do Linux — o código que permite que _software_ e _hardware_ trabalhem juntos.

Hoje, vários sistemas baseados em Linux são executados em muitos dos servidores, decodificadores STB, _smartphones_, _tablets_, roteadores de rede, PCs e supercomputadores ao redor do mundo.

_Antes do anúncio, o Sr. Torvalds deu uma rara entrevista à BBC._

{% include image.html src="/files/2020/08/linus2.jpg" caption="O sistema para _smartphones_ Android, baseado em Linux, espalhou o uso da invenção do Sr. Torvalds." %}

**Quando você postou sobre o _kernel_ do sistema original na Usenet em 1991, o que você achava que aconteceria com ele?**

Eu acho que sua pergunta assume um nível de planejamento que simplesmente não existia na verdade. Não se tratava tanto sobre eu ter quaisquer expectativas do que aconteceria quando eu disponibilizasse os fontes do _kernel_ original: muito do ímpeto para lançá-lo foi simplesmente uma espécie de "ei, olha o que eu fiz".

Eu definitivamente não esperava que as pessoas me ajudassem com o projeto, mas esperava algum _feedback_ sobre o que eu tinha feito e procurava ideias do que mais as pessoas considerariam uma boa ideia.

**O sucesso do Linux se deve em grande parte à sua natureza de código aberto. Por que você acha que as pessoas têm se disposto a abrir mão de tanto tempo sem recompensa financeira?**

De várias formas, na verdade eu penso que a verdadeira ideia do código aberto é permitir que todos sejam "egoístas", não tentar fazer com que todos contribuam para algum bem comum.

Em outras palavras, eu não vejo o código aberto como algum tipo muito bonzinho que diz "vamos todos cantar kumbaya em volta da fogueira e fazer do mundo um lugar melhor". Não, o código aberto só funciona de verdade se todos estiverem contribuindo para suas próprias motivações egoístas.

Agora, esses motivos egoístas de forma alguma precisam ser "recompensas financeiras", no entanto.

As primeiras razões "egoístas" para fazer o Linux tendiam a se concentrar apenas no prazer de "futucar". Foi por isso que o fiz — programar era meu _hobby_ — paixão, na verdade — e aprender a controlar o _hardware_ era meu próprio objetivo egoísta. E acabou que eu não estava tão sozinho nisso.

Grandes universidades com departamentos de ciência da computação tinham pessoas interessadas nos mesmos tipos de coisas.

E a maioria das pessoas assim pode não ser louca o suficiente para começar a escrever seus próprios sistemas operacionais do zero, mas certamente havia pessoas por aí que acharam essa coisa de mexer com o _hardware_ interessante, e que estavam interessadas o suficiente para começar a brincar com o sistema e fazer sugestões de melhorias e, eventualmente, até mesmo fazerem elas mesmas essas melhorias e enviá-las de volta para mim.

E os direitos autorais protegiam esse tipo de pessoa. Se você é uma pessoa que está interessada em sistemas operacionais, e você vê esse projeto que faz isso, você não vai querer se envolver se sentir que de alguma forma "tirariam proveito" das suas contribuições, mas com a GPLv2 [a licença], isso simplesmente nunca foi um problema.

A propriedade fundamental da GPLv2 é um modelo muito simples de "olho por olho": eu darei a você minhas melhorias, se você prometer devolver as suas.

É uma licença fundamentalmente justa, e você não precisa se preocupar que outra pessoa vai aparecer e tirar proveito do seu trabalho.

E o que então pareceu surpreender as pessoas é que essa noção de "justiça" realmente escalona muito bem.

Claro, muitas empresas estavam no início bastante desconfiadas de uma licença que elas não estavam tão acostumadas antes, e às vezes desconfiadas em dobro, porque algumas partes da área do _software_ livre tinham sido declaradamente anti-comerciais e esperavam que as empresas do dia pra noite transformassem tudo em _software_ livre.

Mas realmente, todo o modelo de "olho por olho" não é justo apenas numa escala individual, é justo na escala de uma empresa, e é justo numa escala global.

Uma vez que as pessoas e empresas superaram seus obstáculos — renomeá-lo como "código aberto" e apenas deixar claro que aquilo não era algum tipo de empreitada anti-comercial definitivamente ajudou — as coisas simplesmente explodiram.

E a questão é, se seus concorrentes não se esforçam da mesma maneira que você, eles não podem colher os mesmos tipos de recompensas que você: se eles não contribuem, eles não conseguem controlar a direção do projeto, e eles não terão o mesmo tipo de conhecimento e compreensão que você tem.

Portanto, há realmente grandes vantagens em estar ativamente envolvido — você não pode simplesmente se escorar no trabalho de outra pessoa.

{% include image.html src="/files/2020/08/linus3.jpg" caption="O Sr. Torvalds construiu uma coleção de pinguins — o mascote oficial do _kernel_ do Linux." %}

**7.800 desenvolvedores em 80 países contribuíram para a última versão do _kernel_ Linux. Mas, à medida que ele se torna mais complexo, existe o perigo de se tornar menos acessível para novas pessoas se envolverem?**

Então, o _kernel_ definitivamente cresceu e ficou mais complexo, e certas áreas centrais em particular são coisas que um novo desenvolvedor não deve de forma alguma esperar simplesmente chegar e começar a mexer.

As pessoas ficam muito nervosas quando alguém que elas não veem como tendo um histórico sólido começa a enviar _patches_ para o código principal — e complexo — como o do subsistema de máquinas virtuais.

Portanto, é absolutamente muito mais difícil se tornar um desenvolvedor central hoje do que há 15 anos.

Ao mesmo tempo, acho que é muito fácil entrar no desenvolvimento do _kernel_ se você não for pelas partes mais centrais e complexas primeiro. O fato de eu lançar uma versão do _kernel_ aproximadamente a cada três meses, e cada uma dessas versões geralmente tem mais de 1.000 pessoas envolvidas, mostra que certamente não sentimos falta de contribuidores.

**Você mencionou anteriormente que você não tem condição de verificar se todo o código enviado funcionará em todo o _hardware_ — o quão grande é o problema de confiar em um projeto de código aberto como esse?**

Oh, confiança é a coisa mais importante. E é uma via de mão dupla.

Não sou apenas eu que posso confiar que algum subtenente fará a coisa certa, eles, por sua vez, podem confiar em mim para ser imparcial e fazer a coisa certa.

Certamente nem sempre concordamos, e às vezes as discussões podem se tornar bem acaloradas, mas no final do dia, vocês podem nem sempre gostar um do outro, mas pelo menos podem confiar que as pessoas não estão tentando sacanear umas às outras.

E é por esse problema de confiança que eu nunca quis trabalhar para uma empresa comercial de Linux, por exemplo.

Eu simplesmente não quero que as pessoas tenham sequer a impressão de viés — quero que as pessoas possam confiar que sou imparcial, não apenas porque me viram manter o _kernel_ ao longo dos anos, mas porque sabem que eu simplesmente não não tenho nenhum incentivo onde eu poderia querer apoiar uma empresa Linux em vez de outra.

Atualmente, eu trabalho em tempo integral no Linux, e sou pago para fazer isso, mas isso não aconteceu até que eu me sentisse confortável de que havia uma forma que poderia ser obviamente neutra, por meio de uma indústria sem fins lucrativos que realmente não vende o Linux em si.

E mesmo assim, para afastar todos os temores, nós realmente nos certificamos de que meu contrato diz explicitamente que meu emprego não significa que a Linux Foundation possa me dizer o que fazer.

Então, exatamente porque penso que essas questões de confiança são tão importantes, tenho um dos contratos de trabalho mais estranhos de que você já ouviu falar.

É basicamente um parágrafo falando sobre o que devo fazer — basicamente se resume ao fato de que tudo o que faço deve ser de código aberto — e o resto do contrato é sobre todas as formas que a empresa para a qual trabalho não pode me influenciar.

"Confiança" não se trata de algum tipo de neutralidade absoluta, ou algo parecido, se trata de um certo nível de previsibilidade e de saber que você não será enganado.

> "Confiança" não se trata de algum tipo de neutralidade absoluta, ou algo parecido, se trata de um certo nível de previsibilidade e de saber que você não será enganado.
>
> _Linus Torvalds, criador do Linux_

**O Linux é popular em muitas áreas da computação, incluindo _smartphones_ e servidores, mas nunca teve o mesmo avanço em _desktops_ — você acha que isso algum dia acontecerá?**

Então, eu acho que para transformar isso em um mercado consumidor, você realmente precisa vir pré-instalado. E, como o Android mostrou, o Linux realmente pode ser um produto de consumo. Portanto, não é que o mercado consumidor em si seja necessariamente um osso duro de roer, mas o "você precisa vir pré-instalado" é um grande ponto.

E no mercado de _notebooks_ e _desktops_, simplesmente nunca tivemos nenhuma empresa fazendo esse tipo de jogada. E não me interpretem mal — não é uma jogada fácil de se fazer.

Dito isso, por outro lado, eu também não o descartaria. Toda essa coisa de "navegador onipresente" tornou esse tipo de jogo de mercado mais realista, e acho que a pressão do Google Chrome (Chromebox e Chromebooks) claramente aponta nessa direção.

{% include image.html src="/files/2020/08/linus4.jpg" caption="O _notebook_ Chromebook do Google vem com seu sistema baseado em Linux pré-instalado." %}

Portanto, eu ainda estou esperançoso. Para mim, o Linux no _desktop_ é onde eu comecei, e o Linux no _desktop_ é literalmente o que eu ainda uso hoje principalmente — embora eu obviamente tenha outros dispositivos Linux, incluindo um telefone Android — então eu pessoalmente adoraria que ele dominasse esse mercado também.

Mas acho que nesse meio tempo não posso realmente reclamar do sucesso em outros mercados.

**Steve Ballmer uma vez descreveu o Linux como um "câncer", mas nos últimos meses ouvimos que a Microsoft está mudando sua divisão do Skype para computadores com Linux e agora está oferecendo uma versão baseada em Linux do seu serviço de nuvem Azure — isso te dá satisfação ?**

Bem, digamos que estou aliviado que a Microsoft parece ter, pelo menos em algum grau, parado de ver o Linux como o inimigo. Toda essa coisa de "câncer" e "não americano" era realmente muito embaraçosa.

> Estou aliviado que a Microsoft parece ter, pelo menos em algum grau, parado de ver o Linux como o inimigo.
>
> _Linus Torvalds, criador do Linux_

**O recente lançamento do Raspberry Pi, rodando Linux, atraiu muita atenção. Você tem esperança de que isso inspire outra geração de programadores que podem contribuir para o _kernel_ do Linux?**

{% include image.html src="/files/2020/08/linus5.jpg" caption="O computador de baixo custo Raspberry Pi pode rodar um sistema operacional Linux carregado a partir de um cartão de memória." %}

Então, pessoalmente, eu venho de uma experiência de "mexer com computadores" e, sim, como resultado, vejo que coisas como o Raspberry Pi são importantes: tentar possibilitar que um grupo maior de pessoas mexa com computadores e simplesmente brinque com eles.

E tornar os computadores baratos o suficiente para que você possa realmente não apenas comprar o _hardware_ em grande quantidade, mas talvez o mais importante, também consiga "suportar as perdas".

Com isso, quero dizer que eu suspeito que muitos deles irão para crianças que brincam um pouco com eles, mas que em seguida decidem que simplesmente não querem mais saber.

Mas tudo bem. Se for barato o suficiente, você pode arcar com o custo de ter muitos "não quero saber" se, ainda que de vez em quando, você acabe acionando um caso até mesmo bastante raro de "quero saber".

Portanto, na verdade eu penso que se você fizer esses tipos de plataformas baratas o suficiente — realmente "baratas de jogar fora" de certa forma — o fato de que você pode desperdiçar pode ser uma coisa boa, se isso significar que você alcançará algumas crianças que de outra forma não teria alcançado.

**Você trabalha em casa — o quão difícil é evitar se distrair com a vida familiar e se concentrar no que devem ser conceitos muito abstratos?**

Oh, tenho certeza de que pode ser difícil para algumas pessoas. Nunca foi um problema para mim.

Sempre achei os computadores fascinantes, muitas vezes a ponto de simplesmente sair e fazer minhas próprias coisas e não ser muito sociável.

Ter uma família não parece ter feito esse traço de caráter realmente diferente.

Eu ficarei feliz em ficar sentado em frente ao computador o dia todo, e se as crianças me distraírem quando estou no meio de algo, uma certa quantidade de pragas pode rolar.

Em outras palavras: o que poderia ser visto como uma falha de caráter socialmente debilitante pode certamente funcionar a seu favor também.

{% include image.html src="/files/2020/08/linus6.jpg" caption="O Sr. Torvalds trabalha no _kernel_ Linux em seu escritório em casa em Oregon." %}
