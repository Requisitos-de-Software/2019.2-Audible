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
