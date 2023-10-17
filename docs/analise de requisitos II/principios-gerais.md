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
A diretriz de Correspondência com as Expectativas dos Usuários não é seguida no site "Nota Legal", um exemplo disso pode ser visto na imagem X, onde o título do footer do site diz "Fale conosco", porém, o footer contém inúmeras coisas, e não somente formas de contato. Além disso, as formas de contato estão do outro lado do footer. Isso quebra a expectativa do usuário, que ao ler "Fale conosco", espera informações de contato, e não um menu. A ordem não é natural. Por causa das violações, esta diretriz será aplicada e corrigida em nosso projeto.
<br>
<div align="center">
<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/0ae026e487f939a3286124807410c4989c318df4/docs/imagens/principios-gerais/expectativa-usuario.png" style="width: 75%;height=auto;">
<p>Figura X - Footer do site Nota Legal. Fonte: Izabella Alves, 2023.</p>
</div>

### Simplicidade nas Estruturas das Tarefas
A diretriz de Simplicidade nas Estruturas das Tarefas no geral está sendo bem seguida no site "Nota Legal", as tarefas que podem ser realizadas no site possuem uma complexidade aceitável e não hà nada complexo demais. Na figura X, é possível visualizar a tela de lançamentos de indicação do "Nota Legal", onde o usuário pode visualizar suas indicações ao informar o tipo de lançamento e o exercício. Esta tarefa tem uma boa complexidade e uma baixa quantidade de planejamento para que seja executada, portanto, em nosso projeto vamos manter este modelo de estrutura das tarefas.
<br>
<div align="center">
<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/e129fbf160ec8541e7ee312cd5a371f05bc36625/docs/imagens/principios-gerais/simplicidade-tarefas.png" style="width: 75%;height=auto;">
<p>Figura X - Tela de visualização e lançamentos de indicação do site Nota Legal. Fonte: Izabella Alves, 2023.</p>
</div>

### Equilíbrio entre Controle e Liberdade do Usuário
A diretriz de Equilíbrio entre Controle e Liberdade do Usuário é violada no site "Nota Legal", um exemplo de violação pode ser visto na figura X, onde o usuário é obrigado a continuar na tela de carregamento, pois o site não possui nenhum mecanismo para que o usuário cancele, desfaça ou refaça suas ações. De acordo com o Equilíbrio entre Controle e Liberdade do Usuário, os usuários não devem ﬁcar presos num caminho de interação único para realizar uma atividade [1], por isso, esta diretriz será aplicada e corrigida no nosso projeto.
<br>
<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/liberdade-usuario.png?raw=true" style="width: 75%;height=auto;">
<p>Figura X - Tela de carregamento do site Nota Legal. Fonte: Izabella Alves, 2023.</p>
</div>


### Consistência e Padronização
### Promovendo a Eﬁciência do Usuário
### Antecipação

### Visibilidade e Reconhecimento
Em geral, o site Nota legal mantém o usuário atualizado do status atual do sistema com informações claras e de fácil persepção, fornecendo feedbacks (resposta do sistema) sutis e no tempo certo. Na figura X, é possível ver como o site informa o usuário que está ocorrendo um carregamento de página atráves de uma "ampulheta" animada no meio da tela, indicando que o sistema não está travado.

<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/nota_legal.gif" width="533" height="300">
<p>Figura X - Status de carregamento do site Nota Legal. Fonte: Gabriel Zaranza, 2023.</p>
</div>

Porém, esse carregamento de página pode passar dos 30 segundos (Vídeo 1) e de acordo com Tognazzini (2003), quando uma ação ultrapassa 2 segundos de execução, o sistema deverá informar a demora estimada junto a uma barra de progresso, fornecer opções de cancelar a ação ao usuário e para casos de ultrapassar 10 segundos o sistema deve emitir um aviso sonoro e visual indicando o final da ação [2]. Nesse quesito o site Nota Legal viola a diretriz de Visibilidade e Reconhecimento.

<iframe width="560" height="315" src="https://youtu.be/fC5Dodn3MZQ" title="Tela de carregamento do Login do site Nota Legal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<div align="center">
<p>Vídeo X - Tela de carregamento violando a diretriz de Visibilidade e Reconhecimento. Fonte: Gabriel Zaranza, 2023.</p>
</div>

Outros pontos relacionados à Visibilidade e Reconhecimento são informar ao usuário o caminho que ele percorreu no sistema e os objetos, ações e as opções devem ser atualizadas e facilmente perceptíveis (Tognazzini, 2003). Na figura X, pode-se observar que o site Nota Legal mostra ao usuário o caminho que ele seguiu até determinada página e atualiza as opções e ações que ele pode executar nessa nova página. Importante ressaltar que essas informações são fornecidas no centro da página e destacadas do background do site, fazendo com que o usuário as encontre de maneira rápida.

<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/Visibilidade%20e%20reconhecimento.png?raw=true" style="width: 75%;height=auto;">
<p>Figura X - Exemplo de caminho que o usário percorreu dentro do site Nota legal e as opções de ações da página "Documentos Fiscais". Fonte: Gabriel Zaranza, 2023.</p>
</div>

### Conteúdo Relevante e Expressão Adequada

O site do Nota Legal aprensenta um design minimalista e com poucos elementos ao longo de suas páginas, principalemte quando se fala da página do usuário. Um dos quesitos dessa diretriz é o principio estético e minimalista definido por Nilsen (1993), em que deve-se mostrar para o usuário apenas informação relevantes e comumente usadas no contexto das tarefas [1]. Na figura X, pode-se observar que o menu principal da página do usuário contém apenas as opções de funcionalidades do sistema e o saldo do Nota Legal. Esse padrão de mostrar apenas as opções de funcionalidades sem textos ou elementos extras é replicado ao longo de todo o site, como por exemplo na página de indicação mostrada na figura X.

<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/menu_nota_legal.png?raw=true" style="width: 75%;height=auto;">
<p>Figura X - Página principal da conta de usuário do Nota Legal. Fonte: Gabriel Zaranza, 2023.</p>
</div>

<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/pag_estornar_indicacao.png" style="width: 75%;height=auto;">
<p>Figura X - Página onde realiza a indicação do saldo do Nota Legal. Fonte: Gabriel Zaranza, 2023.</p>
</div>

Outro ponto que está de acordo com a diretriz em questão, é a clareza e legibilidade dos textos presentes nos botões e rótulos do site, como é observado nas Figuras X e X. Pode-se resaltar a presença de contraste dos textos em relação ao fundo, além da funcionalidade de alto contraste presente em todo site (Figura X). Porém, não existem as funcionalidades de aumentar o tamanho da fonte dos textos e modo daltônico que são recomendadas por Tognazzini (2003).

<div align="center">
<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/principios-gerais/alto_contraste.png?raw=true" style="width: 75%;height=auto;">
<p>Figura X - Funcionalidade de alto contraste ativada no site Nota Legal. Fonte: Gabriel Zaranza, 2023.</p>
</div>

### Projeto para Erros

## Referências Bibliográficas
> [1] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> [2] TOGNAZZINI, B. First principles of interaction design. 2003.


## Bibliografia
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/10/2023|Criação do documento|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.1`|16/10/2023|Adição de analise|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|`1.2`|16/10/2023|Adição de analise Visibilidade e Reconhecimento|[Gabriel Zaranza](https://github.com/gzaranza)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.2`|16/10/2023|Adição de analise Conteúdo Relevante e Expressão Adequada|[Gabriel Zaranza](https://github.com/gzaranza)|[Izabella Alves](https://github.com/izabellaalves)|
