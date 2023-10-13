# Cenários

## Introdução

Os cenários desempenham um papel fundamental na Interação Humano-Computador (IHC), sendo peças-chave no processo de desenvolvimento de sistemas interativos. Eles oferecem uma visão contextualizada e narrativa das situações que os usuários podem enfrentar ao interagir com interfaces digitais, permitindo antecipar suas necessidades, desafios e ambientes de uso. Esses cenários são representações, muitas vezes fictícias, que ilustram como os usuários interagem com um sistema, proporcionando insights valiosos para designers, desenvolvedores e pesquisadores. Ao explorar esses cenários, é possível criar soluções mais eficazes, centradas no usuário e adaptadas aos contextos específicos de uso.

## Metodologia

A metodologia utilizada neste artefato é a de Cenários de Interação, tomando como base a descrição e os exemplos presentes no capítulo 07 do livro Interação Humano Computador [1]. Cada membro da equipe ficará responsável por criar um cenário, o membro e o cenário atribuído a ele podem ser vistos na tabela 1, Além disso, os cenários serão definidos através de um texto descritivo que terá: contexto, ator(es), objetivos, ações e avaliação, e o ator principal do cenário será uma das [Personas](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/ad5200e9034c6795c53d8fa9a2f2c6bd0ef86b58/docs/analise%20de%20requisitos/personas.md) definidas pelo grupo.

<div align="center">

| Membro da Equipe | Cenário  |
| ------------------------------------------------------------------------ | ---------------------------    |
| [Gabriel Rosa](https://github.com/gabrielrosa09)                         | [Registrar nova reclamação](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#registrar-nova-reclama%C3%A7%C3%A3o)       |
| [Gabriel Zaranza](https://github.com/GZaranza)                           | [Desbloquear saldo](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#desbloquear-saldo)                                     |
| [Izabella Alves](https://github.com/izabellaalves)                       | [Consultar estabelecimento](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-estabelecimento)                 |
| [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira) | [Visualizar recibo fiscal](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#visualizar-recibo-fiscal)                  |
| [Lucas Ribeiro](https://github.com/lucassouzs)                           | [Consultar reclamação](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-reclama%C3%A7%C3%A3o)                        |
| [Lucas Víctor](https://github.com/Lucas13032003)                         | [Indicação de créditos](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#indica%C3%A7%C3%A3o-de-cr%C3%A9ditos)      |
| [Lucas Víctor](https://github.com/Lucas13032003)                         | [Consultar extrato](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-extrato)                                     |
| [Zenilda Vieira](https://github.com/zenildavieira)                       | [Consultar resultado de sorteio](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-resultado-de-sorteio)                  |

**Tabela 1:** Definição de membro da equipe que trabalhou em determinado cenário.
Fonte: [Izabella Alves](https://github.com/izabellaalves),  [Lucas Víctor](https://github.com/Lucas13032003),  2023.

</div>

## Cenários Identificados

### Registrar nova reclamação

[Luiz](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-primária-1-luiz-economista) é um consumidor frequente de um restaurante localizado perto de seu trabalho. Ele costuma almoçar lá todos os dias e sempre pede a nota fiscal para acumular créditos no programa Nota Legal.

No entanto, Luiz percebeu que, nos últimos meses, as notas fiscais de suas refeições não estavam sendo registradas corretamente no programa. Preocupado com a situação, Luiz decidiu fazer uma reclamação no site do Nota Legal.

Primeiro, Luiz acessou o site do [Nota Legal](https://www.notalegal.df.gov.br/) e fez login em sua conta. Em seguida, ele navegou até a seção de “Reclamações” localizada no menu principal. Lá, ele encontrou um botão para “Registrar nova reclamação”.

Ao clicar no botão, Luiz foi direcionado para uma página onde poderia detalhar sua reclamação. Ele anexou o documento fiscal e selecionou o tipo da nota. Em seguida, ele inseriu a chave de acesso, CNPJ, data de emissão, número da nota e o valor, pois todos esses campos eram obrigatórios.

Depois de preencher todos os campos necessários, Luiz clicou no botão “Registrar reclamação”. Uma mensagem de confirmação apareceu na tela, informando que sua reclamação havia sido registrada com sucesso e que o Nota Legal entraria em contato com ele em breve.

Luiz ficou satisfeito por ter conseguido registrar sua reclamação e esperava que a situação fosse resolvida em breve. Ele continuou a monitorar sua conta no Nota Legal para verificar se as notas fiscais estavam sendo registradas corretamente.

### Desbloquear saldo

[Luiz](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-primária-1-luiz-economista) é um economista aposentado e gosta de participar de programas de vantagens, como o Nota Legal. Todo lugar em que faz uma compra, Luiz pede o CPF na nota fiscal para arrecadar saldo no Nota Legal e assim conseguir desconto no IPVA do seu carro. Próximo do período de encerramento da indicação do saldo Nota Legal, Luiz decide entrar no site do [Nota Legal](https://www.notalegal.df.gov.br/) para realizar sua indicação e percebe que uma parte do seu saldo está bloqueada para uso.

Para não perder esse saldo, Luiz seleciona a opção "desbloquear", localizada abaixo do saldo, e lhe aparece uma mensagem informando que algumas notas fiscais que ele solicitou o Nota Legal foram bloqueadas e que era possível visualiza-las clicando em "Visualizar documento bloqueados" ou então pedir o desbloqueio desses documentos no Portal de Serviços da Receita da Secretaria de Fazenda do Distrito Federal, atravez do hiperlink "clique aqui". 

Luiz decide por visualizar os documentos e percebe que os documentos bloqueados são de compras que ele realizou no mês anterior. Por se tratar de um valor considerável de saldo, ele decide desbloquear e seleciona o hiperlink "Desblqueio de créditos, localizado ao final da lista de documentos bloqueado.

O economista é redirecionado para o Portal de Serviços da Receita da Secretaria de Fazenda do Distrito Federal e consegue fazer o desbloqueio desse saldo utilizando o canal de atendimento do site.

### Consultar Estabelecimento

[Maria](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-prim%C3%A1ria-2-maria-administradora) é formada em administração e trabalha na administração de uma empresa localizada no centro da cidade há muitos anos. Uma vez por mês, após o trabalho, Maria costuma ir até uma farmácia comprar uma caixa de seu remédio diário. Ao chegar em casa, ela verifica se a nota fiscal foi cadastrada corretamente, para que possa reunir créditos para o desconto do Nota Legal ao final do ano.

Porém, a farmácia que Maria frequentava fechou. Maria deseja continuar com o costume de comprar mensalmente seu remédio após o trabalho. Então ela decidiu verificar quais farmácias localizadas nos arredores de seu trabalho também são cadastradas no programa Nota Legal, para que ela possa continuar ganhando o desconto.

Maria pesquisa no Google e vê que há 5 possíveis farmácias. Então, ela acessa o site do [Nota Legal](https://www.notalegal.df.gov.br/) e navega pelo site até chegar no rodapé e clicar no botão de consultar estabelecimentos. Depois disso, ela vê os vários filtros que podem ser utilizados e resolve utilizar o filtro de razão social, onde ela coloca o nome de cada uma das 5 farmácias. Em seguida, utiliza o filtro de ramo comercial, onde ela define o ramo de medicamentos e saúde. A partir daí, clica no botão e verifica se cada uma das farmácias está ou não cadastrada.

O resultado obtido por Maria é que das 5 empresas, 3 são cadastradas no programa Nota Legal. Ela ficou feliz por ter conseguido encontrar novas farmácias cadastradas e decidiu ir comprar o remédio na farmácia que era cadastrada e mais próxima de seu trabalho.

### Visualizar Recibo Fiscal

[Luiz](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-primária-1-luiz-economista) é um economista aposentado de 52 anos com uma paixão por tecnologia e finanças. Ele passou a maior parte de sua vida trabalhando com números, analisando tendências econômicas e ajudando as pessoas a fazer escolhas financeiras inteligentes. Agora que está aposentado, ele tem mais tempo para explorar suas paixões e hobbies. Um desses hobbies é ficar atualizado com as últimas tendências tecnológicas, especialmente aquelas relacionadas às finanças.

Luiz descobriu o site [Nota Legal](https://www.notalegal.df.gov.br/) há algum tempo e ficou imediatamente impressionado com as possibilidades que tem ao usar o site nota legal.

Recentemente, Luiz recebeu um recibo fiscal que deseja visualizar no site Nota Legal. Ele já está familiarizado com o processo, tendo feito isso várias vezes antes. Ele sabe que precisa fazer login em sua conta, navegar até a página correta e inserir os detalhes necessários para visualizar o recibo.

Como um especialista em economia e um entusiasta da tecnologia, Luiz está sempre em busca de maneiras inteligentes de gerenciar seu dinheiro. Ele usa o aplicativo Nota Legal para recomendar estratégias de investimento para amigos e familiares, tornando-se um usuário fiel do aplicativo.

Agora, Luiz está pronto para visualizar seu recibo fiscal no site Nota Legal. Ele sabe que este é apenas mais um passo em sua jornada contínua para se manter atualizado com as últimas tendências financeiras e tecnológicas.

### Consultar Reclamação

[Luiz](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-primária-1-luiz-economista) é um cliente frequente de um restaurante localizado nas proximidades de seu local de trabalho. Diariamente, ele faz suas refeições no estabelecimento e sempre solicita a emissão da nota fiscal, visando acumular créditos no programa Nota Legal.

Após vivenciar diversas situações desconfortáveis dentro do restaurante, Luiz decidiu rever as queixas que havia registrado durante esses incidentes.

Ao entrar no site do [Nota Legal](https://www.notalegal.df.gov.br/) e fazer Login em sua conta, Luiz navegou até a seção 'Consulta de Reclamações'. Nesse espaço, deparou-se com seis campos de pesquisa distintos, cada um destinado a um aspecto específico de suas queixas. 

Após preencher os campos necessários, clicou no botão 'Consultar'. Em resposta, o sistema exibiu uma lista contendo todas as reclamações que ele havia registrado, com base nas características previamente informadas nos campos de pesquisa.

Ao ver suas reclamações de forma clara, Luiz percebeu que seus problemas eram reais. Ele se sentiu confiante ao confrontar o restaurante com evidências sólidas, decidindo agir. Levou suas preocupações às autoridades e ao estabelecimento, esperando por refeições melhores no futuro.

### Indicação de créditos

[Luiz](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-primária-1-luiz-economista) , um economista aposentado com ampla experiência em finanças, começava todos os anos com uma rotina financeira sólida. Todo início de janeiro, ele abria seu computador e acessava o Site [Nota Legal](https://www.notalegal.df.gov.br/). Essa era uma prática que ele seguia há anos, e era parte crucial de sua estratégia financeira.

Primeiro, Luiz entrava na seção do IPTU. Com sua habilidade e conhecimento, ele rapidamente indicava os créditos fiscais para ajudar a compensar parte do imposto predial. Isso era como um ritual para ele, uma maneira de otimizar suas finanças pessoais e economizar dinheiro.

Em seguida, Luiz navegava até a seção do Nota Legal. Ele inseria com cuidado os recibos fiscais das compras realizadas no ano anterior. Para Luiz, cada recibo era uma oportunidade de acumular créditos que poderiam ser usados em suas futuras despesas.

Ao concluir suas indicações no aplicativo, Luiz se sentia satisfeito. Ele sabia que estava tomando medidas práticas para manter suas finanças em ordem e, ao mesmo tempo, apoiar o comércio local. Era uma maneira de começar o ano com o pé direito, sabendo que estava cuidando bem de suas finanças.

### Consultar extrato

[Maria](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-prim%C3%A1ria-2-maria-administradora) é uma profissional experiente formada em adimistração, moradora dedicada da cidade de Brasília. Ela sempre foi uma cidadã exemplar que valorizava a transparência e a responsabilidade financeira. Todos os meses, após suas compras e interações com diversos estabelecimentos locais, Maria fazia questão de guardar todos os recibos e comprovantes fiscais. Ela sabia que esses documentos eram valiosos, não apenas para garantir que suas despesas fossem contabilizadas, mas também para contribuir com o programa "Nota Legal".

Com o início do mês, Maria estava ansiosa para conferir seu extrato no site [Nota Legal](https://www.notalegal.df.gov.br/). Ela sabia que este extrato era uma forma de rastrear todas as suas interações financeiras com os estabelecimentos cadastrados no programa. Maria acreditava que a transparência e o controle financeiro eram essenciais, e o Nota Legal era uma ferramenta fundamental para isso.

Maria pegou seu computador e, acessou o site. Ela navegou até aba de "Extrato" e esperou que as informações fossem carregadas na tela, logo depois colocou o periodo de consulta de extrato. Quando seu extrato apareceu, Maria viu todos os créditos que havia acumulado a partir de suas compras e transações do mês anterior. Era gratificante ver o quanto ela estava contribuindo para o programa, ao mesmo tempo em que se beneficiava com os créditos acumulados.

### Consultar resultado de sorteio

Cenário de análise: *Consulta de resultado de sorteio do programa Nota Legal*
Atores: Ana, professora, e Joana, sua aluna de economia.

[Ana](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/personas.md#persona-secund%C3%A1ria-2-ana-professora) tem 57 anos e é professora de economia em uma escola local. Ela dá aulas sobre educação financeira. Ana ensina a seus alunos a importância de saber gastar bem e de exigir a nota fiscal em todas as compras, exercendo sua cidadania. Os alunos de Ana aprenderam a participar do Programa Nota Legal do Distrito Federal e sempre que fazem compras em estabelecimentos participantes do programa, pedem nota fiscal  e informam seu CPF. Além de colaborarem com o aumento da arrecadação fiscal, o que pode ser transformado em melhorias na cidade para todos, os alunos sabem que além da concessão de créditos anual, eles podem participar também de sorteios com prêmios em dinheiro.
Em uma determinada aula, Ana estava ensinando aos alunos como verificar no site do [Nota Legal](https://www.notalegal.df.gov.br/) se eles estavam participando dos sorteios semestrais e se algum deles já tinha sido sorteado. Joana, uma de suas alunas, estava participando dessa aula. Joana tem 45 anos, durante o dia trabalha como caixa de supermercado e à noite estuda economia. Ela valoriza muito essas aulas e tudo que aprende repassa a seu filho Rafael de 12 anos. Na aula, Joana fez login no site com seu CPF e senha e em seguida clicou no ícone “Sorteio”. Desde antes da professora Ana ensinar sobre o assunto, Joana já pedia sempre nota fiscal com CPF e acessava o portal periodicamente, com esperanças de ser sorteada um dia. Em seguida, Joana acessou o último sorteio realizado, o sorteio do segundo semestre de 2023. Após alguns segundos de espera e ansiedade (o site sempre demora um pouco para responder!), a tela de informações apareceu e no campo “Premiado” estava a palavra “Sim”. Joana ficou sem fala, mal podia acreditar! Com algum esforço conseguiu chamar a professora Ana. Juntas elas clicaram em “consultar bilhetes premiados” e descobriram que Joana tinha ganhado 500 mil reais!!! Ana orientou Joana a clicar em “indicar dados bancários para crédito do prêmio”  para que ela pudesse receber o dinheiro. Joana já começou a fazer planos de como iria gastar uma parte desse valor e investir o restante, como a professora Ana sempre ensina.

## Referências Bibliográficas

> [1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

## Histórico de Versão

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|07/10/2023|Adição da introdução, tabela, metodologia e cenário 1|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.1`|10/10/2023|Adição do cenário de indicação de créditos|[Lucas Víctor](https://github.com/Lucas13032003)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.2`|10/10/2023|Adição do cenário consultar saldo|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.3`|10/10/2023|Adição do cenário de registrar nova reclamação|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.4`|10/10/2023|Revisão do cenário consultar saldo, adição da introdução, tabela e metodologia|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.5`|11/10/2023|Adição do cenário consultar reclamação|[Lucas Ribeiro de Souza](https://github.com/lucassouzs)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.6`|11/10/2023|Adição do cenário consultar extrator |[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro de Souza](https://github.com/lucassouzs)
|`1.7`|11/10/2023|Adição do cenário visualizar Recibo Fiscal |[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Lucas Víctor](https://github.com/Lucas13032003)|
|`1.8`|11/10/2023|Revisão do cenário Visualizar Recibo Fiscal |[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Víctor](https://github.com/Lucas13032003)|
|`1.9`|12/10/2023|Adição do cenário consultar resultado de sorteio |[Zenilda Vieira](https://github.com/zenildavieira)|[Lucas Ribeiro](https://github.com/lucassouzs)|