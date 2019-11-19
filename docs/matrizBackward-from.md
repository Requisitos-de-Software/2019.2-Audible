# Matriz Backward-from

## Versionamento

| Versão | Data | Modificação | Autor |
| :---: | :---: | :---: | :---: |
| 1.0 | 17/11/2019 | Adição do artefato. | [Thallys Braz](https://github.com/thallysbraz) |
| 1.1 | 18/11/2019 | Adição dos requisitos não funcionais e elos. | [Murilo Loiola](https://github.com/murilo-dan) |

## Introdução

<p align="justify">&emsp;&emsp;Este artefato busca ligar cada requisito levantado aos respectivos métodos de elicitação e modelagem utilizados na disciplina por meio da rastreabilidade Backward-from.</p>

## Legenda

| Sigla | Descrição |
| :---: | --------- |
| RF, RNF | Requisito Funcional, Requisito Não Funcional |
| EF, ENF | Elo Funcional, Elo Não Funcional |
| RP | RichPicture |
| C | Cenário |
| L | Léxico |
| UC | Caso de Uso |
| ES | Especificação Suplementar |
| IS | IStar |
| US | História de Usuário |
| NFR | NFR Framework |

## Matriz de Requisitos Funcionais

| ID  | Requisito                                                    | Origem                                                                            | Elo |
| ----- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | -------------- |
| RF01  | Possibilidade de navegar no aplicativo através de comandos de voz.      |      [Introspecção](https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/) | EF01        |
| RF02  | Adição de um tutorial de como usar o aplicativo.                        | [Introspecção](https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/) | EF02        |
| RF03  | Adicionar mais opções como artigos e revistas científicas.	            | [Introspecção](https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/) | EF03        |
| RF04  | A biblioteca/loja de audiolivros deve ser bem categorizada.	            | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF04        |
| RF05  | O aplicativo deve ofertar audiolivros.                                  | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF05        |
| RF06  | O usuário pode baixar os livros localmente para escutar mesmo off-line. | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF06        |
| RF07  | O usuário tem que ter acesso a uma barra de pesquisa para poder pesquisar palavras-chaves, autores, títulos, narrador, editora.                                                                | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF07        |
| RF08  | O aplicativo deve conter um ambiente para reprodução dos próprios audiolivros.	                                                                    | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF08        |
| RF09 | Deve haver variedade de livros disponíveis para o usuário.	              | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF09        |
| RF10 | O aplicativo deve ser capaz de salvar o progresso de leitura do usuário, para que ele consiga ouvir de onde parou.	                                                                          | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | EF10        |
| RF11 | Salvar biblioteca pessoal na nuvem.		                                  | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | EF11        |
| RF12 | Avaliação de livros disponível amplamente.		                            | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | EF12        |
| RF13 | Busca de livros por narrador.		                                        | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | EF13        |
| RF14 | Serviço de assinatura para acesso ilimitado de livros.		                | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | EF14        |

## Matriz de Requisitos Não-Funcionais

| ID  | Requisito                                                    | Origem                                                                            | Elo |
| ----- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | -------------- |
| RNF01  | Usuários de longa data recebem vantagens.	      |      [Introspecção](https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/) | ENF01        |
| RNF02  | O aplicativo deve fornecer áudio de alta qualidade.	                        | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/) | ENF02        |
| RNF03  | O usuário deve ser capaz de personalizar a reprodução do áudio livro (ex: acelerar/reduzir a velocidade de reprodução).		            | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/) | ENF03        |
| RNF04  | O usuário pode avaliar as avaliações.		            | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF04        |
| RNF05  | O sistema deve ter uma gama de audiolivros próprios.	                                  | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF05        |
| RNF06  | O usuário poderá salvar títulos em uma lista de desejos de fácil acesso a qualquer momento no app.	 | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF06        |
| RNF07  | O usuário tem acesso a uma prévia do livro antes de efetuar a compra.                                                               | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF07        |
| RNF08  | O sistema deve fornecer uma grande variedade de línguas.		                                                                    | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF08        |
| RNF09 | O app é multiplataforma iOS (Apple iPhone, Apple Watch, iPad), Android, Sonos, Kindle e Dispositivos habilitados para Alexa.		              | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF09        |
| RNF10 | O usuário deve ser capaz de avaliar o audiolivro de acordo com sua experiência.		                                                                          | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/)     | ENF10        |
| RNF11 | O usuário deve poder visualizar as avaliações de outros usuários antes de comprar o audiolivro.			                                  | [BrainStorm](https://requisitos-de-software.github.io/2019.2-Audible/brainstorm/) | ENF11        |
| RNF12 | Maior acessibilidade em toda a aplicação.			                            | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | ENF12        |
| RNF13 | Grande variedade de livros.	                                        | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | ENF13        |
| RNF14 | Áreas de descoberta de novos livros baseada nos gostos do usuário.			                | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | ENF14        |
| RNF15 | Sistema ter maneiras de incentivar a leitura ao usuário.			                | [Questionário](https://requisitos-de-software.github.io/2019.2-Audible/questionario/) | ENF15        |

## Elos Funcionais

**EF01**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/#persona-1">P1</a></br>
<a href="http://localhost:8000/suplementar/#agilidade">ES</a></br>
Elos:</br>Satisfação: ES **satisfaz** P1

**EF02**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/#persona-2">P2</a></br>
<a href="http://localhost:8000/suplementar/#pequena-curva-de-aprendizado">ES</a></br>
Elos:</br>Satisfação: ES **satisfaz** P2

**EF03**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/#persona-3">P3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#6-caso-de-uso-variedade-de-livros">UC6</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#audiolivro">L1</a></br>
Elos:</br>Satisfação: C3 **satisfaz** P3; C3 **satisfaz** UC6

**EF04**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C10</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C11</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C12</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C13</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C14</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C15</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C16</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#biblioteca">L2</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us04-criar-colecoes-proprias-dos-audiolivros-adquiridos">US4</a></br>
Elos:</br>Recurso: C's são **recursos** de L2;

**EF05**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/rich_picture/#rp4-loja">RP04</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C1</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#loja">L7</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#2-caso-de-uso-comprar-audiolivros">UC2</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us014-ter-acesso-a-uma-loja-bem-categorizada">US14</a></br>
Elos:</br>Satisfação: US14 **satisfaz** C1;
</br>Representação: RP4 **representa** L1; RP4 **representa** C1;
</br>Alocação: UC2 está **alocada** em RP4;

**EF06**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C17</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#3-caso-de-uso-baixar-audiolivros">UC3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us07-salvar-meus-audiolivros-localmente">US7</a></br>
Elos:</br>Representação: UC3 **representa** US7;
</br>Satisfação: UC3 **satisfaz** C17;

**EF07**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C1</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#barra-de-busca">L3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#4-caso-de-uso-barra-de-pesquisa">UC04</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/istar/#busca">IS2</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us03-fazer-uma-busca-na-biblioteca-de-audiolivros">US03</a></br>
Elos:</br>Satisfação: UC4 **satisfaz** C1;
</br>Representação: UC4 **representa** L3;
</br>Agregação: IS2 é **composto** por UC4;

**EF08**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C28</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#player">L10</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#5-caso-de-uso-ambiente-de-reproducao">UC5</a></br>
Elos:</br>Representação: UC5 **representa** L10;
</br>Recurso: C28 é **recurso** de UC5;

**EF09**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/introspeccao/#persona-3">P3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#6-caso-de-uso-variedade-de-livros">UC6</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C3</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#audiolivro">L1</a></br>
Elos:</br>Satisfação: C3 **satisfaz** P3; C3 **satisfaz** UC6

**EF10**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#progresso-de-leitura">L4</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#8-uso-de-caso-salvar-o-progresso-do-livro">UC8</a></br>
Elos:</br>Representação: UC8 **representa** L4

**EF11**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C8</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us08-fazer-upload-da-minha-biblioteca-pessoal-para-a-nuvem">US8</a></br>
Elos:</br>Satisfação: US8 **satisfaz** C8

**EF12**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/rich_picture/#rp6-avaliacao">RP6</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#avaliar">L5</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#9-uso-de-caso-avaliacao-de-livros">UC9</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/istar/#avaliacao">IS5</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us011-ter-acesso-a-avaliacoes-de-audiolivros">US11</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us012-avaliar-titulos">US12</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us013-avaliar-avaliacoes">US13</a></br>
Elos:</br>Representação: RP6 **representa** L5; RP6 **representa** US's; UC9 **representa** L5
</br>Recurso: US's são **recursos** de IS5
</br>Alocação: UC9 está **alocado** em RP6

**EF13**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#narrador">L9</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us019-buscar-titulos-por-narrador">US19</a></br>
Elos: Sem elos estabelecidos

**EF14**</br>
Categoria: Desenvolvimento</br>
Elementos Rastreáveis:</br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/rich_picture/#rp4-loja">RP4</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/cenarios/">C2</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/lexicos/#assinatura">L6</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/casos_de_uso/#7-caso-de-uso-assinar-o-audible">UC7</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/istar/#assinatura">IS1</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us09-realizar-assinatura-do-servico-premium">US9</a></br>
<a href="https://requisitos-de-software.github.io/2019.2-Audible/backlog/#us10-obter-catalogo-exclusivo-de-audiolivros-para-assinantes">US10</a></br>
Elos:</br>Representação: UC7 **representa** L6; UC7 **representa** US's
</br>Agregação: UC7 **compõem** IS1
</br>Satisfação: UC7 **satisfaz** C2
