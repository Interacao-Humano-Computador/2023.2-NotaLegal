# Requisitos Elicitados

## Introdução
O site "Nota Legal" é um sistema que visa oferecer aos cidadãos uma plataforma conveniente e informativa para lidar com questões relacionadas à economia local e à gestão de seus créditos acumulados por meio do programa "Nota Legal". Para garantir que o site atenda às necessidades e expectativas dos usuários, foram definidos uma série de requisitos funcionais (RF) e requisitos não funcionais (RNF) durante o processo de elicitação de requisitos. Esses requisitos desempenham um papel fundamental na definição do escopo e na orientação do desenvolvimento do site. Os requisitos elicitados vieram das técnidas de elicitação: [Introspecção](#), [Brainstorming](#) e [Observação](#), e foram reunidos na tabela 2.

## Metodologia
A metodologia adotada envolveu a consolidação de todos os requisitos funcionais (RF) e requisitos não funcionais (RNF) obtidos por meio de diversas técnicas de elicitação em uma tabela estruturada (Tabela 2). Nesta tabela, cada requisito é identificado por um ID exclusivo, categorizado como RF ou RNF para indicar seu tipo e acompanhado de um status de implementação. Além disso, a tabela também rastreia a origem de cada requisito, destacando se ele foi obtido por meio de técnicas como a [Introspecção](#), [Brainstorming](#) e [Observação](#).

Essa abordagem de registro em tabela oferece uma visão organizada e estruturada dos requisitos do projeto, permitindo uma fácil referência e acompanhamento ao longo do ciclo de desenvolvimento. Ela promove a rastreabilidade, o que significa que é possível rastrear a origem de cada requisito, garantindo que todas as necessidades dos stakeholders sejam devidamente consideradas e atendidas no projeto. A legenda para cada sigla esta disponível na tabela 1.



| Tipo | Descrição                           |
|------|-------------------------------------|
| RF   | Requisito Funcional                 |
| RNF  | Requisito Não-Funcional             |
| IS   | Requisito elicitado pela Introspecção |
| BS   | Requisito elicitado pelo Brainstorming |
| O   | Requisito elicitado pelo Observação |

<div align=center>

<div align=center><p><b>Tabela 1:</b> Legenda para a tabela 2 de requisitos do Nota Legal. Fonte:</b><a href="https://github.com/gabrielrosa09"> Gabriel Rosa</a>, 2023.</p></div>

</div>


<br>


| ID   | Código | Descrição                                                                                      | Implementado | Rastreabilidade |
|------|--------|------------------------------------------------------------------------------------------------|--------------| ------ |
| INT01| RF     | O site deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |Sim| IS, BS |
| INT02| RF     | Deve ser possível acessar os dados diretamente da secretaria de estado de economia do distrito federal | Sim | IS |
| INT03| RF     | O site deve permitir a recuperação de senha por meio de um processo seguro e validado. | Sim | IS, , O |
| INT04| RF     | Os usuários devem poder acessar e visualizar informações sobre créditos acumulados. | Sim | IS, O |
| INT05| RF     | O site deve possibilitar a consulta do histórico de notas fiscais associadas à conta do usuário. | Sim | IS, BS, O |
| INT06| RF     | Permitir que os usuários consultem estabelecimentos comerciais parceiros do programa Nota Legal. | Sim | IS, O |
| INT07| RF     | Os usuários devem poder resgatar os créditos acumulados de forma clara e fácil. | Sim | IS, O |
| INT08| RF     | Deve ser possível visualizar promoções e descontos oferecidos em estabelecimentos participantes. | Sim | IS |
| INT09| RF     | O site deve ter uma interface intuitiva, fácil de navegar e que proporcione uma boa experiência ao usuário. | Sim | IS, BS,  |
| INT10| RNF     | A interface deve ser responsiva para o navegador de dispositivos móveis.	 | Sim | IS, BS |
| INT11| RF     | Deve ser disponibilizada uma forma de entrar em contato com a Secretária de Estado de Economia no caso de algum problema específico do usuário | Sim | IS, O |
| INT12| RNF    | Garantir a segurança das informações dos usuários durante a transmissão e armazenamento de dados. | Sim | IS, BS |
| INT13| RNF    | Assegurar conformidade com regulamentações de proteção de dados vigentes no Brasil. | Sim | IS, BS |
| INT14| RNF    | Garantir tempo máximo de resposta das páginas de 10 segundos.	 | Não | IS, BS |
| INT15| RNF    | A inatividade do site só deve ocorrer uma vez na semana, durante o final de semana e em período noturno.	 | Não | IS, BS |
| INT16| RNF    | Garantir que o usuário consiga acessar a página procurada em até 3 cliques.	 | Sim | IS, BS |
| INT17| RNF    | O site deve funcionar tanto no ambiente Windows, quanto no Linux e no IOS.	 | Sim | IS |
| INT18| RNF    | O site deve funcionar no Chrome, no Safari, no Edge e no Mozilla.	 | Sim | IS, BS |
| INT19| RNF    | Garantir que ao fechar o site o usuário seja deslogado | Não | BS, O  |
| INT20| RF  | Garantir que o usuário consiga realizar login com a conta do GOV | Sim | BS |
| INT21| RF  | Possuir informações sobre desbloqueio de valores bloqueados | Não | BS, O |
| INT22| RF  | Possuir informações sobre o percentual de concessão de cŕedito de acordo com o tipo de estabelecimento que emitiu a nota fiscal | Não | BS  |
| INT23| RF  | Possibilitar que o usuário aumente a fonte | Não | BS |  
| INT24| RF  | Possuir um modo escuro e um modo claro | Não | BS |
| INT25| RF  | Salvar os dados bancários da conta usada na indicação | Não | BS |
| INT26| RF  | Deve ser possível encontrar o recibo da indicação | Sim | BS, O  |
| INT27| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 7 caracteres ao cadastrar a placa de um veículo | Sim | BS, O |
| INT28| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 11 números ao cadastrar o renavan de um veículo | Sim | BS, O |
|INT29| RNF  | O usuário não deve conseguir colocar uma quantidade diferente de 8 números ao cadastrar a inscrição de um imóvel | Sim | BS, O |
|INT30| RF  | O usuário deve conseguir emitir a segunda via da dívida ativa | Sim | BS, O  |
<div align=center>
<div align=center><p><b>Tabela 2:</b> Requisitos elicitados do site Nota Legal. Fonte:</b><a href="https://github.com/gabrielrosa09"> Gabriel Rosa</a> e <a href="https://github.com/izabellaalves"> Izabella Alves</a>, 2023.</p></div>

</div>

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|1.0|29/09/2023|Criação do documento e adição de tabela|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|
|1.1|29/09/2023|Adição da introdução, metodologia e inserindo rastreabilidade da tabela|[Gabriel Rosa](https://github.com/gabrielrosa09)|[Izabella Alves](https://github.com/izabellaalves)|
|2.0|10/10/2023|Adaptação do documento pro site Nota Legal|[Izabella Alves](https://github.com/izabellaalves)|[Gabriel Zaranza](https://github.com/gzaranza)|

