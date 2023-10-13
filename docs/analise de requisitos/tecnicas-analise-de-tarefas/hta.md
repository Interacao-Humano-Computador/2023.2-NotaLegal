## Análise Hierárquica de Tarefas

## Introdução

## Análise de Tarefas

<div align="center">

**Tabela 1:** Definição de membro da equipe que trabalhou em determinado cenário.

| Membro da Equipe | Cenário  |
| ------------------------------------------------------------------------ | ---------------------------------- |
| [Gabriel Rosa](https://github.com/gabrielrosa09)                         | [Registrar nova reclamação](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#registrar-uma-reclama%C3%A7%C3%A3o)      |
| [Gabriel Zaranza](https://github.com/GZaranza)                           | [Desbloquear saldo](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#desbloquear-saldo)              |
| [Izabella Alves](https://github.com/izabellaalves)                       | [Consultar estabelecimento](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#consultar-um-estabelecimento)      |
| [Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira) | [Visualizar recibo fiscal](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#visualizar-recibo-fiscal)       |
| [Lucas Ribeiro](https://github.com/lucassouzs)                           | [Consultar reclamação](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#consultar-reclama%C3%A7%C3%A3o)           |
| [Lucas Víctor](https://github.com/Lucas13032003)                         | [Indicar créditos](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#indicar-cr%C3%A9ditos)               |
| [Lucas Víctor](https://github.com/Lucas13032003)                         | [Consultar extrato](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#consultar-extrato)              |
| [Zenilda Vieira](https://github.com/zenildavieira)                       | [Consultar resultado de sorteio](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/tecnicas-analise-de-tarefas/hta.md#consultar-resultado-de-sorteio) |

Fonte: [Izabella Alves](https://github.com/izabellaalves),  [Lucas Víctor](https://github.com/Lucas13032003),  2023.

</div>

### Registrar uma reclamação

Nessa tarefa, o usuário possui como principal objetivo realizar uma reclamação no ambiente do Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#registrar-nova-reclama%C3%A7%C3%A3o). Na figura 1 é possível ver o diagrama HTA desta tarefa, e o mesmo HTA, só que em tabela, está visível na tabela 2.

<div align="center">

**Figura 1:** Diagrama HTA da tarefa Consultar um estabelecimento.

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/HTA%20-%20Registrar%20Reclamação.jpg?raw=true" class="usecaseElement">

Fonte: [Gabriel Rosa](https://github.com/gabrielrosa09), 2023.

</div>

<br>

<div align="center">

**Tabela 2**: Tabela HTA da tarefa registro de reclamação. 

| **Objetivos/Operações**                                     | **Problemas e Recomendações**                       |
| --------------------------------------------- | --------------------------------------------------- |
| Tarefa 0: Registrar uma reclamação no site do Nota Legal |    Nenhum problema ou recomendação listados.   |
| Tarefa 1: Navegar até a seção de "Reclamações" no menu principal | Nenhum problema ou recomendação listados. |
| Tarefa 2: Clicar no botão "Registrar nova reclamação" | **feedback**: ser redirecionado para a página de registro de reclamação.      |
| Tarefa 3: Detalhar a reclamação | Nenhum problema ou recomendação listados.      |
| Subtarefa 3.1: Anexar o documento fiscal | **input**: documento jpg ou png do documento fiscal de interesse.      |
| Subtarefa 3.2: Selecionar o tipo da nota | **input**: o usuário deve selecionar o tipo da nota, se é uma NF-E, NFC-E, NFS-E ou RPS.      |
| Subtarefa 3.3: Inserir a chave de acesso | **input**: o usuário deve inserir a chave de acesso que contém na nota.     |
| Subtarefa 3.4: Inserir o CNPJ | **input**: o usuário deve inserir o CNPJ do local em que foi emitido a nota.      |
| Subtarefa 3.5: Inserir a data de emissão | **input**: o usuário deve selecionar o dia da data de emissão do documento.      |
| Subtarefa 3.6: Inserir o número da nota | **input**: o usuário deve inserir o número da nota.     |
| Subtarefa 3.7: Inserir o valor | **input**: o usuário deve inserir o valor da compra.      |
| Tarefa 4: Clicar no botão "Registrar reclamação" |**feedback**: ser redirecionado para a página de registro de reclamação confirmado com sucesso.      |
| Tarefa 5: Confirmar que a mensagem de confirmação apareceu na tela | **feedback**: mensagem de confirmação da reclamação.      |

Fonte: [Gabriel Rosa](https://github.com/gabrielrosa09), 2023

</div>

### Desbloquear saldo

Nessa tarefa, o usuário possui como principal objetivo desbloquear o saldo de documentos fiscais que a Secretaria de Fazenda do Distrito Federal (SEFAZ-DF) bloqueou no Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#desbloquear-saldo). Na figura 2 é possível ver o diagrama HTA desta tarefa, e o mesmo HTA, só que em tabela, está visível na tabela 3.

<div align="center">

**Figura 2**: Diagrama HTA da tarefa Desbloquear Saldo.

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/HTA%20-%20Desbloquear%20saldo.drawio.png?raw=true" class="usecaseElement">

Fonte: [Gabriel Zaranza](https://github.com/GZaranza), 2023.

</div>

<br>

<div align="center">

**Tabela 3**: Tabela HTA da tarefa Desbloquear saldo.

| Objetivos/Operações       | Problemas e Recomendações                                                                                      |
|--------------------------|-------------------------------------------------------------------------------------------------------------|
| 0. Desbloquear saldo 1+2| **input:** mensagem informando as opções do usuário visualizar os documentos fiscais bloquedos e/ou registrar demanda no portal da SEFAZ-DF.<br> **feedback:** usuário redirecionado para a lista de documentos fiscais bloqueados e/ou portal da SEFAZ-DF.                                                                                                            |
| 1. Visualizar documentos bloqueados | **plano:** listar os documentos fiscais bloqueados                        |
| 1.1 Desbloquear créditos | **input:** apertar o botão "desbloqueio de créditos" <br> **feedback:** usuário redirecionado para o portal de demandas da SEFAZ-DF.                         |
| 1.1.1 Preencher formulário de solicitação | **input:** formulário de solicitação de demanda com tipo de pessoa, assunto, tipo de atendimento, nome, tipo de documento do usuário, e-mail, telefone e descrição da solicitação <br> **feedback:** nova solicitação é enviada para a SEFAZ-DF.                        |
| 2. Registrar demanda no Portal da SEFAZ-DF.    | **plano:** redirecionar o usuário para o portal de demandas da SEFAZ-DF.                                   |
| 2.1 Preencher formulário de solicitação       | **input:** formulário de solicitação de demanda com tipo de pessoa, assunto, tipo de atendimento, nome, tipo de documento do usuário, e-mail, telefone e descrição da solicitação. <br> **feedback:** nova solicitação é enviada para a SEFAZ-DF.  |

Fonte: [Gabriel Zaranza](https://github.com/GZaranza), 2023.

</div>

### Consultar um estabelecimento

Nessa tarefa, o usuário possui como principal objetivo consultar se determinado estabelecimento é ou não cadastrado no programa Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-estabelecimento). Na figura 3 é possível ver o diagrama HTA desta tarefa, e o mesmo HTA, só que em tabela, está visível na tabela 1.
<div align="center">

**Figura 3**: Diagrama HTA da tarefa Consultar um estabelecimento.

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2023.2-NotaLegal/4c0f0ffbff650f37967292a4c4f0437e77db093c/docs/imagens/hta-consultar-estabelecimento.drawio%20(1).png?raw=true" class="usecaseElement">

Fonte: [Izabella Alves](https://github.com/izabellaalves), 2023.

</div>

<br>

<div align="center">

**Tabela 4**: Tabela HTA da tarefa Consultar um estabelecimento.

| Objetivos/Operações       | Problemas e Recomendações                                                                                      |
|--------------------------|-------------------------------------------------------------------------------------------------------------|
| 0. Consultar um estabelecimento 1>2|                                                                                                             |
| 1. Pesquisar dados do estabelecimentos | **input:** tipo de estabelecimento e localidade. <br> **feedback:** uma lista com todos os estabelecimentos do tipo digitado localizados em determinado local.   **plano:** usar os dados dos estabelecimentos no site Nota Legal.                        |
| 2. Acessar área de consultar estabelecimentos  1>2    | **feedback:** usuário é redirecionado para a página de consultar estabelecimento.                                   |
| 2.1 Informar dados do estabelecimento        | **input:** dados do estabelecimento. <br> **plano:** ver os estabelecimentos. |
| 2.2 Verificar se o estabelecimento está na lista 1>2| **feedback:** usuário recebe uma lista tod estabelecimentos cadastrados que possuem dados parecidos. |
| 2.2.1. Selecionar o estabelecimento | **input:** usuário clica no estabelecimento desejado. <br> **feedback:** usuário redirecionado para a página do estabelecimento. |
| 2.2.2. Confirmar se é o estabelecimento correto | **plano:** verificar se os dados do estabelecimento clicado são iguais aos dados do estabelecimento buscado. |

Fonte: [Izabella Alves](https://github.com/izabellaalves), 2023.

</div>

### Visualizar Recibo Fiscal

...[Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#visualizar-recibo-fiscal)

<div align="center">

**Figura 4**: Diagrama HTA da tarefa Consultar um estabelecimento.

<img src="" class="usecaseElement">

Fonte: [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira), 2023.

</div>

<br>

<div align="center">

**Tabela 5**: Tabela HTA da tarefa Visualizar Recibo Fiscal.

| Objetivos/Operações      | Problemas e Recomendações                                |
|--------------------------|----------------------------------------------------------|
|                          |                                                          |

Fonte: [Lucas Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira), 2023.

</div>

### Consultar Reclamação

Nesta tarefa, o usuário tem como principal objetivo consultar as reclamações registradas contra um estabelecimento específico ([Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-reclama%C3%A7%C3%A3o)). O processo envolve verificar se há reclamações cadastradas para o estabelecimento desejado no sistema de reclamações do Nota Legal. Na Figura 5, você pode visualizar o diagrama HTA desta tarefa. Além disso, o mesmo diagrama HTA está disponível em formato de tabela, apresentado na Tabela 4.

<div align="center">

**Figura 5**: Diagrama HTA da tarefa Consultar Reclamação.

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/HTA%20-%20Consultar%20Reclama%C3%A7%C3%A3o.drawio.png?raw=true" class="usecaseElement">

Fonte: [Lucas Ribeiro](https://github.com/lucassouzs), 2023.

</div>

<br>

<div align="center">

**Tabela 6**: Tabela HTA da tarefa Consultar Reclamação.

| Objetivos/Operações       | Problemas e Recomendações                                                                                      |
|---------------------------|----------------------------------------------------------------------------------------------------------------|
|0. Consultar reclamação|-|
|1. Acessar o site ‘Nota Legal’|**feedback**: ser redirecionado para o site ‘Nota Legal’|
|2. Navegar até a página ‘Consulta de Reclamações’|**feedback**: ser redirecionado para a página de consulta de reclamações|
|3. Inserir informações de Consulta|-|
|3.1. Informar CNPJ|**input**: o usuário deve inserir o CNPJ da Empresa em que foi registrada a reclamação|
|3.2. Informar Período Inicial|**input**: o usuário deve inserir a data do período inicial em que foi registrada a reclamação|
|3.3. Informar Período Final|**input**: o usuário deve inserir a data do período final em que foi registrada a reclamação|
|3.4. Informar Número da Reclamação|**input**: o usuário deve inserir o número da reclamação|
|3.5. Informar Valor da Nota R$|**input**: o usuário deve inserir o valor total da nota fiscal da compra registrada|
|3.6. Informar Situação|**input**: o usuário deve informar a situação em que a reclamação se encontra|
|4. Clicar no botão ‘Consultar’|**feedback**: exibir uma lista com as reclamações de acordo com as informações indicadas nos campos|
|5. Analisar Reclamações Registradas|**plano**: verificar se as reclamações exibidas estão de acordo com as informalções inficadas nos campos|

Fonte: [Lucas Ribeiro](https://github.com/lucassouzs), 2023.

</div>

### Consultar extrato

Nesta tarefa, o usuário tem como principal objetivo consultar o extrato no sistema Nota Legal  é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#desbloquear-saldo). A Figura 6 ilustra o diagrama HTA desta tarefa, detalhando as etapas envolvidas. Além disso, o mesmo diagrama HTA é disponibilizado em formato de tabela na Tabela 5 para facilitar a compreensão.

<div align="center">

**Figura 6**: Diagrama HTA da tarefa Consultar Extrato.

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/htt_consultar_extrato.png?raw=true">

Fonte: [Lucas Víctor](https://github.com/Lucas13032003), 2023.

</div>

<div align="center">

**Tabela 7**: Tabela HTA da tarefa  Consultar Extrato.

| Objetivos/Operações       | Problemas e Recomendações                                                                                     |
|---------------------------|---------------------------------------------------------------------------------------------------------------|
|0. Consultar Extrato no Site Nota Legal 0>1   | - **Input**: Necessidade de consultar extrato.                                                 |
|1. Acessar o Site Nota Legal 1>2              |- **Input**: Ter acesso à página principal do Nota Legal.                                       |
|2. Navegar até a Aba "Extrato" 2>3            | - **Input**: Encontrar a aba "Extrato" no site.                                                |
|3. Aguardar o Carregamento das Informações do Extrato 3>4      | - **Input**: Tempo para o carregamento das informações. <br/> - **Feedback**:  Página de consulta de extrato  |
|4. Especificar o Período de Consulta de Extrato 1+2            | - **Input**: Definir o período desejado (mês/ano).                            |
|4.1 Localizar a opção de período na interface | - **Input**: Encontrar a opção de período no site.                                             |
|4.2 Inserir o período desejado (mês/ano)      | - **Input**: Inserir as datas desejadas.                                                       |
|5. Analisar as Transações e Créditos Acumulados no Extrato 1+ | - **Input**: Informações do extrato. <br/> - **Feedback**: Todos os saldos creditados, durante o periodo selecionado|
|5.1 Ler as informações exibidas no extrato    | - **Recomendação**: Melhorar a legibilidade e usabilidade das informações no extrato.          |

Fonte: [Lucas Víctor](https://github.com/Lucas13032003), 2023.

</div>

### Consultar resultado de sorteio

O objetivo principal da tarefa a seguir é consultar o resultado dos sorteios que são realizados semestralmente pelo programa Nota Legal do GDF. No documento de [cenários](https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/analise%20de%20requisitos/cenarios.md#consultar-resultado-de-sorteio) é ilustrado um exemplo dessa tarefa sendo realizada. A Figura 7 abaixo mostra o diagrama HTA para esse cenário e, em seguida, é apresentada a Tabela 8 equivalente a esse mesmo diagrama.

<div align="center">

**Figura 7**: Diagrama HTA da tarefa Consultar Resultado de Sorteio.

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/hta_consultar_resultado_sorteio.png?raw=true">

Fonte: [Zenilda Vieira](https://github.com/zenildavieira), 2023.

</div>

<div align="center">

**Tabela 8**: Tabela HTA da tarefa Consultar Resultado de Sorteio.

| Objetivos/Operações                | Problemas e Recomendações                                       |
| -----------------------------------| --------------------------------------------------------------- |
| 0. Consultar resultado de sorteio  | **ação**: clicar no ícone "sorteio" <br> **plano**: consultar o último sorteio *e depois* consultar o campo "Premiado"                           |
| 1. Consultar último sorteio        | **ação**: clicar no ícone do último sorteio na aba "Em Andamento" |
| 2. Consultar campo "Premiado"      | **feedback**: o campo "Premiado" pode conter "Sim" ou "Não" <br> **plano**: se o campo contiver "Sim", o usuário pode consultar bilhetes premiados *ou* indicar dados bancários <br> **recomendação**: se o campo contiver "Não", deixar desativadas as opções de consultar bilhetes e indicar dados bancários   |
| 2.1. Consultar bilhetes premiados  | **ação**: clicar em "Clique para consultar os bilhetes"           |
| 2.2. Indicar dados bancários | **ação**: clicar em "Indicar dados bancários para crédito do prêmio" <br> **plano**: selecionar o sorteio em questão *e depois* preencher os dados bancários |
| 2.2.1. Selecionar sorteio          | **input**: selecionar o sorteio que foi premiado                  |
| 2.2.2. Preencher dados bancários   | **input**: preencher os dados bancários                           |

Fonte: [Zenilda Vieira](https://github.com/zenildavieira), 2023.

</div>

## Bibliografia

> Bilheteria Digital. Análise Hierárquica de Tarefas. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/>. Acesso em: 08 de outubro 2023.
>
> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|08/10/2023|Criação do documento e adição do hta de consultar estabelecimentos|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|`1.1`|10/10/2023|Adição do hta de registro de reclamação|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|`1.2`|11/10/2023|Adição do hta de desbloqueio de saldo|[Gabriel Zaranza](https://github.com/GZaranza)|[Gabriel Rosa](https://github.com/gabrielrosa09)|
|`1.3`|12/10/2023|Adição do hta de consultar reclamação|[Lucas Ribeiro](https://github.com/lucassouzs)|[Gabriel Zaranza](https://github.com/GZaranza)|
|`1.4`|12/10/2023|Adição do hta de consultar resultado de sorteio|[Zenilda Vieira](https://github.com/zenildavieira)|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
|`1.5`|12/10/2023|Adição do hta de consultar extrato|[Lucas Víctor](https://github.com/Lucas13032003)|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|
