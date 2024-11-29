# Documento de Modelagem de Estados

## Introdução

Este documento descreve a modelagem de estados para o aplicativo de delivery **HungryHub**, abrangendo os estados principais e suas transições para os **Usuários**, **Lojistas**, e **Entregadores**. Este modelo auxilia no entendimento e na estruturação das funcionalidades do sistema.

---

## Metodologia

1. **Identificação de Classes Relevantes**: As principais classes com comportamentos dependentes de estados foram analisadas.
2. **Definição de Estados**: Foram definidos os estados relevantes para cada classe.
3. **Mapeamento de Transições**: Especificamos os eventos e condições que acionam transições entre estados.
4. **Criação do Diagrama**: Os diagramas foram criados para representar os estados e fluxos visualmente.
5. **Validação**: Revisão pelos membros do time para garantir a consistência e alinhamento com os requisitos.

---

## Escopo do Projeto

O projeto **HungryHub** é um aplicativo de delivery que conecta usuários, restaurantes e entregadores. Os principais atores do sistema são:

- **Usuários**: Realizam pedidos, acompanham entregas, e avaliam serviços.
- **Lojistas**: Recebem, preparam e gerenciam pedidos.
- **Entregadores**: Coletam e entregam pedidos aos usuários.

---

## Diagramas de Estados

### Visão Geral

Abaixo está o diagrama consolidado que representa os estados e transições do sistema para os três atores principais:

![Diagrama de Estados](../../assets/Diagrama%20de%20Estados.jpg)

---

**Autores**: [Bruno Araújo](https://github.com/brunocva), [Wolfgang Friedrich Stein](https://github.com/Wolffstein),[Kauan de Torres Eiras](https://github.com/kauaneiras), [Leonardo Sobrinho de Aguiar](https://github.com/Leonardo0o0)

## Estados e Transições por Atores

### 1. Usuário

#### Estados

- **Fazendo Login**: Usuário insere credenciais para acessar o sistema.
- **Logado**: Usuário autenticado, com acesso ao aplicativo.
- **Realizando Pedido**: Seleção de itens do cardápio.
- **Aguardando Confirmação**: Pedido enviado e aguardando resposta do lojista.
- **Pedido Confirmado**: Pedido aceito pelo lojista.
- **Rastreando Pedido**: Pedido em rota para entrega.
- **Pedido Concluído**: Pedido entregue ao usuário.
- **Editando Dados do Usuário**: Usuário altera informações pessoais.
- **Editando Informações de Pagamento**: Atualização de métodos de pagamento.
- **Editando Endereço**: Modificação ou inclusão de endereços.
- **Gerenciando Favoritos**: Adição ou remoção de produtos da lista de favoritos.

#### Tabela 01 - Transições

| **Estado Atual**          | **Evento/Condição**               | **Próximo Estado**        | **Mensagem/Erro**       |
| ------------------------- | --------------------------------- | ------------------------- | ----------------------- |
| Inativo                   | Inserção de credenciais válidas   | Logado                    | -                       |
| Fazendo Login             | Inserção de credenciais inválidas | Fazendo Login             | "Credenciais inválidas" |
| Logado                    | Início de um pedido               | Realizando Pedido         | -                       |
| Realizando Pedido         | Pedido enviado com sucesso        | Aguardando Confirmação    | -                       |
| Aguardando Confirmação    | Pedido aceito pelo lojista        | Pedido Confirmado         | -                       |
| Pedido Confirmado         | Entregador aceitou o pedido       | Rastreando Pedido         | -                       |
| Rastreando Pedido         | Pedido entregue                   | Pedido Concluído          | -                       |
| Editando Dados do Usuário | Dados válidos inseridos           | Logado                    | -                       |
| Editando Dados do Usuário | Dados inválidos inseridos         | Editando Dados do Usuário | "Erro nos dados"        |

<center>

**Autores**: [Bruno Araújo](https://github.com/brunocva), [Wolfgang Friedrich Stein](https://github.com/Wolffstein)

</center>

---

### 2. Lojista

#### Estados

- **Inativo**: Restaurante não está logado no sistema.
- **Logado**: Lojista autenticado, com acesso ao aplicativo.
- **Recebendo Pedidos**: Restaurante habilitado para receber pedidos.
- **Processando Pedido**: Pedido está sendo preparado.
- **Pedido Pronto**: Pedido está pronto para entrega.
- **Gerenciando Cardápio**: Adição, edição ou remoção de itens do cardápio.

#### Tabela 02 - Transições

| **Estado Atual**     | **Evento/Condição**              | **Próximo Estado**   | **Mensagem/Erro**     |
| -------------------- | -------------------------------- | -------------------- | --------------------- |
| Inativo              | Inserção de credenciais válidas  | Logado               | -                     |
| Logado               | Habilitação para receber pedidos | Recebendo Pedidos    | -                     |
| Recebendo Pedidos    | Pedido aceito pelo lojista       | Processando Pedido   | -                     |
| Processando Pedido   | Pedido finalizado                | Pedido Pronto        | -                     |
| Pedido Pronto        | Pedido coletado pelo entregador  | Recebendo Pedidos    | -                     |
| Gerenciando Cardápio | Item atualizado com sucesso      | Gerenciando Cardápio | -                     |
| Gerenciando Cardápio | Erro ao atualizar item           | Gerenciando Cardápio | "Erro ao salvar item" |

<center>

**Autores**: [Bruno Araújo](https://github.com/brunocva), [Wolfgang Friedrich Stein](https://github.com/Wolffstein)

</center>

---

### 3. Entregador

#### Estados

- **Offline**: Entregador não está disponível.
- **Disponível**: Entregador logado e pronto para aceitar pedidos.
- **A Caminho do Restaurante**: Pedido aceito e entregador está a caminho do restaurante.
- **Pedido em Entrega**: Pedido sendo transportado para o cliente.
- **Entrega Concluída**: Pedido entregue ao cliente.
- **Gerenciando Rota**: Entregador rastreia a rota no mapa.

#### Tabela 03 - Transições

| **Estado Atual**         | **Evento/Condição**   | **Próximo Estado**       | **Mensagem/Erro** |
| ------------------------ | --------------------- | ------------------------ | ----------------- |
| Offline                  | Login realizado       | Disponível               | -                 |
| Disponível               | Pedido aceito         | A Caminho do Restaurante | -                 |
| A Caminho do Restaurante | Chegou ao restaurante | Pedido em Entrega        | -                 |
| Pedido em Entrega        | Pedido entregue       | Entrega Concluída        | -                 |
| Pedido em Entrega        | Falha na entrega      | Pedido em Entrega        | "Erro na entrega" |

<center>

**Autores**: [Bruno Araújo](https://github.com/brunocva), [Wolfgang Friedrich Stein](https://github.com/Wolffstein)

</center>

---

## Referências

1. Lucidchart. O que é um Diagrama de Máquina de Estados UML. Disponível em: [Lucidchart](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-maquina-de-estados-uml).
2. Linguagem de Modelagem Unificada: Em Português. Acesso em: 26 nov. 2024.

---

## Histórico de Versão

| Versão | Data da alteração | Comentário                                                                                           | Autor(es)                                         | Revisor(es)                                               | Data de revisão |
| ------ | ----------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------- | --------------------------------------------------------- | --------------- |
| 1.0    | 26/11/2024        | Criação do documento e adição de introdução, metodologia, escopo, definição de estados e referências | [Leonardo Aguiar](https://github.com/Leonardo0o0) | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | 28/11/2024      |
| 1.1    | 26/11/2024        | Atualização da documentação e correções                                                              | [Bruno Araújo](https://github.com/brunocva)       | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | 28/11/2024      |
| 1.2    | 28/11/2024        | Refatoramento da documentação e correções                                                            | [Bruno Araújo](https://github.com/brunocva)       | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | 28/11/2024      |
