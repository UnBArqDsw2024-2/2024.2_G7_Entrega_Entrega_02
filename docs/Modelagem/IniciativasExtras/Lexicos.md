# Léxicos

## Introdução

Na engenharia de requisitos, os léxicos são documentos que reúnem um conjunto de termos e vocabulário específico associado ao domínio do sistema/projeto em desenvolvimento. Eles funcionam como uma ferramenta de referência para assegurar que todos os integrantes da equipe compartilhem uma compreensão clara e uniforme dos conceitos empregados no projeto. Além disso, os léxicos auxiliam na padronização da linguagem usada para descrever os requisitos do software (ZOWGHI; COULIN, 2003).

## Metodologia

Este artefato tem como objetivo identificar os léxicos relacionados ao aplicativo HungryHub, que será desenvolvido. Para isso, os termos utilizados no contexto do sistema serão coletados e descritos de forma clara e objetiva. A medida que novos termos surgirem na documentação do projeto, serão adicionados neste documento. Essa abordagem é essencial para garantir que todos os envolvidos no projeto tenham uma compreensão uniforme dos termos utilizados, facilitando a comunicação e o desenvolvimento do sistema.

**Tabela 1: Template para os léxicos**

| Termo                    | Tipo                | Noção                                                           | Impacto                                                     | Autor                              |
| :----------------------: | :-----------------: | :-------------------------------------------------------------: | :---------------------------------------------------------: | :--------------------------------: |
| Nome associado ao léxico | Objeto/Verbo/Estado | Significado do termo, descrito de forma objetiva               | Descrição do efeito ou uso do termo no sistema              | Indivíduo responsável pela descrição |


## **Léxicos de Verbo**

| Termo              | Tipo   | Noção                                                                 | Impacto                                                                                 | Autor |
|--------------------|--------|----------------------------------------------------------------------|----------------------------------------------------------------------------------------|-------|
| Aceitar            | Verbo  | Ação do entregador de confirmar a realização de uma entrega.         | Atualiza o status do pedido e inicia o rastreamento da entrega.                        | [Kauan Eiras](https://github.com/kauaneiras) |
| Adicionar          | Verbo  | Ação de incluir itens no carrinho de compras.                        | Permite ao cliente preparar um pedido para finalização.                                | [Kauan Eiras](https://github.com/kauaneiras) |
| Atualizar          | Verbo  | Ação de modificar informações (perfil, catálogo, status do pedido).  | Garante que os dados estejam sempre corretos e atualizados.                            | [Kauan Eiras](https://github.com/kauaneiras) |
| Avaliar            | Verbo  | Ação de atribuir uma nota ou comentário para um restaurante ou pedido. | Melhora a reputação e confiabilidade das lojas e entregadores.                         | [Kauan Eiras](https://github.com/kauaneiras) |
| Cadastrar          | Verbo  | Ação de registrar um novo usuário no sistema (cliente, lojista ou entregador). | Permite o acesso ao aplicativo e suas funcionalidades.                                | [Kauan Eiras](https://github.com/kauaneiras) |
| Filtrar            | Verbo  | Ação de aplicar critérios de pesquisa (localização, categoria, avaliação). | Melhora a experiência de busca, reduzindo o tempo para encontrar produtos.             | [Kauan Eiras](https://github.com/kauaneiras) |
| Finalizar          | Verbo  | Ação de concluir o pedido no carrinho.                               | Gera um pedido e o envia para o restaurante e entregador.                              | [Kauan Eiras](https://github.com/kauaneiras) |
| Notificar          | Verbo  | Ação de enviar notificações sobre atualizações de status (pedido, promoções). | Mantém o usuário informado sobre o andamento do pedido e ofertas relevantes.           | [Kauan Eiras](https://github.com/kauaneiras) |
| Pesquisar          | Verbo  | Ação de buscar restaurantes ou produtos no aplicativo.               | Facilita a navegação do usuário e a localização de itens ou lojas específicas.         | [Kauan Eiras](https://github.com/kauaneiras) |
| Rastrear           | Verbo  | Ação de acompanhar o trajeto do pedido em tempo real.                | Oferece transparência ao cliente sobre a localização do pedido.                        | [Kauan Eiras](https://github.com/kauaneiras) |

**Autores:** [Kauan Eiras](https://github.com/kauaneiras),

## **Léxicos de Objeto**

| Termo              | Tipo    | Noção                                                                | Impacto                                                                                 | Autor |
|--------------------|---------|---------------------------------------------------------------------|----------------------------------------------------------------------------------------|-------|
| Avaliação          | Objeto  | Nota e comentário feitos pelos usuários sobre produtos ou serviços. | Auxilia na melhoria contínua do sistema e na reputação dos restaurantes.               | [Kauan Eiras](https://github.com/kauaneiras) |
| Carrinho           | Objeto  | Espaço virtual onde os produtos são armazenados antes de serem comprados. | Facilita o gerenciamento de itens antes da finalização do pedido.                      | [Kauan Eiras](https://github.com/kauaneiras) |
| Endereço           | Objeto  | Local onde o pedido será entregue.                                 | Define a logística e o tempo estimado para a entrega.                                  | [Kauan Eiras](https://github.com/kauaneiras) |
| Mapa               | Objeto  | Ferramenta que exibe a rota do entregador em tempo real.            | Oferece visibilidade ao cliente e suporte logístico ao entregador.                     | [Kauan Eiras](https://github.com/kauaneiras) |
| Notificação        | Objeto  | Mensagem informativa enviada ao usuário.                           | Mantém o cliente atualizado sobre o status dos pedidos ou promoções.                  | [Kauan Eiras](https://github.com/kauaneiras) |
| Pedido             | Objeto  | Conjunto de produtos selecionados para compra.                     | Centraliza a interação entre cliente, lojista e entregador.                            | [Kauan Eiras](https://github.com/kauaneiras) |
| Produto            | Objeto  | Item que pode ser comprado pelos clientes (lanche, bebida, etc.).  | É o principal elemento da experiência de compra no aplicativo.                         | [Kauan Eiras](https://github.com/kauaneiras) |
| Restaurante        | Objeto  | Entidade que oferece produtos no aplicativo.                        | Fornece os itens a serem exibidos, comprados e entregues aos clientes.                 | [Kauan Eiras](https://github.com/kauaneiras) |
| Usuário            | Objeto  | Qualquer pessoa que utiliza o aplicativo (cliente, lojista ou entregador). | É o público-alvo do sistema e define os requisitos funcionais a serem desenvolvidos.   | [Kauan Eiras](https://github.com/kauaneiras) |

**Autores:** [Kauan Eiras](https://github.com/kauaneiras),

## **Léxicos de Estado**

| Termo              | Tipo   | Noção                                                                | Impacto                                                                                 | Autor |
|--------------------|--------|---------------------------------------------------------------------|----------------------------------------------------------------------------------------|-------|
| Carrinho Cheio     | Estado | Carrinho com itens adicionados.                                     | Permite que o cliente finalize a compra.                                               | [Kauan Eiras](https://github.com/kauaneiras) |
| Carrinho Vazio     | Estado | Carrinho sem itens.                                                 | Impede a finalização de pedidos.                                                       | [Kauan Eiras](https://github.com/kauaneiras) |
| Logado             | Estado | Usuário autenticado no sistema.                                     | Permite o acesso às funcionalidades restritas.                                         | [Kauan Eiras](https://github.com/kauaneiras) |
| Não Logado         | Estado | Usuário não autenticado.                                            | Restringe o acesso a funcionalidades avançadas, como pedidos.                          | [Kauan Eiras](https://github.com/kauaneiras) |
| Pedido Cancelado   | Estado | Pedido cancelado pelo cliente ou restaurante.                      | Interrompe o fluxo de entrega e requer notificação.                                     | [Kauan Eiras](https://github.com/kauaneiras) |
| Pedido Em Preparo  | Estado | Pedido sendo preparado pelo restaurante.                           | Informa ao cliente e entregador que o pedido está em produção.                         | [Kauan Eiras](https://github.com/kauaneiras) |
| Pedido Em Rota     | Estado | Pedido sendo transportado pelo entregador.                         | Atualiza o rastreamento do pedido em tempo real.                                        | [Kauan Eiras](https://github.com/kauaneiras) |
| Pedido Entregue    | Estado | Pedido finalizado e entregue ao cliente.                           | Fecha o ciclo do pedido e permite avaliação.                                           | [Kauan Eiras](https://github.com/kauaneiras) |

**Autores:** [Kauan Eiras](https://github.com/kauaneiras),

## Referências
1. **Zowghi, D.; Coulin, C.** - Requirements Elicitation: A Survey of Techniques, Aproaches and Tools.

## Histórico de versões

| Versão | Data       | Descrição         | Autor                                           | Revisor |
| ------ | ---------- | ----------------- | ----------------------------------------------- | ------- |
| 1.0    | 16/11/2024 | Criação do Artefato Lexico | [Kauan Eiras](https://github.com/kauaneiras)  |    |