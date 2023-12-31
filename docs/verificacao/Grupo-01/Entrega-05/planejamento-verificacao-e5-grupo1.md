# Planejamento da Verificação da Etapa 5 do Grupo 1

## Introdução

A verificação e validação (V&V) são processos fundamentais no desenvolvimento de software, desempenhando papéis cruciais na garantia da qualidade e confiabilidade dos artefatos produzidos. A verificação refere-se à avaliação sistemática dos artefatos de software para garantir que eles atendam aos requisitos e padrões especificados. Este processo concentra-se na análise estática e dinâmica do código, na conformidade com as diretrizes de codificação, na identificação de erros e na garantia de que o software seja construído de acordo com as expectativas.

Dito isso, este documento fará a verificação da entrega 5 realizada pelo [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/), que está trabalhando com o site Nota Legal, na disciplina Interação Humano Computador.

## Objetivos

O propósito deste documento é realizar uma verificação minuciosa dos artefatos desenvolvidos pelo [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) durante a etapa 5, que abrange os temas de Design, Avaliação e Desenvolvimento II. O objetivo é assegurar que esses artefatos estejam em plena conformidade com os requisitos estabelecidos na disciplina de Interação Humano-Computador, bem como em alinhamento com os padrões consagrados na literatura especializada nesse campo. Essa análise visa garantir a qualidade e a aderência às melhores práticas, contribuindo para o desenvolvimento de artefatos ainda melhores para o projeto.

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

Os integrantes do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) responsáveis por fazer a verificação da Entrega 5 do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/) são [Gabriel Zaranza](https://github.com/GZaranza), [Izabella Alves](https://github.com/izabellaalves), [Lucas De Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira), [Lucas Ribeiro](https://github.com/lucassouzs), [Lucas Víctor](https://github.com/Lucas13032003) e [Zenilda Vieira](https://github.com/zenildavieira). Estes participantes farão a verificação de todos os documentos produzidos na Entrega 5 e documentarão os resultados encontrados, que serão revisados por [Gabriel Rosa](https://github.com/gabrielrosa09), também integrante do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

## Objetos de verificação

A tabela 1 mostra os artefatos que serão inspecionados durante o processo de verificação.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Artefatos que serão verificados. </p></font>

<table>

<thead>
    <tr>
        <th>Artefato</th>
        <th>Versão</th>
        <th>Data</th>
        <th>Autor</th>
    </tr>
</thead>
<tbody>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/prototipos-de-papel/">Protótipos de Papel</a></td>
      <td>1.4</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/planejamento_avaliacao_prototipo_papel/">Planejamento da avaliação do protótipo de papel</a></td>
      <td>1.3</td>
      <td>07/11/2023</td>
      <td><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/planejamento_relato_prototipo_papel/">Planejamento do relato dos resultados da avaliação do Protótipo de Papel</a></td>
      <td>1.3</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/modelo-relato-prototipo-papel/">Documento Modelo - Relato dos resultados da avaliação do Protótipo de Papel</a></td>
      <td>1.0</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar_extrato/">Relato dos resultados da avaliação da análise de tarefa "Consultar extrato"</a></td>
      <td>1.1</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-estabelecimento/">Relato dos resultados da avaliação da análise de tarefa "Consultar estabelecimento"</a></td>
      <td>1.1</td>
      <td>02/11/2023</td>
      <td><a href="https://github.com/izabellaalves">Izabella Alves</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-sorteio/">Relato dos resultados da avaliação da Análise da Tarefa "Consultar Sorteio"</a></td>
      <td>1.1</td>
      <td>05/11/2023</td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
     </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/desbloquear_saldo/">Relato dos resultados da avaliação do Storyboard "Desbloquear Saldo"</a></td>
      <td>1.0</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/registrar_reclamacao/">Relato dos resultados da avaliação da análise de tarefa "Registro de uma reclamação"</a></td>
      <td>1.1</td>
      <td>05/11/2023</td>
      <td><a href="https://github.com/gabrielrosa09">Gabriel Rosa</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/visualizar_recibo/">Relato dos resultados da avaliação da análise de tarefa "Visualizar Recibo de Indicação"</a></td>
      <td>1.1</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação da análise de tarefa "Consultar reclamação"</a></td>
      <td>1.1</td>
      <td>08/11/2023</td>
      <td><a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar_extrato/">Relato dos resultados da avaliação do Storyboard "Consultar Extrato"</a></td>
      <td>1.0</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/Lucas13032003">Lucas Victor</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-estabelecimento/">Relato dos resultados da avaliação do Storyboard "Consultar Estabelecimento"</a></td>
      <td>1.1</td>
      <td>02/11/2023</td>
      <td><a href="https://github.com/izabellaalves">Izabella Alves</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-sorteio/">Relato dos resultados da avaliação do Storyboard "Consultar Sorteio"</a></td>
      <td>1.1</td>
      <td>05/11/2023</td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/desbloquear_saldo/">Relato dos resultados da avaliação do Storyboard "Desbloquear Saldo"</a></td>
      <td>1.0</td>
      <td>31/10/2023</td>
      <td><a href="https://github.com/GZaranza">Gabriel Zaranza</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/registrar_reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação do Storyboard "Registrar uma reclamação"</a></td>
      <td>1.1</td>
      <td>02/11/2023</td>
      <td><a href="https://github.com/gabrielrosa09">Gabriel Rosa</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/visualizar_recibo/">Relato dos resultados da avaliação do StoryBoard "Visualizar Recibo de Indicação"</a></td>
      <td>1.1</td>
      <td>06/11/2023</td>
      <td><a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a></td>
    </tr>
    <tr>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação do Storyboard "Consultar Reclamação"</a></td>
      <td>1.1</td>
      <td>08/11/2023</td>
      <td><a href="https://github.com/lucassouzs">Lucas Ribeiro</a> </td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a> , 2023</p></font>
</div>

## Cronograma

A verificação será executada entre os dias 18/11/2023 e 03/12/2023, as atividades desenvolvidas nesse processo estão na Tabela 2.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Cronograma de verificação da etapa 5. </p></font>


<table>

<thead>
    <tr>
        <th>Data</th>
        <th>Descrição</th>
        <th>Responsável</th>
    </tr>
</thead>
<tbody>
    <tr>
      <td>03/11/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/prototipos-de-papel/">Protótipos de Papel</a></td>
      <td>
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a> <br> 
        <a href="https://github.com/Lucas13032003">Lucas Victor</a>
      </td>
    </tr>
    <tr>
      <td>03/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/planejamento_avaliacao_prototipo_papel/">Planejamento da avaliação do protótipo de papel</a></td>
      <td>
        <a href="https://github.com/GZaranza">Gabriel Zaranza</a> <br> 
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>
      </td>
    </tr>
    <tr>
      <td>03/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/prototipo_papel/planejamento_relato_prototipo_papel/">Planejamento do relato dos resultados da avaliação do Protótipo de Papel</a></td>
      <td>
        <a href="https://github.com/GZaranza">Gabriel Zaranza</a> <br> 
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>
      </td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar_extrato/">Relato dos resultados da avaliação da análise de tarefa "Consultar extrato"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-estabelecimento/">Relato dos resultados da avaliação da análise de tarefa "Consultar estabelecimento"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-sorteio/">Relato dos resultados da avaliação da Análise da Tarefa "Consultar Sorteio"</a></td>
      <td>
        <a href="https://github.com/LucasOliveiraDiasmarquesFerreira">Lucas Oliveira</a> <br> 
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
      </td>
     </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/desbloquear_saldo/">Relato dos resultados da avaliação de análise de tarefa "Desbloquear Saldo"</a></td>
      <td>
        <a href="https://github.com/zenildavieira">Zenilda Vieira</a> <br>
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>
      </td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/registrar_reclamacao/">Relato dos resultados da avaliação da análise de tarefa "Registro de uma reclamação"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>25/11/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/visualizar_recibo/">Relato dos resultados da avaliação da análise de tarefa "Visualizar Recibo de Indicação"</a></td>
      <td>
        <a href="https://github.com/zenildavieira">Zenilda Vieira</a>
      </td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20analise%20de%20tarefas/consultar-reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação da análise de tarefa "Consultar reclamação"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar_extrato/">Relato dos resultados da avaliação do Storyboard "Consultar Extrato"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-estabelecimento/">Relato dos resultados da avaliação do Storyboard "Consultar Estabelecimento"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/11/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-sorteio/">Relato dos resultados da avaliação do Storyboard "Consultar Sorteio"</a></td>
      <td>
        <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a> <br> 
        <a href="https://github.com/lucassouzs">Lucas Ribeiro</a></td>
    </tr>
    <tr>
      <td>24/11/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/desbloquear_saldo/">Relato dos resultados da avaliação do Storyboard "Consultar Estabelecimento"</a></td>
      <td>
        <a href="https://github.com/zenildavieira">Zenilda Vieira</a> <br> 
        <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a>
      </td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/registrar_reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação do Storyboard "Registrar uma reclamação"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/visualizar_recibo/">Relato dos resultados da avaliação do StoryBoard "Visualizar Recibo de Indicação"</a></td>
      <td>
        <a href="https://github.com/zenildavieira">Zenilda Vieira</a>
      </td>
    </tr>
    <tr>
      <td>02/12/2023</td>
      <td><a href="https://interacao-humano-computador.github.io/2023.2-NotaLegal/design-avaliacao-desenvolvimento%20II/relatos%20dos%20resultados%20-%20storyboard/consultar-reclama%C3%A7%C3%A3o/">Relato dos resultados da avaliação do Storyboard "Consultar Reclamação"</a></td>
      <td><a href="https://github.com/zenildavieira">Zenilda Vieira</a></td>
    </tr>
  </tbody>
</tbody>
</table>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a> , 2023</p></font>
</div>

## Checklists

Nesta etapa, será definido um checklist de verificação geral, que deve ser aplicado a todos os artefatos, e um checklist específico para cada artefato. As questões disponíveis no checklist devem ser respondidas com Sim, Não, Incompleto ou Não Se Aplica, onde Sim e Não significam que o artefato está em conformidade ou não com o item analisado.

Além disso, as observações devem ser registradas após a tabela, indicando o ID respectivo que gerou a observação.

### Checklist Geral

Na tabela 3, estão listados os critérios que devem ser verificados em todos os artefatos da Entrega 5 do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Checklist para todos os artefatos da Entrega 3</p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Descrição</th>
      <th>Fonte</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>O artefato possui histórico de versão padronizado com pelo menos data, descrição, autores e revisores?</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>2</td>
      <td>O artefato possui bibliografia e/ou referência bibliográfica? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td>3</td>
      <td>As referências bibliográficas seguem a ordem de chamada do texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Todas as referências bibliográficas são chamadas no texto? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-1.png?raw=true"></td>
    </tr>
    <tr>
      <td>5</td>
      <td>O artefato possui introdução? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-2.png?raw=true"></td>
    </tr>
    <tr>
      <td>6</td>
      <td>Todas as tabelas possuem legendas e fontes padronizadas? [2]</td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-4.png?raw=true"></td>
    </tr>
    <tr>
      <td>7</td>
      <td>Todas as tabelas são referenciadas no texto? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
      <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-5.png?raw=true"></td>
    </tr>
    <tr>
      <td>8</td>
      <td>Todas as figuras possuem legendas e fontes padronizadas e todas utilizam a palavra "figura" e não "imagem"? [2] </td>
      <td>Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.</td>
     <td> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2023.2-Economia-DF/main/docs/imagens/e3-4.png?raw=true"></td>
    </tr>
  </tbody>
</table>

<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/zenildavieira">Zenilda Vieira</a> e <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023</p></font>
</div>

### Checklist do Relato dos Resultados da Análise de Tarefas

Na tabela 3, estão listados os critérios que devem ser verificados no Relato dos Resultados das Análises de Tarefas de todos os integrantes do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 3:</b> Checklist de Verificação para o artefato Relato dos Resultados das Análise de Trarefas</p>
  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O artefato descreve os objetivos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve o método empregado na avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve as questões práticas da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve as questões éticas da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato apresenta o participante selecionado? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato possui um cronograma executado da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato possui um tópico para a apresentação dos dados obtidos? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato possui uma gravação da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>09</td>
      <td>O artefato possui um tópico para análise dos resultados? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>Caso necessário, o artefato possui um cronograma para a correção? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>11</td>
      <td>O artefato segue o padrão definido no "Planejamento do Relato dos Resultados" proposto pelo grupo? </td>
      <td></td>
    </tr>
  </table>

<p><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</p>
</div>

### Checklist do Relato dos Resultados do Storyboard

Na tabela 4, estão listados os critérios que devem ser verificados no Relato dos Resultados dos Storyboards de todos os integrantes do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 4:</b> Checklist de Verificação para o artefato Relato dos Resultados dos Storyboards</p>
  <table>
    <tr>
      <th>ID</th>
      <th>Critério</th>
      <th>Avaliação</th>
    </tr>
    <tr>
      <td>01</td>
      <td>O artefato descreve os objetivos da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>02</td>
      <td>O artefato descreve o método empregado na avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>03</td>
      <td>O artefato descreve as questões práticas da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>04</td>
      <td>O artefato descreve as questões éticas da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>05</td>
      <td>O artefato apresenta o participante selecionado? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>06</td>
      <td>O artefato possui um cronograma executado da avaliação?</td>
      <td></td>
    </tr>
    <tr>
      <td>07</td>
      <td>O artefato possui um tópico para a apresentação dos dados obtidos? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>08</td>
      <td>O artefato possui uma gravação da avaliação? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>09</td>
      <td>O artefato possui um tópico para análise dos resultados? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>10</td>
      <td>Caso necessário, o artefato possui um cronograma para a correção? [3]</td>
      <td></td>
    </tr>
    <tr>
      <td>11</td>
      <td>O artefato segue o padrão definido no "Planejamento do Relato dos Resultados" proposto pelo grupo? </td>
      <td></td>
    </tr>
  </table>


<p><b>Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</p>
</div>

### Checklist do Planejamento da avaliação do Protótipo de Papel

Na tabela 6, estão listados os critérios que devem ser verificados no Planejamento da avaliação do Protótipo de Papel do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 6:</b> Checklist de Verificação para o artefato Planejamento da avaliação do Protótipo de Papel</p>
 
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

<p><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023.</p>
</div>

### Checklist do Planejamento do relato dos resultados da avaliação do Protótipo de Papel

Na tabela 6, estão listados os critérios que devem ser verificados no Planejamento do relato dos resultados da avaliação do Protótipo de Papel do [Grupo 1](https://interacao-humano-computador.github.io/2023.2-NotaLegal/).

<div align="center">
  <p><b>Tabela 6:</b> Checklist de Verificação para o artefato Planejamento do relato dos resultados da avaliação do Protótipo de Papel</p>
 
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

<p><b>Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023.</p>
</div>



## Referências Bibliográficas

> [1] FAGAN, Michael E. Design and Code Inspections to Reduce Errors in Program Development. 1976.
> 
> [2] Normas ABNT: 2023. Disponível em: <a href="https://www.normasabnt.org/normas-abnt-2023/">https://www.normasabnt.org/normas-abnt-2023/</a>. Acesso em: 18 de novembro de 2023.
>
> [3] BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
>
> [4] PUC-PR. Comitê de Ética e Pesquisa – CEP. Paraná, 2017. Disponível em: <https://www.pucpr.br/estudante/graduacao/iniciacao-cientifica/cep/>. Acesso em: 20 de novembro de 2023.

## Histórico de versões


| Versão | Data       | Descrição                                 | Autor(es)                                                                                           | Revisor(es)                                      |
| ------ | ---------- | ----------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------- |
| `1.0`  | 09/11/2023 | Criação do documento                | [Izabella Alves](https://github.com/izabellaalves) | [Gabriel Rosa](https://github.com/gabrielrosa09)|
| `1.1`  | 24/11/2023 | Objetos de verificação               | [Zenilda Vieira](https://github.com/zenildavieira) | [Gabriel Rosa](https://github.com/gabrielrosa09)|
| `1.2`  | 03/12/2023 | Imagens de referências do checklist geral e datas | [Zenilda Vieira](https://github.com/zenildavieira) | [Gabriel Rosa](https://github.com/gabrielrosa09)|
