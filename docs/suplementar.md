# Especificação Suplementar

## Introdução

<p align="justify">&emsp;&emsp;Uma especificação suplementar lista os requisitos não-funcionais do sistema, junto com as outras técnicas de modelagem e elicitação utilizadas é possível capturar o conjunto completo de requisitos do sistema. Entre estes requisitos estão incluídos: os atributos de qualidade do sistema a ser criado, abrangendo requisitos de usabilidade, desempenho e suportabilidade. Além de outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade, restrições de design e legislação associada.</p>

### Finalidade

<p align="justify">&emsp;&emsp;Este documento tem por finalidade definir os requisitos não funcionais do aplicativo Audible que não foram explicitados nas outras técnicas de modelagem de requisitos. As Especificações Suplementares e o modelo de casos de uso,
juntos, capturam um conjunto completo de requisitos do sistema.</p>

### Escopo

<p align="justify">&emsp;&emsp;O Audible é um aplicativo de audio-livros na qual fornece acesso a uma variedade de livros para o usuário ter acesso. Possui ferramentas para novas dublagens e novos dubladores tanto quanto a adição de novos livros independentes.</p>

### Refêrencias

Audible: <a href="https://www.audible.com/">Site da Audible</a></br>
Requisitos de Software Habitica - Especificação Suplementar: <a href="https://requisitos-habitica.netlify.com/EspecificacaoSuplementar">Especificação Suplementar da Habitica</a></br>
Requisitos de Software GuiaBolso - Especificação Suplementar: <a href="https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/especificacao/">Especificação Suplementar do GuiaBolso</a>

## Funcionalidades

<p align="justify">&emsp;&emsp;Todas as funcionalidades do aplicativo Audible podem ser encontradas em toda a documentação já elaborada pelo grupo.</p>

## Usabilidade

#### Facilidade de Uso

* O usuário executa ações críticas em no máximo 5 clicks.
* O usuário poderá salvar títulos em uma lista de desejos de fácil acesso a qualquer momento no app.
* Áreas de descoberta de novos livros baseada nos gostos do usuário.
* O app é multiplataforma iOS (Apple iPhone, Apple Watch, iPad), Android, Sonos, Kindle e Dispositivos habilitados para Alexa.

#### Agilidade

* Possibilidade de navegar no aplicativo através de comandos de voz.

#### Pequena curva de aprendizado
* O aplicativo deve adicionar um tutorial de como ser usado para pessoas com mais dificuldade

#### Conhecimentos prévios
* <p align="justify">A aplicação exigirá que o usuário saiba usar sistemas móveis Android ou IOS, ou navegadores web como Chrome, Mozilla, Opera.</p>

#### Feedbacks

* O usuário deve ser capaz de avaliar o audiolivro de acordo com sua experiência.
* O usuário pode avaliar as avaliações.
* O usuário deve poder visualizar as avaliações de outros usuários antes de comprar o audiolivro.

## Confiabilidade

#### Disponibilidade
* <p align="justify">Os servidores do aplicativo devem mantê-lo disponível o maior tempo possível enquanto instalado no celular do usuário. Se houver indisponibildade por motivos de manutenção ou atualização, o usuário deve ser previamente avisado.</p>

#### Segurança mínima no armazenamento de dados

* <p align="justify">O armazenamento de dados dos usuário seguem os critérios mínimos da indústria para a segurança das informações de seus usuário.</p>

#### Suporte a falhas

* <p align="justify">No caso de falhas, o aplicativo deve dar segurança ao usuário de que a falha vai ser corrigida e não haverá consequências negativas aos dados sensíveis do usuário.</p>

## Desempenho

#### Rapidez de Resposta
<p align="justify">&emsp;&emsp;O sistema tem que ser o mais rápido possível quando resgatar as informações tanto do usuário, quanto do livro</p>

#### Acessos simultâneos

<p align="justify">&emsp;&emsp;A aplicação deve ter uma lógica de balanceamento de carga de requisições ao servidor, para ser capaz de atender acessos simultâneos de diferentes usuários, cada um em sua devida conta.</p>

#### Armazenamento

<p align="justify">&emsp;&emsp;O aplicativo precisa de 87,2MB(megabyte) de armazenamento em sistemas Android e 84,2MB em sistemas iOS.</p>

## Suportabilidade

<p align="justify">&emsp;&emsp;O sistema do Audible está disponível para as principais plataformas Web e Mobile do mercado. Funcionando nos sistemas operacionais mobile Android, nas versões 5.0 ou superior e IOS, nas versões 9.3 ou superior.</p>

## Restrições de Design

#### Suporte a Idiomas
* O sistema deve fornecer uma grande variedade de línguas.

#### Conteudo
* O sistema deve ter uma gama de audiolivros próprios.
* O aplicativo deve fornecer áudio de alta qualidade.

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

#### Sessão de Ajuda
* <p align="justify">O aplicatovo possui um botão chamado "Help". Ele possui um conjunto FAQ - Frequently Asked Questions -, ou seja, um conjunto de perguntas frequentes com suas soluções.</p>

## Interfaces

#### Interfaces de Usuário

* <p align="justify">O usuário utilizará as versões do aplicativo disponíveis nas lojas mobile ou navegadores web para visualizar e utilizar sua interface.</p>

#### Interface de Hardware

* <p align="justify">O hardware deve ser capaz de utilizar conexão com a internet para atender as necessidades de requisições de dados.</p>

#### Interface de Software

* <p align="justify">A interface do aplicativo é desenvolvida para atender as principais plataformas Web e Mobile do mercado.</p>

## Requisitos de Licenciamento

#### Termos de Uso

* <p align="justify">O aplicativo apresenta seus termos de uso para que o usuário concorde em utilizar o aplicativo e suas informações dentro dos limites apresentados.</p>

### Versionamento
| Data | Versão | Descrição | Autor |
| :--: | :---:  | --------- | :---: |
| 30/09/2019 | 1.0 | Especificação Suplementar | [Ian Rocha](https://github.com/IanPSRocha) |
