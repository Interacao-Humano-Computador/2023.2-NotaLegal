# Planejamento da Verificação da Etapa 4 do Grupo 1

## Introdução

A verificação e validação (V&V) são processos fundamentais no desenvolvimento de software, desempenhando papéis cruciais na garantia da qualidade e confiabilidade dos artefatos produzidos. A verificação refere-se à avaliação sistemática dos artefatos de software para garantir que eles atendam aos requisitos e padrões especificados. Este processo concentra-se na análise estática e dinâmica do código, na conformidade com as diretrizes de codificação, na identificação de erros e na garantia de que o software seja construído de acordo com as expectativas.

Dito isso, este documento fará a verificação da entrega 3 realizada pelo [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/), que está trabalhando com o site Nota Legal, na disciplina Interação Humano Computador.

## Objetivos

O propósito deste documento é realizar uma verificação minuciosa dos artefatos desenvolvidos pelo [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) durante a etapa 4, que abrange os temas de Design, Avaliação e Desenvolvimento. O objetivo é assegurar que esses artefatos estejam em plena conformidade com os requisitos estabelecidos na disciplina de Interação Humano-Computador, bem como em alinhamento com os padrões consagrados na literatura especializada nesse campo. Essa análise visa garantir a qualidade e a aderência às melhores práticas, contribuindo para o desenvolvimento de artefatos ainda melhores para o projeto.

## Metodologia


A metodologia que será utilizada na verificação dos artefatos do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) é a de Inspeção, desenvolvida por Michael E. Fagan [1], que é uma abordagem estruturada para revisão de código e outros artefatos de software. Essa metodologia tem como objetivo identificar e corrigir defeitos de forma eficiente durante o processo de desenvolvimento. A inspeção por Fagan é conhecida por sua abordagem sistemática e rigorosa, enfocando a detecção precoce de erros para melhorar a qualidade do software. 

Este método pode ser dividido em 5 etapas:

- **Preparação:** antes da reunião de inspeção, o autor do artefato (por exemplo, código-fonte) prepara um documento contendo o artefato a ser revisado, além de informações sobre seu contexto e propósito.

- **Inspeção Individual:** os participantes (inspetores) revisam o documento individualmente antes da reunião de inspeção. Cada inspetor concentra-se na identificação de erros, como bugs, inconsistências ou violações de padrões de codificação.

- **Reunião de Inspeção:** durante a reunião, os inspetores se reúnem com o autor para discutir os problemas identificados. O autor não participa ativamente da inspeção durante a fase individual, permitindo uma revisão mais imparcial.

- **Correção e Reinspeção:** o autor corrige os problemas identificados durante a reunião de inspeção. Em seguida, o artefato é reinspecionado para garantir que as correções foram efetuadas adequadamente.

- **Acompanhamento:** a metodologia de Fagan enfatiza a coleta de métricas e dados sobre o processo de inspeção. Isso inclui a contagem de defeitos encontrados, tempo gasto e eficácia geral do processo.

Nesta verificação, chegaremos até a etapa de Correção e Reinspeção, pois após a verificação, os erros encontrados serão devidamente corrigidos.


## Participantes

O integrante do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) responsável por fazer a verificação da Entrega 3 do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) é [Izabella Alves](https://github.com/izabellaalves). Este participante fará a verificação de todos os documentos produzidos na Entrega 3 e documentará os resultados encontrados, que serão revisados pela [Zenilda Vieira](https://github.com/izabellaalves), também integrante do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/). ALém disso, [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira), do mesmo grupo, participará como observador, acompanhando a verificação e auxiliando no processo.

## Objetos de verificação

Os artefatos serão verificados no dia 10/11/2023, e o detalhamento da verificação de cada artefato está disponível na tabela 1.

<div align="center">
<p><b>Tabela 2:</b> Cronograma de verificação da etapa 4.</p>

<table>
  <thead>
    <tr>
      <th>Artefato</th>
      <th>Versão</th>
      <th>Data de Verificação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento-avaliacao-storyboard/">Planejamento da Avaliação do Storyboard</a></td>
      <td>1.5</td>
      <td>XX/11/2023</td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento-relato_storyboard/">Planejamento do Relato dos Resultados da Avaliação do Storyboard</a></td>
      <td>1.2</td>
      <td>XX/11/2023</td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/storyboards/">Storyboards</a></td>
      <td>1.5</td>
      <td>10/11/2023</td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento_analise_tarefas/">Planejamento da Avaliação da Análise de Tarefas</a></td>
      <td>1.4</td>
      <td>XX/11/2023</td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento_relato_tarefas2.md">Planejamento do Relato dos Resultados da Análise de Tarefas</a></td>
      <td>1.3</td>
      <td>XX/11/2023</td>
    </tr>
  </tbody>
</table>
<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

## Checklists

Nesta etapa, será definido um checklist de verificação geral, que deve ser aplicado a todos os artefatos, e um checklist específico para cada artefato. As questões disponíveis no checklist devem ser respondidas com Sim, Não, Incompleto ou Não Se Aplica.

Além disso, as observações devem ser registradas após a tabela, indicando o ID respectivo que gerou a observação.

Os checklists criados se baseiam nos critérios estabelecidos no Plano de Ensino da disciplina Interação Humano Computador [1], bem como na observação dos projetos dos semestres anteriores, e dos feedbacks dados pelos monitores e pelo Professor após as apresentações.



### Checklist Geral

Na tabela 2, estão listados os critérios que devem ser verificados em todos os artefatos da Entrega 4 do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Checklist para todos os artefatos da Entrega 4</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Avaliação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado com pelo menos data, descrição, autores e revisores?</td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica? [2] </td>
      <td></td>
    </tr>
    <tr>
      <td>3</td>
      <td>As referências bibliográficas seguem a ordem de chamada do texto? [2]</td>
      <td></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as referências bibliográficas são chamadas no texto? [2]</td>
      <td></td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui introdução? [2]</td>
      <td></td>
    </tr>
    <tr>
      <td>6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas? [2]</td>
      <td></td>
    </tr>
    <tr>
      <td>7</td>
      <td>Todas as tabelas são referenciadas no texto? [2] </td>
      <td></td>
    </tr>
    <tr>
      <td>8</td>
      <td>Todas as figuras possuem legendas e fontes padronizadas e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td></td>
    </tr>
    <tr>
      <td>9</td>
      <td>Todas as figuras são referenciadas no texto e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Checklist de Planejamento da Avaliação do Storyboard

Na tabela 4, estão listados os critérios que devem ser verificados no [Planejamento da Avaliação do Storyboard](https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento-avaliacao-storyboard/) do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
<p><b>Tabela 4:</b> Checklist de Verificação do artefato "Planejamento da Avaliação do Storyboard".</p>

  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O planejamento da avaliação segue o Framework DECIDE? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve os objetivos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve os métodos a serem utilizados? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve os aspectos práticos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato descreve os aspectos éticos da avaliação? [4]</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato descreve as perguntas a serem feitas na avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato possui um cronograma planejado para a execução da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato apresenta o teste piloto do planejamento da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>09</td>
      <td>O artefato apresenta o motivo do número da escolha dos participantes? [3]</td>
      <td></td>
    </tr>
  </table>

<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist de Planejamento do Relato dos Resultados da Avaliação do Storyboard

Na tabela 5, estão listados os critérios que devem ser verificados no [Planejamento do Relato dos Resultados da Avaliação do Storyboard](https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento-relato_storyboard/) do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 5:</b> Checklist de Verificação para o artefato "Planejamento do Relato dos Resultados da Avaliação do Storyboard"</p>
  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O artefato descreve os objetivos do relato dos resultados da avaliação? [3] </td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve os métodos utilizados? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve como devem ser apresentados os aspectos práticos do relato dos resultados da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve como devem ser apresentados os aspectos éticos do relato dos resultados da avaliação? [4]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato descreve como devem ser apresentados os resultados da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato descreve como devem ser apresentadas as conclusões da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato apresenta o modelo do cronograma executado da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato apresenta a estrutura do relatório a ser utilizado no relato dos resultados?</td>
      <td></td>
    </tr>
  </table>


<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist de Storyboards

Na tabela 6, estão listados os critérios que devem ser verificados nos [Storyboards](https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/storyboards/) do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).


<div align="center">
  <p><b>Tabela 6:</b> Checklist de Verificação para o artefato "Storyboard".</p>

  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>Os storyboards possuem um título? [5] </td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>Cada storyboard foi feito por um membro do grupo?</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>Um storyboard para cada tarefa apresentada pelo grupo?</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>Os storyboards possuem atores? [5]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>Os storyboards possuem cenários? [5]</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>Os storyboards possuem a satisfação do usuário ao final da cena? [5]</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>Os storyboards possuem ações do usuário? [5]</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>Os storyboards possuem objetivos? [5] </td>
      <td></td>
    </tr>
    <tr>
      <td>09</td>
      <td>Os storyboards foram feitos em papel?</td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td> O storyboard mostra um usuário progredindo em uma tarefa sobre o produto em questão? [5]</td>
      <td></td>
    </tr>
  </table>


<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist de Planejamento da Avaliação da Análise de Tarefas

Na tabela 7, estão listados os critérios que devem ser verificados no [Planejamento da Avaliação da Análise de Tarefas](https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento_analise_tarefas/) do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
<p><b>Tabela 7:</b> Checklist de Verificação do artefato "Planejamento da Avaliação da Análise de Tarefas".</p>

  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O planejamento da avaliação segue o Framework DECIDE? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve os objetivos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve os métodos a serem utilizados? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve os aspectos práticos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato descreve os aspectos éticos da avaliação? [4]</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato descreve as perguntas a serem feitas na avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato possui um cronograma planejado para a execução da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato apresenta o teste piloto do planejamento da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>09</td>
      <td>O artefato apresenta o motivo do número da escolha dos participantes? [3]</td>
      <td></td>
    </tr>
  </table>

<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

### Checklist de Planejamento do Relato dos Resultados da Análise de Tarefas

Na tabela 8, estão listados os critérios que devem ser verificados no [Planejamento do Relato dos Resultados da Análise de Tarefas](https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento/planejamento_relato_tarefas2.md) do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 8:</b> Checklist de Verificação para o artefato "Planejamento do Relato dos Resultados da Avaliação da Análise de Tarefas"</p>
  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O artefato descreve os objetivos do relato dos resultados da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve os métodos utilizados? [3] </td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve os aspectos práticos do relato dos resultados da avaliação? [3] </td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve os aspectos éticos do relato dos resultados da avaliação? [4]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato descreve os resultados da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato descreve as conclusões da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato o modelo do cronograma executado da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato apresenta a estrutura do relatório a ser utilizado no relato dos resultados?</td>
      <td></td>
    </tr>
  </table>


<p><b>Fonte:</b> Izabella Alves, 2023.</p>
</div>

## Referências Bibliográficas
>
> [1] FAGAN, Michael E. Design and Code Inspections to Reduce Errors in Program Development. 1976.
>
> [2] Normas ABNT: 2023. Disponível em: <https://www.normasabnt.org/normas-abnt-2023/>. Acesso em: 20 de novembro de 2023.
>
> [3] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> [4] PUC-PR. Comitê de Ética e Pesquisa – CEP. Paraná, 2017. Disponível em: <https://www.pucpr.br/estudante/graduacao/iniciacao-cientifica/cep/>. Acesso em: 20 de novembro de 2023.
>
> [5] Sharp, Helen & Rogers, Yvonne & Preece, Jennifer. (2007). Interaction Design. Beyond Human-Computer Interaction.


## Histórico de versões


| Versão | Data       | Descrição                                 | Autor(es)                                                                                           | Revisor(es)                                      |
| ------ | ---------- | ----------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------- |
| `1.0`  | 09/11/2023 | Criação do documento                | [Izabella Alves](https://github.com/izabellaalves) | [Zenilda Vieira](https://github.com/zenildavieira)|
