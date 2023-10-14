# Instrospecção
## Introdução
A introspecção, como técnica de elicitação de requisitos, é um processo profundo e enriquecedor que visa compreender as propriedades cruciais para o sucesso de um sistema. Requer que o Engenheiro de Requisitos mergulhe em uma análise reflexiva, imaginando-se executando tarefas específicas com os recursos e equipamentos disponíveis, para conceber as funcionalidades e características desejadas do sistema.

Neste documento, apresentaremos os resultados da aplicação da técnica de introspecção para a elicitação de requisitos do site "Nota Legal". Este site visa proporcionar aos usuários o acesso aos serviços oferecidos pelo programa Nota Legal por meio de uma aplicação web.
## Metodologia

Como visto na introdução, a metodologia da Instrospecção consiste no Engenheiro de Requisitos se imaginar executando uma tarefa, e assim, elicitando os requisitos necessários para
que o site seja um sucesso e atenda as necessidades da tarefa. Sendo assim, a situação hipotética está descrita abaixo e os resultados estão na seção "Desenvolvimento".

- #### Situação hipotética
Eu sou uma cidadã que deseja acessar os serviços do programa Nota Legal, como verificar créditos acumulados e histórico de notas fiscais, resolvo fazer isso através de meu computador, e para isso, acesso o site "Nota Legal".

## Desenvolvimento
Na elicitação de requisitos para o site "Nota Legal", que pode ser vista na tabela 1, utilizamos códigos para classificar e organizar os requisitos de maneira clara e estruturada. Dois desses códigos frequentemente usados são RF (Requisitos Funcionais) e RNF (Requisitos Não Funcionais). Além disso, cada requisito elicitado terá um ID.

**RF (Requisitos Funcionais):** Representam funcionalidades específicas que o aplicativo deve oferecer, descrevendo as ações que o sistema deve executar em resposta a entradas.

**RNF (Requisitos Não Funcionais):** Englobam aspectos que não estão diretamente relacionados às funcionalidades específicas do aplicativo, mas afetam sua eficiência, usabilidade, segurança e outros atributos.

**ID:** Cada requisito será identificado por um ID composto da seguinte forma: INTXX (onde XX é um número sequencial). Por exemplo, o primeiro requisito funcional seria INT01 e assim por diante.


| ID   | Código | Descrição                                                                                      | Implementado |
|------|--------|------------------------------------------------------------------------------------------------|--------------|
| INT01| RF     | O site deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |   Sim        |
| INT02| RF     | Deve ser possível acessar os dados diretamente da secretaria de estado de economia do distrito federal | Sim         |
| INT03| RF     | O site deve permitir a recuperação de senha por meio de um processo seguro e validado.  |     Sim      |
| INT04| RF     | Os usuários devem poder acessar e visualizar informações sobre créditos acumulados.           |      Não     |
| INT05| RF     | O site deve possibilitar a consulta do histórico de notas fiscais associadas à conta do usuário. |    Sim      |
| INT06| RF     | Permitir que os usuários consultem estabelecimentos comerciais parceiros do programa Nota Legal. |     Sim      |
| INT07| RF     | Os usuários devem poder resgatar os créditos acumulados de forma clara e fácil.               |    Sim       |
| INT08| RF     | Deve ser possível visualizar promoções e descontos oferecidos em estabelecimentos participantes. |      Sim     |
| INT09| RF     | O site deve ter uma interface intuitiva, fácil de navegar e que proporcione uma boa experiência ao usuário. |    Sim       |
| INT10| RNF    | A interface deve ser responsiva para o navegador de dispositivos móveis.           |     Sim      |
| INT11| RF    | Deve ser disponibilizada uma forma de entrar em contato com a Secretária de Estado de Economia no caso de algum problema específico do usuário                 |  Sim        |
| INT12| RNF    | Garantir a segurança das informações dos usuários durante a transmissão e armazenamento de dados. |     Sim      |
| INT13| RNF    | Assegurar conformidade com regulamentações de proteção de dados vigentes no Brasil.          |     Sim      |
| INT14| RNF    | Garantir tempo máximo de resposta das páginas de 10 segundos.   |    Não      |
| INT15| RNF    | A inatividade do site só deve ocorrer uma vez na semana, durante o final de semana e em período noturno. |     Não      |
| INT16| RNF    | Garantir que o usuário consiga acessar a página procurada em até 3 cliques. |      Sim     |
| INT17| RNF    | O site deve funcionar tanto no ambiente Windows, quanto no Linux e no IOS. |      Sim     |
| INT18| RNF    | O site deve funcionar no Chrome, no Safari, no Edge e no Mozilla.                   |     Sim      |

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1 - Requisitos elicitados. Fonte:</b> <a href="https://github.com/izabellaalves">Izabella Alves</a>, 2023.</b> e </b> <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a></p></font>

</div>


## Bibliografia
> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 23/09/2023.
## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|:-----:|:-------:|
|`1.0`|23/09/2023|Criação do documento|[Izabella Alves Pereira](https://github.com/izabellaalves)|[Lucas Victor Ferreira de Araújo](https://github.com/Lucas13032003)|
|`1.1`|23/09/2023|Preenchimento da tabela com a adição dos resultados da Introspecção|[Lucas de Oliveira](https://github.com/LucasOliveiraDiasMarquesFerreira)|[Izabella Alves Pereira](https://github.com/izabellaalves)|
|`1.2`|10/10/2023|Alterações nos requisitos|[Izabella Alves Pereira](https://github.com/izabellaalves)|[Lucas Victor Ferreira de Araújo](https://github.com/Lucas13032003)|
