# Diagrama de Componentes (Arquitetura Front-end)

## Introdução

Este documento apresenta o diagrama de componentes desenvolvido para a aplicação HungryHub, mapeando a arquitetura front-end do sistema. O diagrama foi elaborado seguindo práticas estabelecidas de design de componentes para aplicações React conforme Munro [1], visando facilitar o entendimento das relações entre diferentes partes da interface, desde a navegação principal até componentes reutilizáveis. Esta visualização arquitetural serve como referência e apoio para a equipe desenvolver o projeto.

## Metodologia

A construção do diagrama de componentes seguiu uma abordagem baseada na identificação e representação visual de diferentes tipos de entidades que compõem a arquitetura front-end. Para garantir uma representação clara e consistente, foi estabelecida uma nomenclatura padronizada que categoriza as entidades em cinco tipos principais: Páginas, Componentes, Modais, Contextos e Dependências. Cada tipo de entidade possui características e representações visuais específicas, conforme detalhado na tabela de classificação abaixo.

| Tipo de Entidade | Descrição                                                                                                                                                        | Exemplo                                                |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| **Página**       | Representa uma rota individual da interface, que pode agregar outros componentes e modais                                                                        | ![exemplo-pagina](assets/exemplo-pagina.png)           |
| **Componente**   | Bloco reutilizável de interface, responsável por renderizar partes específicas da aplicação. Pode ser funcional ou de classe, e encapsula lógica e apresentação. | ![exemplo-modal](assets/exemplo-modal.png)             |
| **Modal**        | Janela sobreposta à interface principal usada para exibir informações ou interações temporárias sem navegar para outra página                                    | ![exemplo-componente](assets/exemplo-componente.png)   |
| **Contexto**     | Ferramenta para gerenciar estado global ou compartilhado entre vários componentes, permitindo comunicação eficiente sem passar props manualmente                 | ![exemplo-contexto](assets/exemplo-contexto.png)       |
| **Dependência**  | Representa uma relação de dependência entre duas entidades indicada pela direção da seta, ou seja, uma entidade depende ou importa uma outra entidade            | ![exemplo-dependencia](assets/exemplo-dependencia.png) |

Esta metodologia permite a visualização clara da estrutura da aplicação e facilita a identificação de potenciais problemas de arquitetura, oportunidades de reuso de componentes e pontos de melhoria no design da interface.

## Diagrama

Para melhor visualização, o diagrama foi divido em seções que individualizam partes da interface que estão mais relacionadas ou próximas entre si. Cada uma dessas sessões e seus autores podem ser encontradas a seguir:

### 1. Seção Login-Home-Notificações

<center>

![!imagem da seção de login-home-notificações](assets/login-home-notifications-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Leonardo Sobrinho de Aguiar](https://github.com/Leonardo0o0), [Guilherme Westphall de Queiroz](https://github.com/west7)

</center>

### 2. Seção Pesquisa-Detalhes

<center>

![!imagem da seção de pesquisa-detalhes](assets/search-details-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Leonardo Sobrinho de Aguiar](https://github.com/Leonardo0o0), [Guilherme Westphall de Queiroz](https://github.com/west7)

</center>

### 3. Seção Pedidos

<center>

![!imagem da seção de favoritos](assets/myorders-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)

</center>

### 4. Seção Favoritos

<center>

![!imagem da seção de favoritos](assets/favorites-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21)

</center>

### 5. Seção Carrinho-Pagamento

<center>

![!imagem da seção de carrinho-pagamento](assets/cart-payment-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Kallyne Macedo Passos](https://github.com/kalipassos), [Guilherme Silva Dutra](https://github.com/GuiDutra21)

</center>

### 5. Seção Perfil

<center>

![!imagem da seção de perfil](assets/profile-section.png)

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Kauan de Torres Eiras](https://github.com/kauaneiras)

</center>

## Referências

1. MUNRO, Michael. Front-end component design principles. Engineering at CarsGuide, 7 dez. 2016. Disponível em: https://engineering.carsguide.com.au/front-end-component-design-principles-55c5963998c9. Acesso em: 16 nov. 2024.

## Histórico de Versão

| Versão | Data da alteração | Comentário                                                                             | Autor(es)                                                 | Revisor(es)                                            | Data de revisão |
|--------|-------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------|-----------------|
| 1.0    | 24/11/2024        | Criação do documento e adição da tabela de metodologia, imagens do diagrama e autorias | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) | [Kallyne Macedo Passos](https://github.com/kalipassos), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) | 27/11/2024      |
| 1.1    | 27/11/2024        | Detalhamento da introdução e da metodologia                                            | [Kallyne Macedo Passos](https://github.com/kalipassos)    |       [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)                                                 |        28/11/2024         |