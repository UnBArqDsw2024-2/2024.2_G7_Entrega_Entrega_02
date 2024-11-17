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
| T07 | Gerenciamento da Loja | Contempla as necessidades das lojas, permitindo o gerenciamento de cardápios, atualização de itens, recepção de pedidos e escolha de entregadores. |
| T08 | Entregador | Abrange funcionalidades específicas para os entregadores, incluindo a aceitação de pedidos, localização de restaurantes e clientes |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade).
</center>

<center>

## Épicos

| Tema	| ID	| Título	| Como um | Eu quero | Para que eu possa |
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
| T05   | E18  | Escolher o Entregador | Loja | Decidir se a entrega será por um entregador próprio ou por parceiros | Escolher a melhor opção para a entrega |
| T06   | E19  | Avaliar Serviços | Usuário | Avaliar o serviço do entregador e o produto entregue | Fornecer feedback ao aplicativo |
| T06   | E20  | Avaliar Entrega | Loja | Avaliar a entrega | Dar feedback ao entregador |
| T07   | E21  | Cardápio | Loja | Cadastrar e atualizar itens do cardápio | Gerenciar os produtos disponíveis |
| T07   | E22  | Receber Pedidos | Loja | Receber detalhes dos pedidos dos usuários | Preparar e entregar |
| T08   | E23  | Aceitar Entregas | Entregador | Aceitar pedidos de entrega | Realizar entregas |
| T08   | E24  | Localização | Entregador | Localizar loja e clientes | Realizar entregas com eficiência |

**Autores**: [Kauan Eiras](https://github.com/kauaneiras) e [Raquel Andrade](https://github.com/raquel-andrade)
</center>

<center>

## Histórias de usuário

| Tema	| Épico  | ID	| Título | Como um | Eu quero | Para que eu possa | Prioridade |
| ----- | ------ | ---- | ------ | ------- | -------- | ----------------- | ---------- |
| T01   | E01    | 01   | CRUD da conta | Usuário | Criar, visualizar, editar e deletar minha conta  | Acessar as funcionalidades do sistema e ter controle sobre a conta | Alta |
| T01   | E02    | 02   | Login | Usuário | Fazer login no aplicativo com email e senha  | Ter acesso ao aplicativo | Alta |
| T01   | E02    | 03   | Sair da conta | Usuário | Sair da minha conta no aplicativo | Minhas informações fiquem protegidas | Alta |
| T01   | E03    | 04   | Recuperar senha | Usuário | Recuperar minha senha caso eu a esqueça ou queira trocá-la | Acessar minha conta sem problemas | Alta |
| T01   | E04    | 05   | Editar informações do perfil | Usuário | Editar e atualizar meus dados do perfil como foto do perfil e informações pessoais | Manter os dados sempre atualizados | Alta |
| T01   | E04    | 06   | Cadastrar endereço | Usuário | Cadastrar ao menos um endereço no meu perfil  | Utilizar minhas informações de localização para as entregas | Alta |
| T02   | E05    | 07   | Visualizar produtos | Usuário | Ver os cardápios e os produtos disponíveis e os seus detalhes  | Decidir minhas preferências | Alta |
| T02   | E05    | 08   | Visualizar recomendações | Usuário | Visualizar as recomendações de produtos e lojas  | Descobrir novas opções | Baixa |
| T02   | E06    | 09   | Buscar lojas e/ou produtos | Usuário | Buscar produtos e lojas pelo nome ou geolocalização | Encontrar opções que atende minhas preferências e necessidades | Alta |
| T02   | E06    | 10   | Utilizar filtros de busca | Usuário | Utilizar os filtros de pesquisa, como por exemplo, lojas perto de mim  | Encontrar mais rapidamente o que estou buscando | Média |
| T02   | E07    | 11   | Visualizar e adicionar itens aos favoritos | Usuário | Ver e adicionar produtos e lojas aos meus favoritos | Acessá-los mais rapidamente no futuro | Média |
| T03   | E08    | 12   | Adicionar e remover itens do carrinho | Usuário | Adicionar ou remover produtos do carrinho | Organizar meu pedido | Alta |
| T03   | E08    | 13   | Visualizar carrinho | Usuário | Visualizar o carrinho com os produtos | Realizar o pedido | Alta |

</center>

## Referências

## Histórico de Versões

| Versão | Data      | Descrição    | Autor     | Revisor | Data de revisão |
|--------|-----------|--------------|-----------|---------|-------------|
| 1.0 | 17/11/2024 | Criação dos Temas e Épicos | [Kauan Eiras](https://github.com/kauaneiras), [Raquel Andrade](https://github.com/raquel-andrade) | ------- | ------- |
| 1.1 | 17/11/2024 | Adiciona as Histórias de usuário | [Raquel Andrade](https://github.com/raquel-andrade) | ------- | ------- |
