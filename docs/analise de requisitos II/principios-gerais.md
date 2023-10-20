# Princípios Gerais

## Introdução

Para garantir que um modelo conceitual atenda eficazmente às necessidades de um usuário específico, possibilitando uma aprendizagem natural e rápida, é crucial que sua estrutura seja embasada pelos Princípios e Diretrizes Gerais.
Esses princípios incluem metas amplas, como a usabilidade, acessibilidade, feedback efetivo e eficiência, que são essenciais para a concepção e o aprimoramento contínuo das interações entre humanos e computadores.

## Metodologia

Este documento busca explorar e apresentar os princípios gerais do projeto do site "Nota Legal" através de alguns princípios e diretrizes
comumente usados em Interação Humano Computador, que foram definidos no livro Interação Humano Computador (S. D. J. Barbosa, B. S. da Silva) [1].

Através desses princípios, apresentados e definidos no tópico abaixo, faremos uma análise de cada um deles dentro do site "Nota Legal", onde vamos observar as violações
desses princípios e diretrizes, e como eles podem ser melhorado e/ou utilizados no nosso projeto.

## Princípios e Diretrizes Gerais

Cada um dos princípios e diretrizes comumente utilizados em IHC e definidos no livro Interação Humano Computador (S. D. J. Barbosa, B. S. da Silva) [1] está listado e 
descrito abaixo de acordo com o capítulo 8 da referência bibliográfica em questão.

### Correspondência com as Expectativas dos Usuários

Deve-se seguir a mesma ordem natural e lógica como a tarefa seria feita no mundo real, utilizando o idioma do usuário.
Garantir que a interface corresponda às expectativas dos usuários, oferecendo uma experiência familiar e coerente com o que eles esperam, é crucial para uma interação bem-sucedida.

### Simplicidade nas Estruturas das Tarefas

Priorizar a simplicidade nas estruturas das tarefas significa tornar as interações o mais intuitivas e descomplicadas possíveis, para reduzir a quantidade de planejamento e a resolução de problemas que elas requerem. 

### Equilíbrio entre Controle e Liberdade do Usuário

Oferecer um equilíbrio adequado entre controle e liberdade dá aos usuários a sensação de autonomia, permitindo que personalizem suas interações enquanto mantêm a orientação dentro do sistema. É importante manter o usuário no controle, pois o computador, a interface e o ambiente de trabalho pertencem ao usuário.

### Consistência e Padronização

A interface deve ser consistente com o modelo conceitual embutido no sistema e, se isso não for possível, o sistema deve ser padronizado para compensar. Manter consistência e padronização na interface assegura que os usuários encontrem elementos conhecidos em diferentes partes do sistema, criando uma experiência unificada e previsível.

### Promovendo a Eﬁciência do Usuário

Priorizar a eficiência do usuário significa minimizar obstáculos na interação, permitindo que os usuários realizem tarefas de forma eficaz e sem perder tempo, colocando suas necessidades em primeiro plano. A eficiência do usuário vem sempre antes da eficiência do computador.

### Antecipação

Antecipar as necessidades do usuário envolve oferecer informações e funcionalidades relevantes antes que sejam explicitamente solicitadas, otimizando a experiência do usuário e tornando a interação mais eficaz.
O sistema deve prever o que o usuário quer e precisa, fornecendo todas as informações e ferramentas necessárias para cada passo do processo.

### Visibilidade e Reconhecimento

É necessário tornar visível para os usuários o que é possível realizar e como as ações devem ser feitas. Tornar as ações e o estado do sistema visíveis proporciona aos usuários uma compreensão clara do que está acontecendo, promovendo uma navegação intuitiva e a identificação rápida de informações importantes.

### Conteúdo Relevante e Expressão Adequada

A interação deve seguir quatro máximas: qualidade (só informações verdadeiras), quantidade (menos é mais, só o necessário), relevância (só informações relativas ao sistema) e clareza (evitar prolixidade e ambiguidade). Fornecer conteúdo relevante apresentado de maneira clara e legível é essencial para garantir que os usuários obtenham informações significativas, facilitando a compreensão e a interação eficaz.

### Projeto para Erros

O sistema deve prever que qualquer erro potencial será cometido e trazer caminhos para revertê-los. Antecipar e projetar soluções para possíveis erros é crucial para permitir que os usuários se recuperem facilmente de equívocos, evitando frustração e mantendo a confiança na interação com o sistema.

## Análise

### Correspondência com as Expectativas dos Usuários

A diretriz de Correspondência com as Expectativas dos Usuários não é seguida no site "Nota Legal", um exemplo disso pode ser visto na figura 1, onde o título do footer do site diz "Fale conosco", porém, o footer contém inúmeras coisas, e não somente formas de contato. Além disso, as formas de contato estão do outro lado do footer. Isso quebra a expectativa do usuário, que ao ler "Fale conosco", espera informações de contato, e não um menu. A ordem não é natural. Por causa das violações, esta diretriz será aplicada e corrigida em nosso projeto.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 1 - Footer do site Nota Legal.</font>

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/main/docs/imagens/principios-gerais/expectativa-usuario.png" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</font>

</div>

### Simplicidade nas Estruturas das Tarefas

A diretriz de Simplicidade nas Estruturas das Tarefas no geral está sendo bem seguida no site "Nota Legal", as tarefas que podem ser realizadas no site possuem uma complexidade aceitável e não há nada complexo demais. Na figura 2, é possível visualizar a tela de lançamentos de indicação do "Nota Legal", onde o usuário pode visualizar suas indicações ao informar o tipo de lançamento e o exercício. Esta tarefa tem uma boa complexidade e uma baixa quantidade de planejamento para que seja executada, portanto, em nosso projeto vamos manter este modelo de estrutura das tarefas.
<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 2 -  Tela de visualização e lançamentos de indicação do site Nota Legal.</font>

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/main/docs/imagens/principios-gerais/simplicidade-tarefas.png" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</font>

</div>

### Equilíbrio entre Controle e Liberdade do Usuário

A diretriz de Equilíbrio entre Controle e Liberdade do Usuário é violada no site "Nota Legal", um exemplo de violação pode ser visto na figura 3, onde o usuário é obrigado a continuar na tela de carregamento, pois o site não possui nenhum mecanismo para que o usuário cancele, desfaça ou refaça suas ações. De acordo com o Equilíbrio entre Controle e Liberdade do Usuário, os usuários não devem ﬁcar presos num caminho de interação único para realizar uma atividade [1], por isso, esta diretriz será aplicada e corrigida no nosso projeto.
<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 3 - Tela de carregamento do site Nota Legal.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/liberdade-usuario.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</font>

</div>

### Consistência e Padronização

Para manter a consistência e padronização deve-se padronizar as ações, os resultados dessas ações, o layout dos diálogos e as visualizações de informação. O site Nota Legal, em sua grande parte, mantém a padronização dos elementos do site. Porém, em algumas telas é possível observar elementos faltando, tornando a padronização incompleta. Na figura 4 é apresentado, do lado esquerdo, um exemplo de tela na qual há o botão de fechar além do X no canto superior direito. No lado direito, é apresentada uma tela com mesma funcionalidade (visualização de informação) que não apresenta o botão fechar, há somente o x no canto superior direito.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 4 - Telas de mesma funcionalidade não padronizadas.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/mensagem-botao-fechar.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</font>

</div>

### Promovendo a Eﬁciência do Usuário

Para Tognazzini, o usuário deve ser mantido ocupado para não haver perda de produtividade. Assim, processos demorados devem ser executados em background sem travar a interação e o sistema também não deve interromper o usuário sem necessidade quando ele estiver trabalhando em algo específico. Se não for possível executar em background, uma solução é manter o diálogo com o usuário, mantendo informado do que está acontecendo e não ficando ocioso. O site Nota Legal fere esse princípio logo quando o usuário efetua login. Ele sempre demora a responder e apresenta a tela ilustrada na Figura 5. Essa tela causa a impaciência e a ociosidade do usuário, pois ele não sabe ao certo se precisa realmente esperar ou se o sistema travou. Para cumprir o princípio da eficiência,  Se não for possível fazer o sistema responder mais rápido, seria necessário dialogar com o usuário enquanto ele espera, mostrando na tela sucessivas mensagens, tais como: "aguarde o carregamento...", "está demorando mais que o previsto...", "só mais um pouco...". Outro exemplo de promover a eficiência do usuário pode ser visto no próximo item.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 5 - Tela de espera de carregamento apresentada após o login.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/aguardando-login.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</font>

</div>

Outra forma de promover a eficiência do usuário é desativar links que não estão disponíveis por algum motivo, evitando que o usuário clique nesses links e só depois descubra que eles não estão funcionais. No site Nota Legal há funcionalidades que só podem ser utilizadas em determinada época do ano ou, como no caso do exemplo ilustrado na Figura 6, se o usuário tiver sido sorteado. O botão da tela anterior "Indicar dados bancários para crédito do prêmio" está ativo mesmo que a pessoa não tenha sido sorteada. E quando a pessoa clica nesse botão, aparece a tela da Figura 6, sem nenhuma informação adicional.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 6 - Tela de indicação de dados bancários.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/selecione-sorteio-em-branco.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</font>

</div>

### Antecipação

Antecipação é a capacidade do sistema de prever o que o usuário quer e precisa. O usuário não deve ter que buscar e coletar informações ou buscar ferramentas parar atender sua vontade, o sistema deve fornecer informações adicionais úteis e ferramentas previamente. POde-se sugerir valores defaults como forma de antecipar a vontade do usuário e promover sua eficiência também. O site nota legal não tem em seus formulários muitos valores defaults, o que seria possível de fazer, já que a maioria das informações podem ser obtidas do cadastro do usuário, como CPF, nome, imóveis e veículos cadastrados etc. E algo que chamou a atenção também foi a falta de instruções e informações para o desbloqueio de saldos. Além do link estar num local muito ruim - no final da tabela de saldos bloqueados - ele não tem o seu devido destaque, como pode-se observar na figura 7.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 7 - Tela de saldos bloqueados.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/desbloquear-saldo.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</font>

</div>

Ao clicar nesse link, o usuário é encaminhado para uma página fora do site nota legal (Figura 8), sem nenhuma instrução de como proceder ou como preencher os dados ali pedidos, o que fere o princípio em questão. Nesse formulário seria possível já trazer a maioria das informações preeenchidas, antecipando o que o usuário precisaria fazer e consequentemente melhorando sua eficiência.

<br>
<div align="center">

<font size="3"><p style="text-align: center">Figura 8 - Tela de solicitação de desbloqueio de créditos.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/desbloquear-saldo-site-externo.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023.</font>

</div>

### Visibilidade e Reconhecimento

Em geral, o site Nota legal mantém o usuário atualizado do status atual do sistema com informações claras e de fácil persepção, fornecendo feedbacks (resposta do sistema) sutis e no tempo certo. Na figura 9, é possível ver como o site informa o usuário que está ocorrendo um carregamento de página atráves de uma "ampulheta" animada no meio da tela, indicando que o sistema não está travado.

<div align="center">

<font size="3"><p style="text-align: center">Figura 9 - Status de carregamento do site Nota Legal.</font>
  
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/nota_legal.gif" width="533" height="300">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a>, 2023.</font>
  
</div>

Porém, esse carregamento de página pode passar dos 30 segundos (Vídeo 1) e de acordo com Tognazzini (2003), quando uma ação ultrapassa 2 segundos de execução, o sistema deverá informar a demora estimada junto a uma barra de progresso, fornecer opções de cancelar a ação ao usuário e para casos de ultrapassar 10 segundos o sistema deve emitir um aviso sonoro e visual indicando o final da ação [2]. Nesse quesito o site Nota Legal viola a diretriz de Visibilidade e Reconhecimento.

<font size="3"><p style="text-align: center">Vídeo 1 - Tela de carregamento violando a diretriz de Visibilidade e Reconhecimento.</a> , 2023.</font>

<iframe width="560" height="315" src="https://youtu.be/fC5Dodn3MZQ" title="Tela de carregamento do Login do site Nota Legal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div align="center">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a> , 2023.</font>

</div>

Outros pontos relacionados à Visibilidade e Reconhecimento são informar ao usuário o caminho que ele percorreu no sistema e os objetos, ações e as opções devem ser atualizadas e facilmente perceptíveis (Tognazzini, 2003). Na figura 10, pode-se observar que o site Nota Legal mostra ao usuário o caminho que ele seguiu até determinada página e atualiza as opções e ações que ele pode executar nessa nova página. Importante ressaltar que essas informações são fornecidas no centro da página e destacadas do background do site, fazendo com que o usuário as encontre de maneira rápida.

<div align="center">

<font size="3"><p style="text-align: center">Figura 10 - Exemplo de caminho que o usário percorreu dentro do site Nota legal.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/Visibilidade%20e%20reconhecimento.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a> , 2023.</font>

</div>

### Conteúdo Relevante e Expressão Adequada

O site do Nota Legal aprensenta um design minimalista e com poucos elementos ao longo de suas páginas, principalemte quando se fala da página do usuário. Um dos quesitos dessa diretriz é o principio estético e minimalista definido por Nilsen (1993), em que deve-se mostrar para o usuário apenas informação relevantes e comumente usadas no contexto das tarefas [1]. Na figura 11, pode-se observar que o menu principal da página do usuário contém apenas as opções de funcionalidades do sistema e o saldo do Nota Legal. Esse padrão de mostrar apenas as opções de funcionalidades sem textos ou elementos extras é replicado ao longo de todo o site, como por exemplo na página de indicação mostrada na figura 12.

<div align="center">

<font size="3"><p style="text-align: center">Figura 11 - Página principal da conta de usuário do Nota Legal.</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/menu_nota_legal.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte:  <a href="https://github.com/gzaranza">Gabriel Zaranza</a> , 2023.</p></font>

</div>

<div align="center">

<font size="3"><p style="text-align: center">Figura 12 - Página onde realiza a indicação do saldo do Nota Legal.</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/pag_estornar_indicacao.png" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a>, 2023.</p></font>

</div>

Outro ponto que está de acordo com a diretriz em questão, é a clareza e legibilidade dos textos presentes nos botões e rótulos do site, como é observado nas Figuras 11 e 12. Pode-se resaltar a presença de contraste dos textos em relação ao fundo, além da funcionalidade de alto contraste presente em todo site (Figura 13). Porém, não existem as funcionalidades de aumentar o tamanho da fonte dos textos e modo daltônico que são recomendadas por Tognazzini (2003).

<div align="center">

<font size="3"><p style="text-align: center">Figura 13 - Funcionalidade de alto contraste ativada no site Nota Legal.</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/alto_contraste.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a>, 2023.</p></font>

</div>

### Projeto para Erros

O site Nota Legal possui mecanismos de ajudar o usuário durante um erro, como por exemplo, mensagens informando que um erro aconteceu (Figura 12). Porém, não seguem critérios levantandos por Nielsen(1993), como ajudar o usuário a reconhecer, diagnosticar e recuperar de erros ao longo do site [3]. Nessa situação de Figura 14, o usuário apenas é informado sobre o erro e o diagnóstico, não havendo a opção de contornar esse problema.

<div align="center">

<font size="3"><p style="text-align: center">Figura 14 - Mensagem de erro no site Nota Legal.</font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/servico_indisponivel.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a>, 2023.</p></font>

</div>

Outro ponto que fere a diretriz de projeto para erros são a localização dos botões de limpar informações próximas a botões de registrar ou consultar em algumas páginas, como é exemplificado na Figura 15. De acordo com Cooper (1999), não é recomendado colocar controles de funções, como é o caso do botão de registrar reclamação, próximo a botões de controles perigosos, como é o caso do botão de limpar as informações [4]. O usuário pode se distrair e realizar uma ação crítica ou que atrapalhe a realização da sua tarefa.

<div align="center">

<font size="3"><p style="text-align: center">Figura 15 - Proximidade do botão "limpar" e "registrar reclamação" no site Nota Legal.</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/bot%C3%A3o_limpar_registrar.png?raw=true" style="width: 75%;height=auto;">

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/gzaranza">Gabriel Zaranza</a>, 2023.</p></font>

</div>

## Referências Bibliográficas
> [1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> [2] TOGNAZZINI, B. First principles of interaction design. 2003.
>
> [3] Nielsen, J. Usability Engineering. New York, NY: Academic Press, 1993.
>
> [4] Cooper, A. Th e Inmates Are Running the Asylum: Why High-Tech Products Drive Us Crazy and How to Restore the Sanity. Sams Publishing, 1999.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.1`|16/10/2023|Adição de analise|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.2`|16/10/2023|Adição de analise Visibilidade e Reconhecimento|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.3`|16/10/2023|Adição de analise Conteúdo Relevante e Expressão Adequada|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.4`|17/10/2023|Adição de analise Projeto para erros|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.5`|20/10/2023|Corrigindo as legendas|[Gabriel Zaranza](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.6`|20/10/2023|Adição de analise Consistência e Padronização |[Zenilda Vieira](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.7`|20/10/2023|Adição de analise Promovendo a Eﬁciência do Usuário |[Zenilda Vieira](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.8`|20/10/2023|Adição de analise Antecipação |[Zenilda Vieira](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.9`|20/10/2023|Padronizando localização dos nomes das figuras e das fontes nas legendas|[Zenilda Vieira](https://github.com/gzaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
