# Brainstorming
## Introdução

O brainstorming é uma técnica amplamente utilizada na elicitação de requisitos no processo de desenvolvimento de software. Essa abordagem colaborativa e criativa envolve a reunião de diversas partes interessadas, como clientes, usuários e membros da equipe de desenvolvimento, em uma sessão de brainstorming. Durante essa reunião, os participantes são encorajados a gerar ideias livremente, sem críticas ou julgamentos, com o objetivo de identificar requisitos, funcionalidades e objetivos do projeto. O brainstorming promove a criatividade, a geração de soluções inovadoras e a participação ativa de todos os envolvidos, o que ajuda a garantir que os requisitos do projeto sejam abrangentes e bem compreendidos desde o início do processo de desenvolvimento.

## Metodologia
O brainstorming foi realizado no dia 28/09/2023 e contou com a participação de todos os integrantes da equipe, a princípio, o moderador [Lucas Victor](https://github.com/Lucas13032003) fez uma breve introdução sobre o programa Nota Legal e explicou como seria realizada a sessão. Foi preparado um quadro de post-it's, na plataforma [Canva](canva.com) [1], para cada uma das seis perguntas que guiariam o brainstorming. O mediador então fazia a introdução da pergunta e pedia para os participantes colarem post-it's com ideias sobre aquele assunto e ao final a equipe falava um pouco sobre as ideias levantadas.

## Desenvolvimento

### Pergunta 1: Como podemos melhorar o Notal Legal?
> - Desing
> - Tempo de resposta
> - Acessibilidade
> - Atendimento virtual
> - Informações mais claras sobre bônus das notas
> - Melhorar a forma de trocar a senha

### Pergunta 2: Quais são as funcionalidades essenciais que o site Nota Legal deve possuir?
> - Se cadastrar com a base de dados do governo
> - Consultar o saldo que possui no Nota Legal
> - Consultar extrato das notas fiscais
> - Fazer indicação
> - Consultar informações do sorteio
> - Login

### Pergunta 3: Quais são os requisitos não funcionais importantes para o site?
> - Tempo de resposta do app menor que 5 segundos
> - Garantir a segurança do usuário
> - Portabilidade para o celular
> - Deslogar com segurança
> - Logar em menos de 10 segundos


### Pergunta 4: O site Nota Legal precisar integrar-se a algum outro sistema ou plataforma?
> - Todos responderam "sim"

### Pergunta 5: Quas são as medidas de segurança e privacidade que devem ser implementadas no site Nota Legal?
> - Login atraves do gov.br
> - Atenticação em 2 fatores
> - Buscar dados na base da receita federal
> - Exigir senha com letras, números e caracteres especias
> - Deslogar automaticamente quando o usuário fechar o navegador
> - Estar de acordo com o padrão LGPD
> - Privacidade dos dados das notas fiscais

### Pergunta 6: Como deve ser a interface do site Nota Legal em termos de design, usabilidade e experiência do usuário?
> - De fácil entendimento
> - Responsividade
> - Minimalista
> - Ícones auto-explicativos
> - Se adaptar a linguagem do usuário
> - Seguir um padrão

Na elicitação de requisitos para o site "Nota Legal", que pode ser visto na tabela 1, utilizamos códigos para classificar e organizar os requisitos de maneira clara e estruturada. Dois desses códigos frequentemente usados são RF (Requisitos Funcionais) e RNF (Requisitos Não Funcionais). Além disso, cada requisito elicitado terá um ID.

**RF (Requisitos Funcionais):** Representam funcionalidades específicas que o aplicativo deve oferecer, descrevendo as ações que o sistema deve executar em resposta a entradas.

**RNF (Requisitos Não Funcionais):** Englobam aspectos que não estão diretamente relacionados às funcionalidades específicas do aplicativo, mas afetam sua eficiência, usabilidade, segurança e outros atributos.

**ID:** Cada requisito será identificado por um ID composto da seguinte forma: INTXX (onde XX é um número sequencial). Por exemplo, o primeiro requisito funcional seria INT01 e assim por diante.


| ID   | Código | Descrição                                                                                      | Implementado |
|------|--------|------------------------------------------------------------------------------------------------|--------------|
| BS01| RF     | O site deve permitir que os usuários se autentiquem de forma segura, usando credenciais únicas, como CPF e senha. |   Sim        |
| BS02|    RF  | O usuário deve ser capaz de logar com as credências do gov.br |   Sim        |
| BS03|    RF| O usuário deve conseguir visualizar o saldo que possui no Nota Legal | Sim          |
| BS04|    RF| O usuário deve conseguir consultar extrato das notas fiscais |     Sim     |
| BS05|    RF  | O usuário deve conseguir indicar onde quer utilizar o seu saldo (IPTU,IPVA ou PIX)  |       Sim   |
| BS06|      RF| O usuário deve conseguir se inscrever nos sorteios do Nota Legal |  Sim         |
| BS07|      RF| O usupario deve conseguir vizualizar os sorteios |     Sim      |
| BS08|   RF   | O usuário deve conseguir se logar no site |  Sim         |
| BS09|   RF   | O login deve possuir autenticação em dois fatores |  Não         |
| BS10|    RNF  | O site deve buscar informações na base da receita federal |    Sim       |
| BS11|  RNF    | O login deve ser feito em menos de 10 segundos |       Sim    |
| BS12|   RNF   | O site deve funcionar no Chrome, no Safari, no Edge e no Mozilla.	 |   Sim        |
| BS13|   RNF   | O aplicativos deve exigir que a senha do usuário possua obrigatoriamente letras, números e caracteres especiais |   Não        |
| BS14|    RNF  | O site deve deslogar a conta do usuário quando for fechado |     Não      |
| BS15|    RF  | O usuário deve conseguir alterar a senha da sua conta |     Não      |
| BS16|    RNF  | O site deve possuir ferramentas de acessibilidade (Alto contraste, libras, aumentar a fonte) |     Não      |

<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 1 - Requisitos elicitados. Fonte:</b> <a href="https://github.com/GZaranza">Gabriel Zaranza</a>, 2023.</b></p></font>

</div>


## Link da Gravação

[Requisitos - Brainstoming](https://youtu.be/wPMoeSRbOjA)

## Referências Bibliográficas

> [1] Canva. Disponível em: <https://www.canva.com/>. Acesso em: 28/09/2023.

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 30/09/2023.


## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|:-----:|:-------:|
|`1.0`|29/09/2023|Criação do documento|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Victor Ferreira de Araújo](https://github.com/Lucas13032003)|
|`1.1`|01/10/2023|Adição de metodologia e perguntas|[Gabriel Zaranza](https://github.com/GZaranza)|[Lucas Victor Ferreira de Araújo](https://github.com/Lucas13032003)|
|`1.2`| 02/10/2023 | Adiçao do link da gravação | [Lucas Ribeiro de Souza](https://github.com/lucassouzs) | [Gabriel da Silva Rosa](https://github.com/gabrielrosa09) |
|`2.0`| 10/10/2023 | Alterações nos requisitos e na metodologia | [Izabella Alves](https://github.com/izabellaalves) | [Gabriel da Silva Rosa](https://github.com/gabrielrosa09) |
