# Product Backlog

## Introdução

O backlog do produto é um artefato essencial no contexto da modelagem ágil, especialmente no framework Scrum. Ele consiste em uma lista que reúne todas as funcionalidades, melhorias, correções e outros itens necessários para o desenvolvimento ou evolução do produto.

Ao contrário de uma especificação inicial fechada, o backlog do produto é um documento vivo que evolui constantemente, em que reflete as mudanças nos requisitos e permite ajustes baseados em feedback dos usuários, mudanças nos objetivos do negócio ou descobertas durante o desenvolvimento. Cada item do backlog, muitas vezes representado por histórias de usuário, descreve de forma simples e clara o que deve ser feito para agregar valor ao produto (SCHWABER; SUTHERLAND, 2020).

## Metodologia

A metodologia utilizada para a elaboração do backlog segue uma estrutura hierárquica, e composta pelos Temas, em que fornece uma visão geral do que precisa ser feito, os Épicos, que fornece uma direção mais detalhada do que deve ser desenvolvido, e as Histórias de Usuário, que representam o nível mais detalhado do backlog. Inicialmente, os **Temas** foram definidos com base nos [requisitos levantados](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline), no [mapa mental](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/MapaMental) e no [rich picture](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/ArtefatoGeneralista/RichPicture), abrangendo áreas e objetivos do sistema. Esses temas são divididos em **Épicos**, que representam grupos de funcionalidades relacionadas e mais detalhadas. Por fim, cada épico é subdividido em **Histórias de Usuário**, que descrevem de maneira específica as funcionalidades ou necessidades que o produto deve atender.

Essa abordagem permite uma visualização estruturada do backlog, facilitando a priorização e o refinamento contínuo do projeto, garantindo que os itens estejam alinhados aos objetivos do produto e às necessidades dos usuários (PICHLER, 2017). 

<center>

## Temas

|  ID  | Título                 | Descrição                                        |
| ---- | ---------------------- | ------------------------------------------------ |
| <a id="t01">T01</a> | Cadastro e Autenticação | Abrange as funcionalidades de registro, acesso e gerenciamento de dados pessoais, garantindo que os usuários possam criar e acessar suas contas de forma segura e intuitiva. |
| <a id="t02">T02</a> | Exploração do Catálogo | Trata das funcionalidades que permitem aos usuários visualizar, buscar, explorar e marcar itens e lojas como favoritos. Facilita a descoberta e seleção de produtos no aplicativo. |
| <a id="t03">T03</a> | Pedido | Inclui funcionalidades para gerenciar compras, personalizar pedidos, confirmar compras, visualizar o histórico de pedidos e acompanhar o status de pedidos feitos. |
| <a id="t04">T04</a> | Pagamento | Abrange funcionalidades relacionadas às formas de pagamento, como selecionar métodos, salvar dados bancários e garantir a segurança dos dados financeiros. |
| <a id="t05">T05</a> | Entrega | Foca no processo de entrega dos pedidos, incluindo rastreamento em tempo real, opção de retirada no local, e escolha entre entregadores próprios ou parceiros para a entrega. |
| <a id="t06">T06</a> | Avaliação | Envolve funcionalidades para que usuários e lojas possam avaliar entregas e produtos, fornecendo feedback para melhorar o serviço e a experiência geral. |
| <a id="t07">T07</a> | Gerenciamento da Loja | Contempla as necessidades das lojas, permitindo o gerenciamento de cardápios, atualização de itens e recepção de pedidos. |
| <a id="t08">T08</a> | Entregador | Abrange funcionalidades específicas para os entregadores, incluindo a aceitação de pedidos, localização de restaurantes e clientes |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade).
</center>

<center>

## Épicos

| Tema | ID | Título | Como um(a) | Eu quero | Para que eu possa |
| ---- |----|--------|------------|----------|-------------------|
| [T01](#t01) | <a id="e01">E01</a> | Registro | Usuário | Registrar o meu perfil | Acessar o aplicativo com minha conta única |
| [T01](#t01) | <a id="e02">E02</a> | Acesso | Usuário | Acessar minha conta utilizando meu email e senha | Ter acesso às funcionalidades do aplicativo |
| [T01](#t01) | <a id="e03">E03</a> | Recuperação de Senha | Usuário | Recuperar minha senha caso a esqueça | Garantir o acesso à minha conta |
| [T01](#t01) | <a id="e04">E04</a> | Gerenciar Dados do Perfil | Usuário | Atualizar meu perfil como nome, email e dados pessoais | Manter minhas informações sempre atualizadas |
| [T02](#t02) | <a id="e05">E05</a> | Visualização de produtos | Usuário | Visualizar os produtos disponíveis | Escolher qual será meu pedido |
| [T02](#t02) | <a id="e06">E06</a> | Busca | Usuário | Buscar produtos e lojas | Encontrar produtos e lojas da minha preferência |
| [T02](#t02) | <a id="e07">E07</a> | Favoritos | Usuário | Adicionar produtos e lojas aos favoritos | Acessar rapidamente produtos e lojas que gosto |
| [T03](#t03) | <a id="e08">E08</a> | Carrinho | Usuário | Adicionar, remover e visualizar itens no carrinho | Realizar meu pedido |
| [T03](#t03) | <a id="e09">E09</a> | Personalizar Pedido | Usuário | Ajustar complementos e quantidades dos produtos | Receber os produtos exatamente como quero |
| [T03](#t03) | <a id="e10">E10</a> | Confirmar Pedido | Usuário | Finalizar o pedido com endereço e pagamento | Enviar minha solicitação para a loja |
| [T03](#t03) | <a id="e11">E11</a> | Histórico | Usuário | Visualizar o histórico de pedidos | Acessar pedidos que foram feitos, como também, realizar uma compra novamente que já foi feita anteriormente |
| [T03](#t03) | <a id="e12">E12</a> | Status do Pedido | Usuário | Acompanhar o status do pedido | Saber quando o pedido será entregue |
| [T04](#t04) | <a id="e13">E13</a> | Formas de Pagamento | Usuário | Selecionar uma das formas de pagamento disponíveis | Efetuar o pagamento |
| [T04](#t04) | <a id="e14">E14</a> | Salvar Dados Bancários | Usuário | Salvar meus dados bancários para pagamentos futuros | Utilizá-los novamente em outras compras |
| [T04](#t04) | <a id="e15">E15</a> | Segurança | Usuário | Guardar meus dados bancários com segurança | Garantir que não serão utilizados indevidamente |
| [T05](#t05) | <a id="e16">E16</a> | Rastreio | Usuário | Ver o pedido no mapa | Acompanhar onde está minha entrega |
| [T05](#t05) | <a id="e17">E17</a> | Retirada | Usuário | Poder retirar meu pedido na loja | Contratar o serviço sem a entrega |
| [T05](#t05) | <a id="e18">E18</a> | Confirmar entrega | Usuário | Receber meu pedido mediante confirmação de código do pedido que apenas eu possuo | Ter segurança que meu pedido será entregue corretamente |
| [T05](#t05) | <a id="e19">E19</a> | Escolher o Entregador | Loja | Decidir se a entrega será por um entregador próprio ou por parceiros | Escolher a melhor opção para a entrega |
| [T06](#t06) | <a id="e20">E20</a> | Avaliar Serviços | Usuário | Avaliar o serviço do entregador e o produto entregue | Fornecer feedback ao aplicativo |
| [T06](#t06) | <a id="e21">E21</a> | Avaliar Entrega | Loja | Avaliar a entrega | Dar feedback ao entregador |
| [T07](#t07) | <a id="e22">E22</a> | Cardápio | Loja | Cadastrar e atualizar itens do cardápio | Gerenciar os produtos disponíveis |
| [T07](#t07) | <a id="e23">E23</a> | Aparência | Loja | Personalizar aparência da loja | Manter a identidade visual da minha loja |
| [T07](#t07) | <a id="e24">E24</a> | Receber Pedidos | Loja | Receber detalhes dos pedidos dos usuários | Preparar e entregar |
| [T08](#t08) | <a id="e25">E25</a> | Aceitar Entregas | Entregador | Aceitar pedidos de entrega | Realizar entregas |
| [T08](#t08) | <a id="e26">E26</a> | Localização | Entregador | Localizar loja e clientes | Realizar entregas com eficiência |


**Autores**: [Kauan Eiras](https://github.com/kauaneiras), [Raquel Andrade](https://github.com/raquel-andrade) e [Leonardo Aguiar](https://github.com/Leonardo0o0).
</center>

<center>

## Histórias de usuário

| Tema   | Épico  | ID        | Título                              | Como um(a)  | Eu quero                                                            | Para que eu possa                                              | Prioridade |
|--------|--------|-----------|-------------------------------------|-------------|---------------------------------------------------------------------|----------------------------------------------------------------|------------|
| [T01](#t01) | [E01](#e01) | <a id="us01">US01</a> | CRUD da conta | Usuário | Criar, visualizar, editar e deletar minha conta | Acessar as funcionalidades do sistema e ter controle sobre a conta | Alta |
| [T01](#t01) | [E02](#e02) | <a id="us02">US02</a> | Login | Usuário | Fazer login no aplicativo com email e senha | Ter acesso ao aplicativo | Alta |
| [T01](#t01) | [E02](#e02) | <a id="us03">US03</a> | Sair da conta  | Usuário     | Sair da minha conta no aplicativo  | Minhas informações fiquem protegidas  | Alta  |
| [T01](#t01) | [E03](#e03) | <a id="us04">US04</a> | Recuperar senha | Usuário     | Recuperar minha senha caso eu a esqueça ou queira trocá-la | Acessar minha conta sem problemas | Alta |
| [T01](#t01) | [E04](#e04) | <a id="us05">US05</a> | Editar informações do perfil  | Usuário     | Editar e atualizar meus dados do perfil como foto do perfil e informações pessoais | Manter os dados sempre atualizados  | Alta |
| [T01](#t01) | [E04](#e04) | <a id="us06">US06</a> | Cadastrar endereço | Usuário     | Cadastrar ao menos um endereço no meu perfil | Utilizar minhas informações de localização para as entregas  | Alta |
| [T02](#t02) | [E05](#e05) | <a id="us07">US07</a> | Visualizar produtos | Usuário | Ver os cardápios e os produtos disponíveis e os seus detalhes | Decidir minhas preferências  | Alta |
| [T02](#t02) | [E05](#e05) | <a id="us08">US08</a> | Visualizar recomendações | Usuário | Visualizar as recomendações de produtos e lojas | Descobrir novas opções | Baixa |
| [T02](#t02) | [E06](#e06) | <a id="us09">US09</a> | Buscar lojas e/ou produtos | Usuário     | Buscar produtos e lojas pelo nome ou geolocalização | Encontrar opções que atendem minhas preferências e necessidades  | Alta |
| [T02](#t02) | [E06](#e06) | <a id="us10">US10</a> | Utilizar filtros de busca | Usuário     | Utilizar os filtros de pesquisa, como por exemplo, lojas perto de mim | Encontrar mais rapidamente o que estou buscando | Média |
| [T02](#t02) | [E07](#e07) | <a id="us11">US11</a> | Visualizar e adicionar itens aos favoritos | Usuário | Ver e adicionar produtos e lojas aos meus favoritos | Acessá-los mais rapidamente no futuro | Média      |
| [T03](#t03) | [E08](#e08) | <a id="us12">US12</a> | Adicionar e remover itens do carrinho | Usuário     | Adicionar ou remover produtos do carrinho | Organizar meu pedido | Alta       |
| [T03](#t03) | [E08](#e08) | <a id="us13">US13</a> | Visualizar carrinho | Usuário     | Visualizar o carrinho com os produtos | Realizar o pedido | Alta       |
| [T03](#t03) | [E09](#e09) | <a id="us14">US14</a> | Personalizar itens do pedido | Usuário     | Personalizar os produtos no meu carrinho, como escolher tamanho e extras | Receber o produto exatamente como desejo | Alta       |
| [T03](#t03) | [E09](#e09) | <a id="us15">US15</a> | Adicionar observações ao pedido | Usuário     | Incluir comentários ou instruções especiais ao meu pedido | Garantir que minhas necessidades específicas sejam atendidas     | Média      |
| [T03](#t03) | [E10](#e10) | <a id="us16">US16</a> | Selecionar endereço de entrega | Usuário     | Escolher o endereço onde desejo receber o pedido | Receber meu pedido no local correto | Alta       |
| [T03](#t03) | [E10](#e10) | <a id="us17">US17</a> | Escolher forma de pagamento na confirmação | Usuário     | Selecionar o método de pagamento ao confirmar o pedido | Finalizar minha compra | Alta |
| [T03](#t03) | [E10](#e10) | <a id="us18">US18</a> | Revisar e confirmar o pedido | Usuário     | Verificar todos os detalhes antes de confirmar a compra | Garantir que tudo está correto antes de finalizar | Alta       |
| [T03](#t03) | [E11](#e11) | <a id="us19">US19</a> | Visualizar histórico de pedidos | Usuário     | Acessar a lista de todos os meus pedidos anteriores | Consultar pedidos passados ou repetir pedidos | Média      |
| [T03](#t03) | [E11](#e11) | <a id="us20">US20</a> | Repetir um pedido anterior | Usuário     | Refazer um pedido já realizado com facilidade | Economizar tempo ao pedir algo que já gostei | Média      |
| [T03](#t03) | [E12](#e12) | <a id="us21">US21</a> | Acompanhar status do pedido | Usuário     | Ver em tempo real o andamento do meu pedido | Saber quando o pedido será entregue | Alta       |
| [T04](#t04) | [E13](#e13) | <a id="us22">US22</a> | Selecionar forma de pagamento | Usuário     | Escolher entre cartão, dinheiro ou outros métodos disponíveis | Efetuar o pagamento de forma conveniente | Alta       |
| [T04](#t04) | [E14](#e14) | <a id="us23">US23</a> | Salvar dados de pagamento | Usuário     | Armazenar meus dados bancários no aplicativo | Agilizar futuros pagamentos sem reentrada de dados | Média      |
| [T04](#t04) | [E15](#e15) | <a id="us24">US24</a> | Segurança nos pagamentos | Usuário     | Ter garantia de que meus dados financeiros estão protegidos | Confiar no aplicativo para realizar transações | Alta       |
| [T05](#t05) | [E16](#e16) | <a id="us25">US25</a> | Rastreio do pedido | Usuário     | Ter noção de se meu pedido já saiu da loja e em que parte do caminho ele se encontra | Me preparar para receber o pedido | Média      |
| [T05](#t05) | [E17](#e17) | <a id="us26">US26</a> | Retirada do pedido | Usuário     | Ter a opção de eu mesmo retirar o pedido na loja | Não depender apenas do entregador | Alta |
| [T05](#t05) | [E18](#e18) | <a id="us27">US27</a> | Confirmar entrega do pedido| Usuário     | Que o aplicativo exija um código que apenas eu possua para que o entregador possa liberar o pedido | Não me preocupar se meu pedido será entregue para outra pessoa | Alta       |
| [T05](#t05) | [E19](#e19) | <a id="us28">US28</a> | Escolher o tipo de entregador | Loja        | Que o aplicativo permita a escolha entre entregador próprio ou entregador do aplicativo para as entregas dos pedidos que minha loja receber | Não dependa do entregador do aplicativo  | Alta       |
| [T06](#t06) | [E20](#e20) | <a id="us29">US29</a> | Avaliar entregador | Usuário     | Poder avaliar a entrega feita | Ajudar a mostrar, no aplicativo, se o entregador trabalhou bem   | Alta       |
| [T06](#t06) | [E20](#e20) | <a id="us30">US30</a> | Avaliar pedido | Usuário     | Poder avaliar o pedido entregue | Ajudar a mostrar, no aplicativo, se a loja entrega um bom lanche | Alta |
| [T06](#t06) | [E21](#e21) | <a id="us31">US31</a> | Avaliar entrega | Loja | Poder avaliar se o pedido foi bem entregue | Dar feedback para melhorar os serviços do aplicativo | Alta |
| [T07](#t07) | [E22](#e22) | <a id="us32">US32</a> | Personalizar cardápio | Loja        | Poder fazer mudanças nos itens da loja e em sua ordem | Manter o cardápio atualizado e dar destaque para certos itens  | Alta |
| [T07](#t07) | [E23](#e23) | <a id="us33">US33</a> | Personalizar aparência | Loja        | Poder personalizar a aparência da minha loja | Manter a identidade visual da minha loja atualizada | Alta       |
| [T07](#t07) | [E24](#e24) | <a id="us34">US34</a> | Receber notificações de pedidos | Loja        | Receber a notificação com os detalhes de um pedido quando ele for feito | Preparar o pedido para entrega assim que possível | Alta       |
| [T08](#t08) | [E25](#e25) | <a id="us35">US35</a> | Aceitar entregas de pedidos | Entregador  | Receber a notificação com os detalhes de uma entrega e poder escolher aceitá-la ou não | Escolher as melhores entregas no momento | Alta       |
| [T08](#t08) | [E26](#e26) | <a id="us36">US36</a> | Localizar lojas | Entregador  | Procurar por lojas próximas que estejam precisando de entregadores  | Escolher a loja da qual vou receber pedidos de entrega | Alta       |
| [T08](#t08) | [E26](#e26) | <a id="us37">US37</a> | Localizar Pedidos | Entregador  | Ver o destino dos pedidos que são feitos na loja que eu escolhi | Decidir se vale a pena fazer entregas para a loja escolhida    | Alta       |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras), [Raquel Andrade](https://github.com/raquel-andrade) e [Leonardo Aguiar](https://github.com/Leonardo0o0).

</center>

## Referências

1. **LuizTools**. Product Backlog - Introdução. YouTube, 21 de março de 2020. Disponível em: https://www.youtube.com/watch?v=z4ubaBwjCsU. Acesso em 17 de Novembro de 2024.

2. **SCHWABER, Ken**; SUTHERLAND, Jeff. The Scrum Guide. The Definitive Guide to Scrum: The Rules of the Game. 2020. Disponível em: https://scrumguides.org/scrum-guide.html. Acesso em: 17 de Novembro de 2024.

3. **PICHLER, Roman**. Agile Product Management with Scrum: Creating Products that Customers Love. 1. ed. Addison-Wesley Professional, 2017.

## Histórico de Versões

| Versão | Data      | Descrição    | Autor     | Revisor | Data de revisão |
|--------|-----------|--------------|-----------|---------|-------------|
| 1.0 | 17/11/2024 | Criação dos Temas e Épicos | [Kauan Eiras](https://github.com/kauaneiras), [Raquel Andrade](https://github.com/raquel-andrade) | ------- | ------- |
| 1.1 | 17/11/2024 | Adiciona as Histórias de usuário US01 até US13 | [Raquel Andrade](https://github.com/raquel-andrade) | ------- | ------- |
| 1.2 | 18/11/2024 | Adiciona as Histórias de usuário US14 até US24| [Kauan Eiras](https://github.com/kauaneiras) | ------- | ------- |
| 1.3 | 18/11/2024 | Adiciona as Histórias de usuário US25 até US37, Adiciona dois epicos "Confirmar entrega" e "Aparência" | [Leonardo Aguiar](https://github.com/Leonardo0o0) | ------- | ------- |