# Árvore de Tarefas Concorrentes (CTT)

## Introdução

O CTT (Árvore de Tarefas Concorrentes) é uma técnica de análise de tarefas que permite representar graficamente as relações entre as tarefas que um usuário realiza em um sistema interativo. O CTT utiliza uma notação simples e expressiva para descrever as condições, as tarefas e os testes que compõem um cenário de uso. O CTT também permite especificar as propriedades temporais e lógicas das tarefas, como a ordem, a concorrência, a interrupção e a escolha. O CTT é útil para modelar e analisar os requisitos funcionais de um sistema, bem como para avaliar a usabilidade e a acessibilidade do mesmo.

## Metodologia

O primeiro passo na metodologia do CTT é identificar as tarefas que os usuários precisam realizar. Isso pode ser feito através de entrevistas com os usuários, observação direta, ou análise de documentos e manuais existentes. Uma vez que as tarefas são identificadas, elas são organizadas em uma árvore hierárquica. A árvore começa com a tarefa principal no topo, e então se ramifica para subtarefas mais específicas. Cada nó na árvore representa uma tarefa, e as arestas representam as relações entre as tarefas. Depois que a árvore de tarefas é desenvolvida, cada tarefa é analisada em detalhes. Isso inclui a identificação das condições necessárias para a tarefa, os passos envolvidos na realização da tarefa, e os critérios para determinar se a tarefa foi concluída com sucesso. As tarefas e suas relações são então representadas graficamente usando a notação do CTT. Isso inclui símbolos para representar diferentes tipos de tarefas (por exemplo, tarefas de usuário, tarefas de sistema), e operadores para representar as relações entre as tarefas (por exemplo, sequência, concorrência). Finalmente, a árvore de tarefas é usada para avaliar a usabilidade do sistema. Isso pode incluir a identificação de possíveis problemas de usabilidade, a avaliação da eficiência das tarefas, e a sugestão de melhorias no design do sistema. Visando 

As tarefas analisadas neste documento foram baseadas nos [cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md) feitos pela equipe, e o responsável por cada análise foi definido na tabela 2.

Para criarmos o diagrama CTT, utilizaremos os seguintes símbolos contidos na tabela 1.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Legenda Diagrama CTT</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/Legenda.png?raw=true">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div>

## CTT

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Definição de membro da equipe que trabalhou em determinado cenário</p></font>

<table>
    <thead>
        <tr>
            <th>Membro da Equipe</th>
            <th>Cenário</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/gabrielrosa09">Gabriel Rosa</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#registrar-nova-reclama%C3%A7%C3%A3o">Registrar nova reclamação</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#desbloquear-saldo">Desbloquear saldo</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/izabellaalves">Izabella Alves</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#consultar-um-estabelecimento">Consultar estabelecimento</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#visualizar-recibo-fiscal">Visualizar recibo fiscal</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#consultar-reclama%C3%A7%C3%A3o">Consultar reclamação</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/Lucas13032003">Lucas Víctor</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#consultar-extrato">Consultar extrato</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
            <td><a href="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/ctt.md#consultar-resultado-de-sorteio">Consultar resultado de sorteio</a></td>
        </tr>
    </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>

</div>

### Registrar nova reclamação

Nessa tarefa, o usuário tem como objetivo registrar uma reclamação no site do Nota Legal, é possível verificar o cenário que se baseia nessa tarefa nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#registrar-nova-reclama%C3%A7%C3%A3o). Na figura 1 é possível ver o digrama CTT da tarefa registrar reclamação.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama CTT para registrar uma reclamação</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/Diagrama%20CTT%20Registrar%20Reclama%C3%A7%C3%A3o.jpg?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>, 2023</p></font>
</div>

### Desbloquear saldo

Nessa tarefa, o usuário possui como principal objetivo desbloquear o saldo de documentos fiscais que a Secretaria de Fazenda do Distrito Federal (SEFAZ-DF) bloqueou no Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#desbloquear-saldo). Na figura 2 é possível ver o diagrama CTT da tarefa em questão.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 2:</b> Diagrama CTT da tarefa Desbloquear saldo</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/CTT%20-%20Desbloquear%20saldo%20(1).png?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023</p></font>
</div>

### Consultar um estabelecimento

Nessa tarefa, o usuário possui como principal objetivo consultar se determinado estabelecimento é ou não cadastrado no programa Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-estabelecimento). Na figura 3 é possível ver o diagrama CTT da tarefa em questão.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 3:</b> Diagrama CTT da tarefa Consultar um estabelecimento</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/ctt-consultar-estabelecimento.png?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Visualizar recibo de indicação

O objetivo principal da tarefa a seguir é visualizar os recidos de indicação do programa Nota Legal do GDF. No documento de [cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-resultado-de-sorteio) é ilustrado um exemplo dessa tarefa sendo realizada. A Figura 4 abaixo mostra o diagrama CTT para esse cenário.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 4:</b> Diagrama CTT da tarefa Visualizar recibo fiscal</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/ctt_consultar_resultado_sorteio.png?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas de Oliveira</a>, 2023</p></font>
</div>

### Consultar reclamação

Nesta tarefa, os usuários buscam consultar reclamações no site "Nota Legal", essencial para acompanhar interações com estabelecimentos do programa. É possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-reclama%C3%A7%C3%A3o). A Figura 5 do diagrama CTT revela um processo eficiente e transparente, destacando a importância da transparência nas relações consumidor-estabelecimento.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 5:</b> Diagrama CTT da tarefa Consultar Reclamação</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/CTT%20-%20Consultar%20Reclama%C3%A7%C3%A3o.drawio.png?raw=true" class="usecaseElement">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div>

### Consultar extrato

Nesta tarefa, o objetivo visualizar o extrato de transações no site "Nota Legal" para acompanhar e registrar suas interações financeiras com os estabelecimentos cadastrados no programa. É possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-extrato). Na figura 6 é possível ver o diagrama CTT da tarefa em questão.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 1:</b> Diagrama CTT para Consultar Extrato</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/Consultar_Extrato.png?raw=true">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucas13032003">Lucas Víctor</a>, 2023</p></font>
</div>

### Consultar resultado de sorteio

O objetivo principal da tarefa a seguir é consultar o resultado dos sorteios que são realizados semestralmente pelo programa Nota Legal do GDF. No documento de [cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-resultado-de-sorteio) é ilustrado um exemplo dessa tarefa sendo realizada. A Figura 7 abaixo mostra o diagrama CTT para esse cenário.

<div align="center">
<font size="3"><p style="text-align: center"><b>Figura 7:</b> Diagrama CTT para Consultar resultado de sorteio</p></font>

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/ctt_consultar_resultado_sorteio.png?raw=true" style="width: 75%; height: auto;">

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Bibliografia

> SALES, André Barros. Apresentação Cap6 . Disponível em: https://aprender3.unb.br/pluginfile.php/2692526/mod_resource/content/4/Apresentacao%20cap06.pdf. Acesso em: 03 de outubro de 2023;
>
> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|08/10/2023|Criação do documento e adição do ctt de consultar estabelecimentos|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|11/10/2023|Adição do ctt de consultar extrato|[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.2`|11/10/2023|Adição do ctt de desbloquear saldo|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.3`|12/10/2023|Adição do ctt de consultar reclamação|[Lucas Ribeiro](https://github.com/lucassouzs)|[Lucas Víctor](https://github.com/Lucas13032003)|
|`1.4`|12/10/2023|Adição do ctt de consultar resultado de sorteio|[Zenilda Vieira](https://github.com/zenildavieira)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.5`|12/10/2023|Adição do ctt de registrar nova reclamação|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Zenilda Vieira](https://github.com/zenildavieira)|
|`1.6`|12/10/2023|Adição do diagrama ctt de consultar extrato|[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.7`|13/10/2023|Revisão do ctt de registrar nova reclamação|[Zenilda Vieira](https://github.com/zenildavieira)| - (revisão não precisa de revisor) |
|`1.8`|16/10/2023|Adição da legenda do diagrama ctt |[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas Ribeiro](https://github.com/lucassouzs)|
