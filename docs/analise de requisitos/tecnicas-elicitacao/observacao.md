# Observação

## Introdução

Existem diversas formar de se realizar a elicitação requisitos. Uma delas é, dentro de um estudo de campo, a observação.
Os estudos de campo podem ser utilizados em qualquer etapa do desenvolvimento, mas são mais úteis no início. Com esses estudo é possível:

- Encontrar novas ideias para funcionalidades e produtos.
- Questionar suposições sobre os usuários e como eles trabalham.
- Descobrir se as ferramentas e procedimentos correspondem ao modo como os usuários pensam.
- Compreender as metas dos usuários.
- Saber o que é necessário para treiná-los.
- Criar designs iniciais.
- Listar as tarefas que os usuários realizam.
- Definir a ordem de importância das tarefas.
- Coletar objetos ou itens que os usuários usam.
- Verificar se os usuários se encaixam nos perfis que inicialmente imaginamos.
- Criar personas baseadas na observação dos usuários reais.
- Coletar informações para melhorar a qualidade de uso, como fazer pesquisas de usabilidade.

A forma mais simples de realizar o estudo de campo é através da observação dos usuários utilizando o sistema. Ela pode ser de forma pura, sem a intervenção do observador ou pode ser uma observação guiada por tópicos de interesse.

Neste documento, apresentaremos o resultado da observação guiada de um usuário do site "Nota Legal", com a intenção de elicitar requisitos para o programa  "Nota Legal", tanto para o site, para a disciplina de Interação Humano-Computador, como para o aplicativo "Economia DF", para a disciplina de Requisitos de Software. O resultado da elicitação de requisitos feita através desta técnica pode ser vista abaixo na tabela 1.

## Metodologia

Nossa observação foi feita com uma usuária do sexo feminimo, 55 anos, nível de escolaridade Superior Completo, de média para baixa afinidade com tecnologia, baixa frequência de uso do sistema Nota Legal, acesso pelo computador e que tem como principal objetivo realizar indicações de concessão de créditos. No início da gravação, foi solicitada a permissão de gravação da usuária utilizando o site e durante a observação foram anotadas as funcionalidades utilizadas (como requisitos implementados), o nível de dificuldade que a usuária apresentou em cada uma delas e funcionalidades que a usuária sentiu falta (requisitos não implementados).
Não foi possível utilizar a função de indicação de concessão de créditos pois ela não estava disponível no momento da gravação (fica disponível somente no início de cada ano). Outro detalhe importante é que o vídeo gravado mostra o usuário já logado e termina antes dele deslogar. Portanto, as observações feitas sobre login e desconexão de login não constam na gravação. Os requisitos elicitados podem ser encontrados na tabela 1.

**RF (Requisitos Funcionais):** são funcionalidades específicas que o sistema deve oferecer em resposta a entradas do usuário.

**RNF (Requisitos Não Funcionais):** são aspectos não relacionados diretamente a funcionalidades, mas que afetam sua eficiência, usabilidade, segurança e outros atributos importantes.

**ID:** Cada requisito será identificado por um código composto da seguinte maneira: OXX, onde "XX" representa um número sequencial único.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos elicitados</p></font>
</div>

| ID    | Código | Descrição                                                    | Implementado | Nível de Dificuldade                |
| :---: | :----: | ------------------------------------------------------------ | :----------: | ----------------------------------- |
| O01   | RF     | Recuperação da senha                                         | Sim | médio - consegue realizar com dificuldade    |
| O02   | RF     | Visualização de créditos acumulados                          | Sim | fácil - consegue realizar                    |
| O03   | RF     | Visualização de saldo bloqueado                              | Sim | fácil - consegue realizar                    |
| O04   | RF     | Desbloquear saldo bloqueado                                  | Sim | difícil - não consegue realizar              |
| O05   | RF     | Indicação de concessão de créditos                           | Sim | não foi possível realizar (fora do prazo)    |
| O06   | RF     | Verificação de indicação de lançamentos                      | Sim | fácil - consegue realizar                    |
| O07   | RF     | Verificação de informações sobre sorteios                    | Sim | fácil - consegue realizar                    |
| O08   | RF     | Consulta do histórico de notas fiscais                       | Sim | fácil - consegue realizar                    |
| O09   | RF     | Consulta de informações sobre o percentual de concessão de crédito de acordo com o tipo de estabelecimento que emitiu a nota fiscal | Não | - |
| O10   | RF     | Consulta de estabelecimentos comerciais parceiros do programa Nota Legal. | Não | -                               |
| O11   | RF     | Forma de contato com a Secretaria de Estado de Economia no caso de algum problema específico do usuário | Não | - |
| O12   | RNF    | Garantir que ao fechar o aplicativo o usuário seja deslogado | Não | -                                            |

<div align="center">
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/zenildavieira">Zenilda Vieira</a>, 2023</p></font>
</div>

## Link da Gravação

No vídeo 1 encontra-se a gravação da reunião.

<div align="center">
<p style="text-align: center"><a href="https://youtu.be/FJ0vc5UsAz8" target="blanket"><b>Vídeo 1:</b> Requisitos - Reunião 01</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/FJ0vc5UsAz8" title="Apresentação 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/lucassouzs">Lucas Ribeiro</a>, 2023</p></font>
</div >

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

## Histórico de Versões

| Versão | Data       | Descrição                          | Autor                                                      | Revisor                                                   |
| :----: | ---------- | ---------------------------------- | :--------------------------------------------------------: | :-------------------------------------------------------: |
| `1.0`  | 28/09/2023 | Criação do documento               | [Zenilda Vieira](https://github.com/zenildavieira) | [Izabella Alves](https://github.com/izabellaalves)|
| `1.1`  | 10/10/2023 | Inclusão dos requisitos elicitados | [Zenilda Vieira](https://github.com/zenildavieira) | [Izabella Alves](https://github.com/izabellaalves)|
| `1.2`  | 12/10/2023 | Revisão |  [Izabella Alves](https://github.com/izabellaalves)| - (revisão não precisa de revisor) |
| `1.3`  | 13/10/2023 | Adição do vídeo da observação |  [Lucas Ribeiro](https://github.com/lucassouzs)| [Zenilda Vieira](https://github.com/zenildavieira) 
| `1.4`  | 13/10/2023 | Padronizando a legenda da tabela 1 e fazendo citação no texto |  [Gabriel Zaranza](https://github.com/GZaranza)| [Zenilda Vieira](https://github.com/zenildavieira) 
