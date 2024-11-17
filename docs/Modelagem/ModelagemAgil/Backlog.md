# Product Backlog

## Introdução
O backlog do produto é um artefato essencial no contexto da modelagem ágil, especialmente no framework Scrum. Ele consiste em uma lista que reúne todas as funcionalidades, melhorias, correções e outros itens necessários para a criação ou evolução do produto.

Diferente de uma especificação inicial fechada, o backlog do produto é um documento vivo que evolui continuamente, permitindo ajustes baseados em feedback dos usuários, mudanças nos objetivos do negócio ou descobertas durante o desenvolvimento. Cada item do backlog, muitas vezes representado por histórias de usuário, descreve de forma simples e clara o que deve ser feito para agregar valor ao produto (SCHWABER; SUTHERLAND, 2020).

## Metodologia
A metodologia utilizada para a elaboração do backlog segue uma estrutura hierárquica. Inicialmente, os **temas** são definidos com base nos [requisitos levantados](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline), abrangendo áreas e objetivos do sistema. Esses temas são divididos em **épicos**, que representam grupos de funcionalidades relacionadas e mais detalhadas. Por fim, cada épico é subdividido em **histórias de usuário**, que descrevem de maneira específica as funcionalidades ou necessidades que o produto deve atender.

Essa abordagem permite uma visualização estruturada do backlog, facilitando a priorização e o refinamento contínuo do projeto, garantindo que os itens estejam alinhados aos objetivos do produto e às necessidades dos usuários (PICHLER, 2017). 

## Backlog

### Temas

|  ID  | Título                 | Descrição                                        |
| ---- | ---------------------- | ------------------------------------------------ |
| T01 | Cadastro e Autenticação | Abrange as funcionalidades de registro, acesso e gerenciamento de dados pessoais, garantindo que os usuários possam criar e acessar suas contas de forma segura e intuitiva. |
| T02 | Exploração do Catálogo | Trata das funcionalidades que permitem aos usuários visualizar, buscar, explorar e marcar itens e lojas como favoritos. Facilita a descoberta e seleção de produtos no aplicativo. |
| T03 | Pedido | Inclui funcionalidades para gerenciar compras, personalizar pedidos, confirmar compras, visualizar o histórico de pedidos e acompanhar o status de pedidos feitos. |
| T04 | Pagamento | Abrange funcionalidades relacionadas às formas de pagamento, como selecionar métodos, salvar dados bancários e garantir a segurança dos dados financeiros. |
| T05 | Entrega | Foca no processo de entrega dos pedidos, incluindo rastreamento em tempo real, opção de retirada no local, e escolha entre entregadores próprios ou parceiros para a entrega. |
| T06 | Avaliação | Envolve funcionalidades para que usuários e lojas possam avaliar entregas e produtos, fornecendo feedback para melhorar o serviço e a experiência geral. |
| T07 | Gerenciamento da Loja | Contempla as necessidades das lojas, permitindo o gerenciamento de cardápios, atualização de itens, recepção de pedidos e escolha de entregadores. |
| T08 | Entregador | Abrange funcionalidades específicas para os entregadores, incluindo a aceitação de pedidos, localização de restaurantes e clientes |

**autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade).

### Épicos

| Tema	| ID	| Título	| Como um | Eu quero | Para que eu possa |
| ---- | ---- | ------- | ------- | -------- | ----------------- |
| T01	| E001	| Registro	| Usuário | Registrar o meu perfil | Acessar o aplicativo com minha conta única |
| T01	| E002	| Acesso	| Usuário | Acessar minha conta utilizando meu email e senha | Ter acesso às funcionalidades do aplicativo |
| T01	| E003	| Recuperação de Senha | Usuário | Recuperar minha senha caso a esqueça | Garantir o acesso à minha conta |
| T01	| E004	| Gerenciar Dados do Perfil	| Usuário | Atualizar meu perfil como nome, email e dados pessoais | Manter minhas informações sempre atualizadas |
| T02	| E005	| Visualização de produtos	| Usuário | Visualizar os produtos disponíveis e seus detalhes | Escolher qual será meu pedido |
| T02	| E006	| Busca	    | Usuário | Buscar produtos e lojas, pelo nome ou geolocalização | Encontrar produtos e lojas da minha preferência |
| T02   | E007   | Favoritos | Usuário | Adicionar produtos e lojas aos favoritos | Acessar rapidamente produtos e lojas que gosto |
| T03	| E008	| Carrinho	| Usuário | Adicionar, remover e visualizar itens no carrinho | Realizar meu pedido |
| T03	| E009	| Personalizar Pedido | Usuário | Ajustar complementos e quantidades dos produtos | Receber os produtos exatamente como quero |
| T03	| E010	| Confirmar Pedido	| Usuário | Finalizar o pedido com endereço e pagamento | Enviar minha solicitação para a loja |
| T03	| E011	| Histórico	| Usuário | Visualizar o histórico de pedidos | Acessar pedidos que foram feitos, como também, realizar uma compra novamente que já foi feita anteriormente |
| T03   | E012  | Status do Pedido | Usuário | Acompanhar o status do pedido | Saber quando o pedido será entregue |
| T04   | E013  | Formas de Pagamento | Usuário | Selecionar uma das formas de pagamento disponíveis | Efetuar o pagamento |
| T04   | E014  | Salvar Dados Bancários | Usuário | Salvar meus dados bancários para pagamentos futuros | Utilizá-los novamente em outras compras |
| T04   | E015  | Segurança | Usuário | Guardar meus dados bancários com segurança | Garantir que não serão utilizados indevidamente |
| T05   | E016  | Rastreio  | Usuário | Ver o pedido no mapa | Acompanhar onde está minha entrega |
| T05   | E017  | Retirada | Usuário | Poder retirar meu pedido na loja | Contratar o serviço sem a entrega |
| T05   | E018  | Escolher o Entregador | Loja | Decidir se a entrega será por um entregador próprio ou por parceiros | Escolher a melhor opção para a entrega |
| T06   | E019  | Avaliar Serviços | Usuário | Avaliar o serviço do entregador e o produto entregue | Fornecer feedback ao aplicativo |
| T06   | E020  | Avaliar Entrega | Loja | Avaliar a entrega | Dar feedback ao entregador |
| T07   | E021  | Cardápio | Loja | Cadastrar e atualizar itens do cardápio | Gerenciar os produtos disponíveis |
| T07   | E022  | Receber Pedidos | Loja | Receber detalhes dos pedidos dos usuários | Preparar e entregar |
| T08   | E023  | Aceitar Entregas | Entregador | Aceitar pedidos de entrega | Realizar entregas |
| T08   | E024  | Localização | Entregador | Localizar loja e clientes | Realizar entregas com eficiência |

**autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade)

### Histórias de usuário

## Referências

## Histórico de Versões

| Versão | Data    | Descrição         | Autor                                           | Revisor |
| 1.0 | 17/11/2024 | Criação dos Temas e Épicos | [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade) | ------- |