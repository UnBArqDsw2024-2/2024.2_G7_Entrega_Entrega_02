# Léxicos

## Introdução

Na engenharia de requisitos, os léxicos são documentos que reúnem um conjunto de termos e vocabulário específico associado ao domínio do sistema/projeto em desenvolvimento. Eles funcionam como uma ferramenta de referência para assegurar que todos os integrantes da equipe compartilhem uma compreensão clara e uniforme dos conceitos empregados no projeto. Além disso, os léxicos auxiliam na padronização da linguagem usada para descrever os requisitos do software (ZOWGHI; COULIN, 2003).

## Metodologia

Este artefato tem como objetivo identificar os léxicos relacionados ao sistema HungryHub, que será desenvolvido. Para isso, os termos utilizados no contexto do sistema serão coletados e descritos de forma clara e objetiva. A medida que novos termos surgirem na documentação do projeto, serão adicionados neste documento. Essa abordagem é essencial para garantir que todos os envolvidos no projeto tenham uma compreensão uniforme dos termos utilizados, facilitando a comunicação e o desenvolvimento do sistema.

**Tabela 1: Template para os léxicos**

|          Termo           |        Tipo         |                      Noção                       |                    Impacto                     |                Autor                 |
| :----------------------: | :-----------------: | :----------------------------------------------: | :--------------------------------------------: | :----------------------------------: |
| Nome associado ao léxico | Objeto/Verbo/Estado | Significado do termo, descrito de forma objetiva | Descrição do efeito ou uso do termo no sistema | Indivíduo responsável pela descrição |


## **Léxicos de Verbo**

<!-- talvez Confirmar pudesse ser a confirmação de pagamento ao invés de recebimento (de acordo com protótipo) -->

| Termo     | Tipo  | Noção                                                                          | Impacto                                                                        | Autor                                           |
| --------- | ----- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ----------------------------------------------- |
| Aceitar   | Verbo | Ação do entregador de confirmar que irá realizar uma entrega.                   | Atualiza o status do pedido e inicia o rastreamento da entrega.                | [Kauan Eiras](https://github.com/kauaneiras)    |
| Acessar   | Verbo | Ação de entrar no aplicativo ou em uma funcionalidade específica.              | Permite ao usuário utilizar as funcionalidades do sistema.                     | [Lucas Martins](https://github.com/martinsglucas) |
| Adicionar | Verbo | Ação de incluir itens no carrinho de compras.                                  | Permite ao cliente preparar um pedido para finalização.                        | [Kauan Eiras](https://github.com/kauaneiras)    |
| Atualizar | Verbo | Ação de modificar informações (perfil, catálogo, status do pedido).            | Garante que os dados estejam sempre corretos e atualizados.                    | [Kauan Eiras](https://github.com/kauaneiras)    |
| Avaliar   | Verbo | Ação de atribuir uma nota ou comentário para um restaurante ou pedido.         | Impacta a reputação e confiabilidade das lojas e entregadores.                 | [Kauan Eiras](https://github.com/kauaneiras)    |
| Cadastrar | Verbo | Ação de registrar um novo usuário no sistema (cliente, loja ou entregador). | Permite o acesso ao aplicativo e suas funcionalidades.                         | [Kauan Eiras](https://github.com/kauaneiras)    |
| Confirmar | Verbo | Ação de validar o recebimento de um pedido | Atualiza o status do pedido e finaliza o processo de entrega. | [Lucas Martins](https://github.com/martinsglucas) |
| Excluir   | Verbo | Ação de remover itens do carrinho de compras.                                  | Permite ao cliente ajustar o pedido antes da finalização.                      | [Guilherme Westphall](https://github.com/west7) |
| Explorar  | Verbo | Ação de navegar pelo aplicativo em busca de novos produtos ou restaurantes.    | Facilita a descoberta de novos itens e lojas e estimula a compra.              | [Guilherme Westphall](https://github.com/west7) |
| Filtrar   | Verbo | Ação de aplicar critérios de pesquisa (localização, categoria, avaliação).     | Melhora a experiência de busca, reduzindo o tempo para encontrar produtos.     | [Kauan Eiras](https://github.com/kauaneiras)    |
| Finalizar | Verbo | Ação de concluir o pedido no carrinho.                                         | Gera um pedido e o envia para o restaurante e entregador.                      | [Kauan Eiras](https://github.com/kauaneiras)    |
| Notificar | Verbo | Ação de enviar notificações sobre atualizações de status (pedido, promoções).  | Mantém o usuário informado sobre o andamento do pedido e ofertas relevantes.   | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pesquisar | Verbo | Ação de buscar restaurantes ou produtos no aplicativo.                         | Facilita a navegação do usuário e a localização de itens ou lojas específicas. | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pagar     | Verbo | Ação de efetuar o pagamento do pedido.                                         | Finaliza a compra e garante a envio do pedido à loja.                            | [Guilherme Westphall](https://github.com/west7) |
| Rastrear  | Verbo | Ação de acompanhar o trajeto do pedido em tempo real.                          | Oferece transparência ao cliente sobre a localização do pedido.                | [Kauan Eiras](https://github.com/kauaneiras)    |
| Visualizar| Verbo | Ação de ver informações detalhadas sobre produtos, pedidos ou perfil.         | Facilita a tomada de decisão e a interação do usuário com o aplicativo.         | [Lucas Martins](https://github.com/martinsglucas) |

**Autores:** [Kauan Eiras](https://github.com/kauaneiras), [Guilherme Westphall](https://github.com/west7), [Lucas Martins](https://github.com/martinsglucas)

## **Léxicos de Objeto**

| Termo                | Tipo   | Noção                                                                                                    | Impacto                                                                              | Autor                                                                                         |
| -------------------- | ------ | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- |
| Avaliação            | Objeto | Nota e comentário feitos pelos usuários sobre produtos ou serviços.                                      | Auxilia na melhoria contínua do sistema e na reputação dos restaurantes e entregadores.             | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Carrinho             | Objeto | Espaço virtual onde os produtos são armazenados antes de serem comprados.                                | Facilita o gerenciamento de itens antes da finalização do pedido.                    | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Categoria            | Objeto | Classificação dos produtos (lanche, bebida, sobremesa, etc.).                                            | Facilita a organização e a busca de itens no aplicativo.                             | [Guilherme Westphall](https://github.com/west7)                                               |
| Cardápio             | Objeto | Lista de produtos disponíveis em um restaurante.                                                         | Apresenta os itens que podem ser comprados e entregues aos clientes.                | [Lucas Martins](https://github.com/martinsglucas)                                             |
| Cliente              | Objeto | Tipo de usuário que utiliza o aplicativo para realizar pedidos.                                          | Define o público-alvo do sistema e suas funcionalidades.                             | [Guilherme Westphall](https://github.com/west7)                                               |
| Endereço de entrega  | Objeto | Local onde o pedido será entregue (endereço residencial do cliente).                                     | Define a logística e o tempo estimado para a entrega.                                | [Kauan Eiras](https://github.com/kauaneiras), [Guilherme Westphall](https://github.com/west7) |
| Endereço de retirada | Objeto | Local onde o pedido pode ser retirado (endereço da loja).                                                    | Facilita a logística de retirada de pedidos e a comunicação entre cliente e lojista. | [Guilherme Westphall](https://github.com/west7)                                               |
| Entregador           | Objeto | Tipo de usuário responsável por transportar os pedidos até os clientes.                                  | Garante a entrega dos produtos e a satisfação do cliente.                            | [Guilherme Westphall](https://github.com/west7)                                               |
| Favoritos            | Objeto | Lista de produtos ou restaurantes marcados como favoritos pelo cliente.                                  | Facilita o acesso a itens frequentemente comprados ou lojas preferidas.              | [Guilherme Westphall](https://github.com/west7)                                               |
| Forma de pagamento  | Objeto | Método utilizado para efetuar o pagamento do pedido (dinheiro, cartão, etc.).                             | Define as opções disponíveis e viabiliza a finalização da compra.                     | [Lucas Martins](https://github.com/martinsglucas)                                             |
| Histórico de pedidos | Objeto | Registro de pedidos realizados pelo cliente.                                                             | Permite ao usuário visualizar pedidos anteriores e repetir compras.                  | [Guilherme Westphall](https://github.com/west7)                                               |
| Localização Atual    | Objeto | Posição atual do entregador no mapa.                                                                     | Facilita a entrega de pedidos e a comunicação entre as partes.                       | [Guilherme Westphall](https://github.com/west7)                                               |
| Lojista              | Objeto | Tipo de usuário que utiliza o aplicativo para gerenciar produtos e pedidos. | Responsável pela gerenciar a loja.              | [Guilherme Westphall](https://github.com/west7)                                               |
| Mapa                 | Objeto | Ferramenta que exibe a rota do entregador em tempo real.                                                 | Oferece visibilidade ao cliente e suporte logístico ao entregador.                   | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Notificação          | Objeto | Mensagem informativa enviada ao usuário.                                                                 | Mantém o cliente atualizado sobre o status dos pedidos ou promoções.                 | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Pedido               | Objeto | Conjunto de produtos selecionados para compra.                                                           | Centraliza a interação entre cliente, loja e entregador.                          | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Perfil               | Objeto | Informações pessoais do usuário (nome, e-mail, telefone, endereços, etc.).                               | Informações básicas sobre o cliente, necessárias para o uso do aplicativo.           | [Guilherme Westphall](https://github.com/west7)                                               |
| Ponto de referẽncia  | Objeto | Local reconhecível para auxiliar na entrega do pedido.                                               | Facilita a identificação do endereço de entrega e a comunicação com o entregador.    | [Guilherme Westphall](https://github.com/west7)                                               |
| Produto              | Objeto | Item que pode ser comprado pelos clientes (lanche, bebida, etc.).                                        | É o principal elemento da experiência de compra no aplicativo.                       | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Promoção             | Objeto | Oferta especial de produtos ou descontos.                                                                | Estimula a compra e fideliza o cliente.                                              | [Guilherme Westphall](https://github.com/west7)                                               |
| Restaurante          | Objeto | Entidade que oferece produtos no aplicativo.                                                             | Fornece os itens a serem exibidos, comprados e entregues aos clientes.               | [Kauan Eiras](https://github.com/kauaneiras)                                                  |
| Resumo do Pedido     | Objeto | Informações resumidas sobre o pedido (itens, valor total, endereço de entrega).                          | Facilita a visualização e confirmação do pedido antes da finalização.                | [Guilherme Westphall](https://github.com/west7)                                               |
| Subtotal do Pedido   | Objeto | Valor parcial do pedido, sem taxas e descontos.                                                          | Informa ao cliente o custo dos produtos selecionados.                                | [Guilherme Westphall](https://github.com/west7)                                               |
| Suporte              | Objeto | Canal de comunicação para tirar dúvidas e resolver problemas.                                            | Oferece assistência ao cliente e melhora a experiência de uso do aplicativo.         | [Guilherme Westphall](https://github.com/west7)                                               |
| Tempo de entrega     | Objeto | Intervalo de tempo estimado para a entrega do pedido.                                                    | Informa ao cliente o tempo necessário para a chegada do pedido.                      | [Guilherme Westphall](https://github.com/west7)                                               |
| Total do Pedido      | Objeto | Valor total do pedido, incluindo produtos, taxas e descontos.                                            | Informa ao cliente o custo final da compra e facilita o pagamento.                   | [Guilherme Westphall](https://github.com/west7)                                               |
| Usuário              | Objeto | Qualquer pessoa que utiliza o aplicativo (cliente, lojista ou entregador).                               | É o público-alvo do sistema e define os requisitos funcionais a serem desenvolvidos. | [Kauan Eiras](https://github.com/kauaneiras)                                                  |

**Autores:** [Kauan Eiras](https://github.com/kauaneiras), [Guilherme Westphall](https://github.com/west7), [Lucas Martins](https://github.com/martinsglucas)

## **Léxicos de Estado**

| Termo               | Tipo   | Noção                                         | Impacto                                                        | Autor                                           |
| ------------------- | ------ | --------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------- |
| Carregando          | Estado | Aplicativo em processo de carregamento.       | Informa ao usuário que o sistema está em execução.             | [Guilherme Westphall](https://github.com/west7) |
| Carrinho Cheio      | Estado | Carrinho com itens adicionados.               | Permite que o cliente finalize a compra.                       | [Kauan Eiras](https://github.com/kauaneiras)    |
| Carrinho Vazio      | Estado | Carrinho sem itens.                           | Impede a finalização de pedidos.                               | [Kauan Eiras](https://github.com/kauaneiras)    |
| Logado              | Estado | Usuário autenticado no sistema.               | Permite o acesso às funcionalidades restritas.                 | [Kauan Eiras](https://github.com/kauaneiras)    |
| Não Logado          | Estado | Usuário não autenticado.                      | Restringe o acesso as principais funcionalidades.  | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pedido Aceito       | Estado | Pedido confirmado pelo restaurante.           | Inicia o processo de entrega e notifica o cliente.             | [Guilherme Westphall](https://github.com/west7) |
| Pedido Cancelado    | Estado | Pedido cancelado pelo cliente ou restaurante. | Interrompe o fluxo de entrega e requer notificação.            | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pedido Em Preparo   | Estado | Pedido sendo preparado pelo restaurante.      | Informa ao cliente e entregador que o pedido está em produção. | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pedido Em Rota      | Estado | Pedido sendo transportado pelo entregador.    | Atualiza o rastreamento do pedido em tempo real.               | [Kauan Eiras](https://github.com/kauaneiras)    |
| Pedido Entregue     | Estado | Pedido finalizado e entregue ao cliente.      | Fecha o ciclo do pedido e permite avaliação.                   | [Kauan Eiras](https://github.com/kauaneiras)    |
| Produto em promoção | Estado | Produto com desconto ou oferta especial.      | Estimula a compra e fideliza o cliente.                        | [Guilherme Westphall](https://github.com/west7) |

<center>

**Autores:** [Kauan Eiras](https://github.com/kauaneiras), [Guilherme Westphall](https://github.com/west7)

</center>

## Referências
1. **Zowghi, D.; Coulin, C.** - Requirements Elicitation: A Survey of Techniques, Aproaches and Tools.

## Histórico de versões

| Versão | Data da alteração | Comentário | Autor(es) | Revisor(es) | Data de revisão |
| -- | -- | -- | -- | -- | -- |
| 1.0    | 16/11/2024 | Criação do Artefato Lexico | [Kauan Eiras](https://github.com/kauaneiras)    | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)       | 27/11/2024 |
| 1.1    | 17/11/2024 | Adição de novos léxicos    | [Guilherme Westphall](https://github.com/west7) |  [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)      | 27/11/2024 |
| 1.2   | 20/11/2024 | Adição de léxicos do tipo verbo e objeto | [Lucas Martins](https://github.com/martinsglucas) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) | 27/11/2024 |