# Documento de Modelagem de Estados

## Introdução

Este documento tem como objetivo descrever a modelagem de estados para o aplicativo de delivery HungryHub. A modelagem de estados é essencial para compreender e estruturar os diferentes estados que o sistema pode assumir, além de definir as transições entre esses estados. Este processo garante que o aplicativo seja desenvolvido de forma organizada e eficiente, atendendo aos requisitos funcionais e de usuários.

## Metodologia

A elaboração do documento aconteceu conforme as etapas a seguir:

1. **Identificação de Classes Relevantes**: Foram analisadas as principais classes do sistema que possuem comportamentos influenciados por estados.

2. **Definição de Estados**: Foram definidos os estados relevantes para cada classe identificada.

3. **Mapeamento de Transições**: Foram especificados os eventos e condições que acionam as transições entre estados.

4. **Criação do Diagrama de Estados**: Um diagrama foi planejado para ilustrar as transições de forma clara e objetiva.

5. **Validação**: O documento foi revisado por membros do projeto para confirmar que os estados e transições atendem aos casos de uso do sistema.

## Escopo do Projeto

O aplicativo de delivery tem como objetivo conectar usuários a restaurantes e entregadores, permitindo pedidos e entregas de forma rápida e eficiente. Os principais atores envolvidos incluem:

* **Usuário**: realiza pedidos e acompanha entregas.

* **Restaurante**: recebe e processam os pedidos.

* **Entregadores**: realiza a coleta e entrega dos pedidos.

## Definição de Estados

Os estados representam as situações em que os componentes do sistema podem estar durante a sua execução. Abaixo está a definição dos estados principais para cada ator envolvido no sistema:

### Estados do Usuário

* **Fazendo cadastro**: Usuário está se cadastrando no sistema.

* **Inativo**: Usuário não está logado no sistema.

* **Fazendo login**: Usuário está logando no sistema.

* **Logado**: Usuário autenticado, com acesso ao aplicativo.

* **Realizando Pedido**: Usuário está navegando no cardápio e selecionando itens.

* **Aguardando Confirmação**: Pedido foi realizado e está aguardando aprovação do restaurante.

* **Pedido Confirmado**: Restaurante aceitou o pedido.

* **Rastreando pedido**: Pedido está sendo entregue pelo entregador e sendo rastreado pelo usuário.

* **Pedido Concluído**: Pedido foi entregue ao usuário.

* **Editando Informações de Pagamento**: Usuário está atualizando os dados de pagamento.

* **Editando Endereço**: Usuário está modificando o endereço de entrega ou adicionando um endereço novo à lista de endereços.

* **Editando Dados do Usuário**: Usuário está alterando informações pessoais.

### Estados do Restaurante

* **Inativo**: Restaurante não está logado ou habilitado para receber pedidos.

* **Logado**: Restaurante autenticado, com acesso ao aplicativo.

* **Recebendo Pedidos**: Restaurante está logado e apto a receber pedidos.

* **Processando Pedido**: Pedido está sendo preparado.

* **Pedido Pronto**: Pedido está pronto para retirada pelo entregador.

### Estados do Entregador

* **Offline**: Entregador não está disponível.

* **Disponível**: Entregador está logado e disponível para aceitar pedidos.

* **A Caminho do Restaurante**: Entregador aceitou um pedido e está indo ao restaurante.

* **Pedido em Entrega**: Entregador está levando o pedido ao cliente.

* **Entrega Concluída**: Pedido foi entregue ao cliente.

## Diagrama de Estados



## Transições entre Estados

Tabela:

| **Estado Atual**       | **Evento/Condição**                           | **Próximo Estado**          |
|-------------------------|-----------------------------------------------|-----------------------------|
| Inativo                | Usuário insere credenciais válidas           | Logado                     |
| Logado                 | Usuário inicia um pedido                     | Realizando Pedido          |
| Realizando Pedido      | Pedido enviado pelo usuário                  | Aguardando Confirmação     |
| Aguardando Confirmação | Restaurante aceita o pedido                  | Pedido Confirmado          |
| Pedido Confirmado      | Entregador aceita o pedido                   | Pedido em Entrega          |

Autor: [Bruno Araújo](https://github.com/brunocva)

## Referências

* Lucidchart. O que é um Diagrama de Máquina de Estados UML. Disponível em: https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-maquina-de-estados-uml. Acesso em: 26 nov. 2024.

* Linguagem de Modelagem Unificada: Em Português. [s.l: s.n.]. p. 1-42. Acesso em: 26 nov. 2024.

## Histórico de Versão

| Versão | Data da alteração | Comentário | Autor(es) | Revisor(es) | Data de revisão |
|--------|-----------|-----------|-----------|-------------|-------------|
| 1.0 | 26/11/2024 | Criação do documento e adição de introdução, metodologia, escopo, definição de estados e referências | [Leonardo Aguiar](https://github.com/Leonardo0o0) |  |  |
| 1.1 | 26/11/2024 | Atualização da documentação e correções | [Bruno Araújo](https://github.com/brunocva) |  |  |