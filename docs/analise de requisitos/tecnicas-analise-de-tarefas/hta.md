## Análise Hierárquica de Tarefas
## Introdução

## Análise de Tarefas
### Consultar um estabelecimento
Nessa tarefa, o usuário possui como principal objetivo consultar se determinado estabelecimento é ou não cadastrado no programa 
Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](). Na figura 1 é possível
ver o diagrama HTA desta tarefa, e o mesmo HTA, só que em tabela, está visível na tabela 1.
<div align="center">

<img src="https://github.com/Interacao-Humano-Computador/2023.2-NotaLegal/blob/main/docs/imagens/hta-consultar-estabelecimento.drawio.png?raw=true" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Figura 1:</b> Diagrama HTA da tarefa Consultar um estabelecimento. Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a></b>, 2023.</p></font>

</div>

<br>
<div align="center">


| Objetivos/Operações       | Problemas e Recomendações                                                                                      |
|--------------------------|-------------------------------------------------------------------------------------------------------------|
| 0. Consultar um estabelecimento 1/2|                                                                                                             |
| 1. Pesquisar dados do estabelecimentos | **input:** tipo de estabelecimento e localidade. **feedback:** uma lista com todos os estabelecimentos do tipo digitado localizados em determinado local.   **plano:** usar os dados dos estabelecimentos no site Nota Legal.                        |
| 2. Acessar área de consultar estabelecimentos  1/2    | **feedback:** usuário é redirecionado para a página de consultar estabelecimento.                                   |
| 2.1 Informar dados do estabelecimento        | **input:** dados do estabelecimento. **plano:** ver os estabelecimentos. |
| 2.2 Verificar se o estabelecimento está na lista 1>2| **feedback:** usuário recebe uma lista tod estabelecimentos cadastrados que possuem dados parecidos. |
| 2.2.1. Selecionar o estabelecimento | **input:** usuário clica no estabelecimento desejado. **feedback:** usuário redirecionado para a página do estabelecimento. |
| 2.2.2. Confirmar se é o estabelecimento correto | **plano:** verificar se os dados do estabelecimento clicado são iguais aos dados do estabelecimento buscado. |

<font size="2"><p style="text-align: center"><b>Tabela 1:</b> Tabela HTA da tarefa Consultar um estabelecimento .Fonte: <a href="https://github.com/izabellaalves">Izabella Alves</a></b>, 2023.</p></font>
</div>

### Registrar uma reclamação
Nessa tarefa, o usuário possui como principal objetivo realizar uma reclamação no ambiente do
Nota Legal, é possível verificar um cenário que se baseia nessa tarefa na nossa página de [Cenários](/docs/analise%20de%20requisitos/cenarios.md). Na figura 1 é possível ver o diagrama HTA desta tarefa, e o mesmo HTA, só que em tabela, está visível na tabela 1.

<center>

![Figura 2 - HTA Reclamação](/docs/imagens/HTA%20-%20Registrar%20Reclamação.jpg)
**Figura 1**: Diagrama HTA da tarefa Consultar um estabelecimento. Fonte: [Gabriel Rosa](https://github.com/gabrielrosa09), 2023

</center>

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

**Tabela 2**: Tabela HTA da tarefa registro de reclamação. Fonte: [Gabriel Rosa](https://github.com/gabrielrosa09), 2023

</center>

## Bibliografia
> Bilheteria Digital. Análise Hierárquica de Tarefas. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/>. Acesso em: 08 de outubro 2023.
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|1.0|08/10/2023|Criação do documento e adição do hta de consultar estabelecimentos|[Izabella Alves](https://github.com/izabellaalves)|[Lucas Ribeiro](https://github.com/lucassouzs)|
|1.1|10/10/2023|Adição do hta de registro de reclamação|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
