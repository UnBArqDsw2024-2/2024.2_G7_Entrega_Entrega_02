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
| T01 | Cadastro e Autenticação | Abrange as funcionalidades de registro, acesso e gerenciamento de dados pessoais, garantindo que os usuários possam criar e acessar suas contas de forma segura e intuitiva. |
| T02 | Exploração do Catálogo | Trata das funcionalidades que permitem aos usuários visualizar, buscar, explorar e marcar itens e lojas como favoritos. Facilita a descoberta e seleção de produtos no aplicativo. |
| T03 | Pedido | Inclui funcionalidades para gerenciar compras, personalizar pedidos, confirmar compras, visualizar o histórico de pedidos e acompanhar o status de pedidos feitos. |
| T04 | Pagamento | Abrange funcionalidades relacionadas às formas de pagamento, como selecionar métodos, salvar dados bancários e garantir a segurança dos dados financeiros. |
| T05 | Entrega | Foca no processo de entrega dos pedidos, incluindo rastreamento em tempo real, opção de retirada no local, e escolha entre entregadores próprios ou parceiros para a entrega. |
| T06 | Avaliação | Envolve funcionalidades para que usuários e lojas possam avaliar entregas e produtos, fornecendo feedback para melhorar o serviço e a experiência geral. |
| T07 | Gerenciamento da Loja | Contempla as necessidades das lojas, permitindo o gerenciamento de cardápios, atualização de itens e recepção de pedidos. |
| T08 | Entregador | Abrange funcionalidades específicas para os entregadores, incluindo a aceitação de pedidos, localização de restaurantes e clientes |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade).
</center>

<center>

## Épicos

| Tema	| ID	| Título	| Como um(a) | Eu quero | Para que eu possa |
| ---- | ---- | ------- | ------- | -------- | ----------------- |
| T01	| E01	| Registro	| Usuário | Registrar o meu perfil | Acessar o aplicativo com minha conta única |
| T01	| E02	| Acesso	| Usuário | Acessar minha conta utilizando meu email e senha | Ter acesso às funcionalidades do aplicativo |
| T01	| E03	| Recuperação de Senha | Usuário | Recuperar minha senha caso a esqueça | Garantir o acesso à minha conta |
| T01	| E04	| Gerenciar Dados do Perfil	| Usuário | Atualizar meu perfil como nome, email e dados pessoais | Manter minhas informações sempre atualizadas |
| T02	| E05	| Visualização de produtos	| Usuário | Visualizar os produtos disponíveis | Escolher qual será meu pedido |
| T02	| E06	| Busca	    | Usuário | Buscar produtos e lojas | Encontrar produtos e lojas da minha preferência |
| T02   | E07   | Favoritos | Usuário | Adicionar produtos e lojas aos favoritos | Acessar rapidamente produtos e lojas que gosto |
| T03	| E08	| Carrinho	| Usuário | Adicionar, remover e visualizar itens no carrinho | Realizar meu pedido |
| T03	| E09	| Personalizar Pedido | Usuário | Ajustar complementos e quantidades dos produtos | Receber os produtos exatamente como quero |
| T03	| E10	| Confirmar Pedido	| Usuário | Finalizar o pedido com endereço e pagamento | Enviar minha solicitação para a loja |
| T03	| E11	| Histórico	| Usuário | Visualizar o histórico de pedidos | Acessar pedidos que foram feitos, como também, realizar uma compra novamente que já foi feita anteriormente |
| T03   | E12  | Status do Pedido | Usuário | Acompanhar o status do pedido | Saber quando o pedido será entregue |
| T04   | E13  | Formas de Pagamento | Usuário | Selecionar uma das formas de pagamento disponíveis | Efetuar o pagamento |
| T04   | E14  | Salvar Dados Bancários | Usuário | Salvar meus dados bancários para pagamentos futuros | Utilizá-los novamente em outras compras |
| T04   | E15  | Segurança | Usuário | Guardar meus dados bancários com segurança | Garantir que não serão utilizados indevidamente |
| T05   | E16  | Rastreio  | Usuário | Ver o pedido no mapa | Acompanhar onde está minha entrega |
| T05   | E17  | Retirada | Usuário | Poder retirar meu pedido na loja | Contratar o serviço sem a entrega |
| T05   | E18  | Confirmar entrega | Usuário | Receber meu pedido mediante confirmação de código do pedido que apenas eu possuo | Ter segurança que meu pedido será entregue corretamente |
| T05   | E19  | Escolher o Entregador | Loja | Decidir se a entrega será por um entregador próprio ou por parceiros | Escolher a melhor opção para a entrega |
| T06   | E20  | Avaliar Serviços | Usuário | Avaliar o serviço do entregador e o produto entregue | Fornecer feedback ao aplicativo |
| T06   | E21  | Avaliar Entrega | Loja | Avaliar a entrega | Dar feedback ao entregador |
| T07   | E22  | Cardápio | Loja | Cadastrar e atualizar itens do cardápio | Gerenciar os produtos disponíveis |
| T07   | E23  | Aparência | Loja | Personalizar aparência da loja | Manter a identidade visual da minha loja |
| T07   | E24  | Receber Pedidos | Loja | Receber detalhes dos pedidos dos usuários | Preparar e entregar |
| T08   | E25  | Aceitar Entregas | Entregador | Aceitar pedidos de entrega | Realizar entregas |
| T08   | E26  | Localização | Entregador | Localizar loja e clientes | Realizar entregas com eficiência |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras), [Raquel Andrade](https://github.com/raquel-andrade) e [Leonardo Aguiar](https://github.com/Leonardo0o0).
</center>

<center>

## Histórias de usuário

| Tema	| Épico  | ID	| Título | Como um(a) | Eu quero | Para que eu possa | Prioridade |
| ----- | ------ | ---- | ------ | ------- | -------- | ----------------- | ---------- |
| T01   | E01    | US01   | CRUD da conta | Usuário | Criar, visualizar, editar e deletar minha conta  | Acessar as funcionalidades do sistema e ter controle sobre a conta | Alta |
| T01   | E02    | US02   | Login | Usuário | Fazer login no aplicativo com email e senha  | Ter acesso ao aplicativo | Alta |
| T01   | E02    | US03   | Sair da conta | Usuário | Sair da minha conta no aplicativo | Minhas informações fiquem protegidas | Alta |
| T01   | E03    | US04   | Recuperar senha | Usuário | Recuperar minha senha caso eu a esqueça ou queira trocá-la | Acessar minha conta sem problemas | Alta |
| T01   | E04    | US05   | Editar informações do perfil | Usuário | Editar e atualizar meus dados do perfil como foto do perfil e informações pessoais | Manter os dados sempre atualizados | Alta |
| T01   | E04    | US06   | Cadastrar endereço | Usuário | Cadastrar ao menos um endereço no meu perfil  | Utilizar minhas informações de localização para as entregas | Alta |
| T02   | E05    | US07   | Visualizar produtos | Usuário | Ver os cardápios e os produtos disponíveis e os seus detalhes  | Decidir minhas preferências | Alta |
| T02   | E05    | US08   | Visualizar recomendações | Usuário | Visualizar as recomendações de produtos e lojas  | Descobrir novas opções | Baixa |
| T02   | E06    | US09   | Buscar lojas e/ou produtos | Usuário | Buscar produtos e lojas pelo nome ou geolocalização | Encontrar opções que atende minhas preferências e necessidades | Alta |
| T02   | E06    | US10   | Utilizar filtros de busca | Usuário | Utilizar os filtros de pesquisa, como por exemplo, lojas perto de mim  | Encontrar mais rapidamente o que estou buscando | Média |
| T02   | E07    | US11   | Visualizar e adicionar itens aos favoritos | Usuário | Ver e adicionar produtos e lojas aos meus favoritos | Acessá-los mais rapidamente no futuro | Média |
| T03   | E08    | US12   | Adicionar e remover itens do carrinho | Usuário | Adicionar ou remover produtos do carrinho | Organizar meu pedido | Alta |
| T03   | E08    | US13   | Visualizar carrinho | Usuário | Visualizar o carrinho com os produtos | Realizar o pedido | Alta |
| T03  | E09   | US14  | Personalizar itens do pedido        | Usuário  | Personalizar os produtos no meu carrinho, como escolher tamanho e extras    | Receber o produto exatamente como desejo            | Alta       |
| T03  | E09   | US15  | Adicionar observações ao pedido     | Usuário  | Incluir comentários ou instruções especiais ao meu pedido                   | Garantir que minhas necessidades específicas sejam atendidas | Média      |
| T03  | E10   | US16  | Selecionar endereço de entrega      | Usuário  | Escolher o endereço onde desejo receber o pedido                            | Receber meu pedido no local correto                 | Alta       |
| T03  | E10   | US17  | Escolher forma de pagamento na confirmação | Usuário  | Selecionar o método de pagamento ao confirmar o pedido                       | Finalizar minha compra         | Alta       |
| T03  | E10   | US18  | Revisar e confirmar o pedido        | Usuário  | Verificar todos os detalhes antes de confirmar a compra                     | Garantir que tudo está correto antes de finalizar   | Alta       |
| T03  | E11   | US19  | Visualizar histórico de pedidos     | Usuário  | Acessar a lista de todos os meus pedidos anteriores                         | Consultar pedidos passados ou repetir pedidos       | Média      |
| T03  | E11   | US20  | Repetir um pedido anterior          | Usuário  | Refazer um pedido já realizado com facilidade                               | Economizar tempo ao pedir algo que já gostei        | Média      |
| T03  | E12   | US21  | Acompanhar status do pedido         | Usuário  | Ver em tempo real o andamento do meu pedido                                 | Saber quando o pedido será entregue                 | Alta       |
| T04  | E13   | US22  | Selecionar forma de pagamento       | Usuário  | Escolher entre cartão, dinheiro ou outros métodos disponíveis               | Efetuar o pagamento de forma conveniente            | Alta       |
| T04  | E14   | US23  | Salvar dados de pagamento           | Usuário  | Armazenar meus dados bancários no aplicativo                                | Agilizar futuros pagamentos sem reentrada de dados  | Média      |
| T04  | E15   | US24  | Segurança nos pagamentos            | Usuário  | Ter garantia de que meus dados financeiros estão protegidos                 | Confiar no aplicativo para realizar transações      | Alta       |
| T05  | E16   | US25  | Rastreio do pedido            | Usuário  | Ter noção de se meu pedido já saiu da loja e em que parte do caminho ele se encontra                 | Me preparar para receber o pedido      | Média       |
| T05  | E17   | US26  | Retirada do pedido            | Usuário  | Ter a opção de eu mesmo retirar o pedido na loja                 | Não depender apenas do entregador      | Alta       |
| T05  | E18   | US27  | Confirmar entrega do pedido  | Usuário  | Que o aplicativo exija um código que apenas eu possua para que o entregador possa liberar o pedido  | Não me preocupar se meu pedido será entregue para outra pessoa | Alta       |
| T05  | E19   | US28  | Escolher o tipo de entregador  | Loja  | Que o aplicativo permita a escolha entre entregador próprio ou entregador do aplicativo para as entregas dos pedidos que minha loja receber  | Não dependa do entregador do aplicativo | Alta       |
| T06  | E20   | US29  | Avaliar entregador            | Usuário  | Poder avaliar a entrega feita | Ajudar a mostrar, no aplicativo, se o entregador trabalhou bem | Alta       |
| T06  | E20   | US30  | Avaliar pedido            | Usuário  | Poder avaliar o pedido entregue | Ajudar a mostrar, no aplicativo, se a loja entrega um bom lanche | Alta       |
| T06  | E21   | US31  | Avaliar entrega            | Loja  | Poder avaliar se o pedido foi bem entregue | Dar feedback para o entregador sobre a entrega que foi feita | Alta       |
| T07  | E22   | US32  | Personalizar cardápio            | Loja  | Poder fazer mudanças nos itens da loja e em sua ordem | Manter o cardápio atualizado e dar destaque para certos itens |
| T07  | E23   | US33  | Personalizar aparência            | Loja  | Poder personalizar a aparência da minha loja | Manter a identidade visual da minha loja atualizada |
| T07  | E24   | US34  | Receber notificações de pedidos            | Loja  | Receber a notificação com os detalhes de um pedido quando ele for feito | Preparar o pedido para entrega assim que possível |
| T08  | E25   | US35  | Aceitar entregas de pedidos            | Entregador  | Receber a notificação com os detalhes de uma entrega e poder escolher aceita-la ou nao | Escolher as melhores entregas no momento |
| T08  | E26   | US36  | Localizar lojas            | Entregador  | Procurar por lojas próximas que estejam precisando de entregadores | Escolher a loja da qual vou receber pedidos de entrega |
| T08  | E26   | US37  | Localizar Pedidos            | Entregador  | Ver o destino dos pedidos que são feitos na loja que eu escolhi | Decidir se vale a pena fazer entregas para a loja escolhida |

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