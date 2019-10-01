## 2 - Caso de Uso: Oferta de audiolivros

|         Sigla          | Definição       |
| :--------------------: | -------------------------------------------------------------------------------------------- |
|         Versão         |              1.0            |
|         Autor          |          Murilo Loiola      |
|       Descrição        |Audiolivros disponíveis na loja para serem comrprados|
|          Ator          |    Audible </br> Usuários   |
|   Pré-condições        |               Haver uma seção do aplicativo destinada a oferta de audiolivros (loja)               |
|    Fluxo principal     |      - Usuário acessa o Audible </br> - Usuário vai até a página da loja </br> - Usuário seleciona um audiolivro disponibilizado pela Audible</br> - Usuário efetua a compra                      |
| Fluxo alternativo      |   **FA2 - Lista de Desejos**</br>    - Usuário acessa o Audible </br> - Usuário vai até sua lista de desejos </br> - Usuário seleciona um audiolivro que ele tenha salvo em sua lista de desejos </br> - Usuário efetua a compra                     |
|   Fluxo de exceções    |  **FE2 - Sem conexão com a internet**</br> - O aplicativo exibe a mensagem "Sem Conexão com a Internet" </br> **FE3 - Nenhum método de compra cadastrado** </br> - O aplicativo redireciona o usuário para a página de cadastro de método de pagamento               |
|     Pós condições      |  O audiolivro comprado pelo usuário é adicionado a sua biblioteca e pode ser consumido                           |
|    Rastreabilidade     |    Baseado no Requisito Funcional 02 - O aplicativo deve ofertar audiolivros         |
