# Cenários

## Introdução

### Essa técnica tem como objetivo demonstrar os requisitos para todos os envolvidos para ter uma maior feedback do que fazer.

## Metodologia

Utilizaremos como base esse modelo de tabela.

|Numero Cenário|Nome do cenário|
|---|---|
|**Versão**|1.0|
|**Autor**| Autor do cenário|
|**Metas**|Objetivo do ceário|
|**Contexto**|**O que?**<br>><br> **Onde?**<br>><br> **Quando?**<br>> <br> **Por que?**<br>><br>|
|**Atores**|Atores Envolvidos|
|**Recursos**|Recursos Envolvidos|
|**Restrições**| Descrição das restrições|
|**Exceções**| Descrição|
|**Episódios**|Detalhes do evento|

Onde tudo deve estar bem detalhado recorrendo a todos os recursos utilizados.

## Cenários
|C1|Pesquisa de livros na aba de pesquisa|
|---|---|
|**Versão**|1.0|
|**Autor**|André Goretti|
|**Metas**|Encontrar o livro desejado|
|**Contexto**|**O que?** <br> Achar o livro<br> **Onde?**<br>Em qualquer Página<br> **Quando?**<br>Antes de ouvir o livro <br> **Por que?**<br>Para conseguir Achar o livro desejado<br>|
|**Atores**|Audible <br> Usuário|
|**Recursos**|Internet <br> |
|**Restrições**|Ter internet |
|**Exceções**| Internet indisponível <br> livro não encontrado |
|**Episódios**|Usuário digita o que quer procurar na aba de pesquisa. <br> Usuário entra na sugestão sugeria <br> ou <br> entra em uma página de livros possíveis.|

<br>
<br>
<br>

|C2|Assinar Audible|
|---|---|
|**Versão**|1.0|
|**Autor**| André Goretti|
|**Metas**|Ter acesso ao serviço de assinatura completo|
|**Contexto**|**O que?**<br>>Assinar o serviço<br> **Onde?**<br>>Nos links ao entrar no site/app<br> **Quando?**<br>>Quando vc quer ter acesso <br> **Por que?**<br>>Para conseguir ouvir livros<br>|
|**Atores**|Usuários <br> Serviço da Amazon de compras|
|**Recursos**|O app <br> Internet <br> serviço amazon <br> Dinheiro|
|**Restrições**| Ter conta amazon|
|**Exceções**| Internet/serviço indisponível <br> Falta de dinheiro|
|**Episódios**|O usuário entra no app e decide contratar o serviço para poder usar livros de graça e ganhar bonificações.|

<br>
<br>
<br>

|C3|Dublar novo livro|
|---|---|
|**Versão**|1.0|
|**Autor**| André Goretti|
|**Metas**|Adicionar livros novos|
|**Contexto**|**O que?**<br>>contratar dubladores para novos livros<br> **Onde?**<br>>estúdio de dublagem <br> **Quando?**<br>>Quando um editora liberar novo livro <br> **Por que?**<br>>Para ter mais livros em oferta <br>|
|**Atores**|Serviços da Amazon <br> Dubladores |
|**Recursos**|Dinheiro para pagar o dublador <br> Lugar para gravar o livro <br> O Dublador|
|**Restrições**|Ter acesso ao livro pelas editoras|
|**Exceções**|Dublagem não ficar qualidade boa <br> |
|**Episódios**|A equipe do app Contrata dubladores para adicionar novos livros utilizando recursos da amazon.|

<br>
<br>
<br>

|C4|Cadastro de Usuário|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Cadastrar novo usuário no Audible|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>não ter cadastro <br> **Pós-Condição:**<br>>usuário cadastrado <br>|
|**Atores**|Usuário não cadastrado |
|**Recursos**|Internet, aplicativo, conta de e-mail|
|**Restrições**|O usúario ter conta na Amazon|
|**Exceções**|Internet cair <br> App dar crash <br> Senha inválida <br> E-mail inválido <br> Amazon fora do ar <br> Conta da Amazon inexistente|
|**Episódios**|Usuário não cadastrado abre o aplicativo <br> Usuário seleciona fazer o cadastro <br> Se o usuário já tiver conta na Amazon, então seleciona entrar <br> Senão usuário preenche e-mail, senha e confirmação da senha <br> Usuário confirma cadastro no e-mail e é redirecionado para a página principal do Audible|

<br>
<br>
<br>

|C5|Fazer login|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Utilizar todas as ferramentas exclusivas para usuários logados|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>Estar cadastrado, inserir o e-mail e a senha corretos <br> **Pós-Condição:**<br>>O usuário está logado <br>|
|**Atores**|Usuário cadastrado |
|**Recursos**|E-mail válido |
|**Restrições**|-|
|**Exceções**|Esquecer a senha <br> Esquecer o e-mail <br> Não ter cadastro |
|**Episódios**|Inicializar o Audible <br> Clicar em "get started" ou "sign in" <br> Inserir email e senha <br> Clicar em "continue"|

<br>
<br>
<br>

|C6|Sair do aplicativo Audible|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Sair de uma conta logada|
|**Contexto**|**Local:**<br>>Aba "more", na opção da engrenagem ("settings")<br> **Pré-Condição:**<br>>o usuário deverá estar logado <br> **Pós-Condição:**<br>>O usuário não estará mais logado <br>|
|**Atores**|Usuário logado |
|**Recursos**|Internet, aplicativo, conta de usuário |
|**Restrições**|-|
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Usuário entra na aba "more" <br> Usuário seleciona a opção "settings" <br> Usuário seleciona a opção "sign out" <br> Usuário confirma a ação <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C7|Experimentar o aplicativo|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C8|Ver audiolivros salvos na nuvem|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Visualizar audiolivros comprados que estão salvos na nuvem|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca<br> **Pós-Condição:**<br>> Exibição dos audiolivros salvos na nuvem <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados|
|**Restrições**|-|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica em "cloud" <br> Usuário visualiza audiolivros salvos na nuvem|

<br>
<br>
<br>

|C9|Ver audiolivros salvos no aparelho|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição dos audiolivros salvos no aparelho <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados e salvos no aparelho|
|**Restrições**|-|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta <br> Não ter baixado nenhum audiolivro|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica em "device" <br> Usuário visualiza audiolivros salvos no aparelho|

<br>
<br>
<br>

|C10|Ordenar por recentes|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Ordenar audiolivros da biblioteca por mais recentes|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição dos audiolivros ordenados por recentes <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados|
|**Restrições**|Ja estar sendo ordenado por recentes|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "sort by" <br> Usuário seleciona "recent" <br> Usuário visualiza audiolivros ordenados por recentes|

<br>
<br>
<br>

|C11|Ordenar por tamanho do audiolivro|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Ordenar audiolivros da biblioteca por tamanho do audiolivro|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição dos audiolivros ordenados por tamanho do audiolivro <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados|
|**Restrições**| Ja estar sendo ordenado por tamanho|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "sort by" <br> Usuário seleciona "length" <br> Usuário visualiza audiolivros ordenados por tamanho|

<br>
<br>
<br>

|C12|Ordenar por título|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Ordenar audiolivros da biblioteca por título|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição dos audiolivros ordenados por título <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados|
|**Restrições**|Ja estar sendo ordenado por título|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "sort by" <br> Usuário seleciona "title" <br> Usuário visualiza audiolivros ordenados por título|

<br>
<br>
<br>

|C13|Ordenar por autor|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Ordenar audiolivros da biblioteca por autor|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição dos audiolivros ordenados por autor <br>|
|**Atores**|Usuário logado com audiolivros na conta|
|**Recursos**|Internet, aplicativo, audiolivros comprados|
|**Restrições**|Ja estar sendo ordenado por autor|
|**Exceções**|Internet cair <br> App dar crash <br> Não possuir audiolivro na conta|
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "sort by" <br> Usuário seleciona "author" <br> Usuário visualiza audiolivros ordenados por autor|

<br>
<br>
<br>

|C14|Filtrar por todos os títulos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Filtrar audiolivros da biblioteca|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca <br> **Pós-Condição:**<br>> Exibição de todos os audiolivros que o usuário possui na biblioteca <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Ja estar sendo filtrado por todos os títulos |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "filter by" <br> Usuário seleciona "all titles" <br> Usuário visualiza todos audiolivros que o usuário possui na biblioteca|

<br>
<br>
<br>

|C15|Filtrar por trechos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Filtrar por trechos de audiolivros|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado <br> **Pós-Condição:**<br>> Exibição de trechos de audiolivros que estão disponiveis para download no Audible<br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Ja estar sendo filtrado por trechos |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "filter by" <br> Usuário seleciona "excerpts" <br> Usuário visualiza trechos de audiolivros que estão disponiveis para download no Audible|

<br>
<br>
<br>

|C16|Filtrar por não terminados|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Filtrar audiolivros da biblioteca por não terminados|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros na biblioteca<br> **Pós-Condição:**<br>> Exibição de todos os audiolivros não terminados que o usuário possui na biblioteca<br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Ja estar sendo filtrado por não terminados |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "filter by" <br> Usuário seleciona "unfinished" <br> Usuário visualiza todos os audiolivros não terminados que o usuário possui na biblioteca|

<br>
<br>
<br>

|C17|Deletar audiolivro|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Deletar audiolivro baixado|
|**Contexto**|**Local:**<br>>Aba "my library"<br> **Pré-Condição:**<br>>o usuário estar logado e possuir livros baixados na biblioteca<br> **Pós-Condição:**<br>> O deleta o audiolivro da sua biblioteca <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo, audiolivro na biblioteca |
|**Restrições**|- |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "my library" <br> Clica no ícone "delete" <br> Usuário seleciona o audiolivro que vai ser deletado <br> Usuário seleciona "delete from device" <br> O audiolivro é deletado da biblioteca|

<br>
<br>
<br>

|C18|Descobrir novos livros em destaque|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Descobrir os audiolivros que são destaque na loja|
|**Contexto**|**Local:**<br>>Aba "discover"<br> **Pré-Condição:**<br>>o usuário querer ver os livros que estão em destaque <br> **Pós-Condição:**<br>> O usuário vê todos os titulos em destaque na loja, por categorias<br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Ja estar sendo buscado por destaques |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "discover" <br> Seleciona "featured" <br> O usuário vê todos os titulos em destaque na loja, por categorias|

<br>
<br>
<br>

|C19|Descobrir novos livros por categorias|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Descobrir os audiolivros pelas suas categorias|
|**Contexto**|**Local:**<br>>Aba "discover"<br> **Pré-Condição:**<br>>o usuário querer ver os livros pelas suas categorias <br> **Pós-Condição:**<br>> O usuário vê todas as categorias existentes<br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Ja estar sendo buscado por categorias |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "discover" <br> Seleciona "categories" <br> O usuário vê todas as categorias existentes|

<br>
<br>
<br>

|C20|Descobrir livros originais audible|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Descobrir audiolivros originais do Audible|
|**Contexto**|**Local:**<br>>Aba "originals"<br> **Pré-Condição:**<br>>o usuário querer ver os audiolivros originais do Audible <br> **Pós-Condição:**<br>> O usuário vê os audiolivros originais do Audible<br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**|-|
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Seleciona a aba "originals" <br> O usuário vê todos audiolivros originais do Audible|

<br>
<br>
<br>

|C21|Ouvir amostra|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C22|Pausar amostra|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C23|Adicionar na lista de desejos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C24|Ler sumário|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C25|Ler reviews|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C26|Adiantar 30 segundos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C27|Voltar 30 segundos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C28|Mudar velocidade de reprodução|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C29|Escolher timer|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C30|Escolher volume|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C31|Emparelhar|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C32|Escolher modo direção|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C33|Escolher tema escuro|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C34|Escolher modo botão livre|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C35|Remover da lista de desejos|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C36|Visualizar tempo de escuta|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C37|Visualizar troféus conquistados|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C38|Visualizar nível de leitor|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C39|Visualizar títulos na biblioteca|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|

<br>
<br>
<br>

|C40|Atualizar biblioteca|
|---|---|
|**Versão**|1.0|
|**Autor**| Marco Antônio|
|**Metas**|Usar o aplicativo Audible como usuário visitante|
|**Contexto**|**Local:**<br>>Página inicial do app Audible (quando não logado)<br> **Pré-Condição:**<br>>o usuário querer experimentar o aplicativo sem logar <br> **Pós-Condição:**<br>> O usuário experimenta o aplicativo <br>|
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo |
|**Restrições**| Usuário já estar logado |
|**Exceções**|Internet cair <br> App dar crash |
|**Episódios**|Usuário abre o aplicativo <br> Clicar em "get started" ou "sign in" <br> Clicar em "try app" <br> Usuário visualiza a o app Audible como visitante|
