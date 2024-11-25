# Cenários
## Introdução 
Este documento apresenta uma série de cenários de uso (COLOCAR O NÚMERO EXATO DE CENÁRIOS AQUI E OS HIPERLINKS) desenvolvidos utilizando os requisitos da [baseline](./Requisitos/baseline.md) do projeto do aplicativo de delivery HungryHub.

Os cenários descritos buscam ilustrar situações reais que usuários podem vivenciar ao interagir com o aplicativo, abrangendo tanto o público final (clientes) quanto os outros atores envolvidos, como entregadores e lojas parceiras. Cada cenário detalha as funcionalidades utilizadas, os fluxos de interação e os benefícios esperados, permitindo uma melhor compreensão do impacto do sistema no dia a dia dos usuários.

Além disso, os cenários servem como um guia prático para validação de requisitos, identificação de melhorias e alinhamento com os objetivos do projeto. Eles representam uma ferramenta essencial para assegurar que as soluções propostas sejam intuitivas, eficientes e alinhadas às expectativas do mercado.

### Cenário de Uso: João, o Usuário Comum (CNE01)

**Perfil:**
João tem 30 anos e mora em uma grande cidade. Ele é um profissional ocupado que valoriza a praticidade na hora de pedir comida. Ele utiliza aplicativos de delivery regularmente para economizar tempo.<br>
**Fluxo de Uso do Aplicativo**<br>

    Cadastro e Login
        João instala o aplicativo e realiza o cadastro como cliente (R01).
        Após preencher seus dados básicos, ele cadastra um endereço residencial para entrega (R06).
        João faz login no sistema utilizando seu e-mail e senha (R04).

    Navegação e Pesquisa de Produtos<br
        No menu inicial, João visualiza diversas lojas e produtos disponíveis (R07).
        Ele utiliza a barra de busca para encontrar restaurantes que vendem "pizza" (R09).
        João clica em um restaurante para visualizar os detalhes de seus produtos, incluindo preço e descrição (R08).

    Seleção de Produtos e Adição ao Carrinho
        João escolhe uma pizza grande e adiciona ao carrinho de compras (R11).
        Ele revisa os itens no carrinho e decide remover um refrigerante antes de prosseguir (R13).

    Finalização da Compra
        João finaliza a compra escolhendo pagar com cartão de crédito (R14, R16).
        O sistema processa o pagamento em menos de 10 segundos, garantindo uma experiência ágil (R43).

    Acompanhamento da Entrega
        Após concluir o pedido, João acompanha o status e a localização do entregador em tempo real no mapa do aplicativo (R15, R39).
        Ele recebe notificações sobre o progresso do pedido, como quando foi preparado e está a caminho (R34).

    Interação Pós-Entrega
        Após receber o pedido, João avalia a loja e o entregador, deixando um comentário positivo sobre a rapidez no serviço (R22, R23, R24).
        Ele verifica o histórico de pedidos e decide favoritar o restaurante para futuras compras rápidas (R20, R21).

    Suporte e Segurança
        Em caso de dúvida sobre o pedido, João utiliza o suporte via chat integrado ao aplicativo (R36).
        João tem a tranquilidade de saber que seus dados bancários e pessoais estão protegidos (R37, R38, R40).

**Autor:** [Davi Pierre](https://github.com/DaviPierre)

### Cenário de Uso: Carlos, o Entregador Dedicado (CNE02)

**Perfil:**
Carlos é um entregador autônomo de 28 anos, que utiliza o aplicativo para complementar sua renda. Ele trabalha em horários flexíveis e prioriza pedidos que sejam eficientes em distância e tempo.<br>
**Fluxo de Uso do Aplicativo**

    Cadastro e Configuração do Perfil
        Carlos instala o aplicativo e realiza seu cadastro como entregador, preenchendo informações pessoais, incluindo dados bancários para receber os pagamentos (R02, R35).
        Após o cadastro, ele carrega uma foto de perfil e personaliza suas preferências de trabalho, como horários disponíveis e regiões de atuação (R05).

    Recebendo Pedidos
        Carlos acessa a interface do entregador, onde pode visualizar solicitações de entrega disponíveis (R31).
        Ele aceita um pedido e verifica os detalhes, incluindo o endereço da loja e o local de entrega (R32, R33).

    Localização e Navegação
        O aplicativo fornece a localização exata da loja utilizando geolocalização em tempo real (R32).
        Carlos utiliza o mapa integrado para planejar a melhor rota até a loja (R39).

    Retirada do Pedido
        Ao chegar na loja, Carlos confirma a retirada do pedido pelo aplicativo, sinalizando que está a caminho do cliente (R15).

    Entrega ao Cliente
        O sistema guia Carlos até o endereço do cliente, atualizando o mapa em tempo real para evitar trânsito e rotas congestionadas (R33, R39).
        Após concluir a entrega, Carlos registra a finalização no aplicativo, o que atualiza automaticamente o status para o cliente (R34).

    Interações e Avaliações
        O cliente avalia a entrega e, caso necessário, pode deixar comentários sobre o serviço. Carlos acompanha as avaliações diretamente no aplicativo, utilizando o feedback para aprimorar sua performance (R22).

    Recebimento de Pagamentos
        Carlos recebe o pagamento pela entrega diretamente na conta bancária cadastrada (R35). O aplicativo valida e garante a segurança da transação (R17, R18).

    Suporte e Problemas Eventuais
        Em caso de dúvidas ou problemas, como dificuldade para localizar o cliente, Carlos pode utilizar o suporte via chat para resolver a situação rapidamente (R36).
**Autor:** [Davi Pierre](https://github.com/DaviPierre)

### Cenário de Uso: Padaria Delícias do Pão (CNE03)

**Perfil:**
A Padaria Delícias do Pão é um estabelecimento familiar que decidiu expandir suas vendas através do aplicativo de delivery. Gerenciada por Marina, a proprietária, a padaria busca aumentar o alcance dos seus produtos, especialmente durante a manhã e no fim da tarde.<br>
**Fluxo de Uso do Aplicativo**

    Cadastro da Loja
        Marina realiza o cadastro da padaria no aplicativo, fornecendo informações básicas, como nome da loja, endereço e horário de funcionamento (R03).
        Em seguida, ela cria seu perfil administrativo para gerenciar pedidos e acompanhar o desempenho de vendas (R04, R05).

    Configuração do Cardápio
        Marina utiliza a funcionalidade de gestão de cardápio para cadastrar todos os produtos oferecidos, incluindo pães, bolos e lanches, com fotos e descrições detalhadas (R25).
        Ela também define preços, categorias e horários de disponibilidade para produtos específicos, como combos matinais (R26).

    Recebendo e Gerenciando Pedidos
        Quando um cliente realiza um pedido, Marina recebe uma notificação no aplicativo com os detalhes completos, como itens solicitados, endereço de entrega e forma de pagamento (R27).
        Ela confirma o pedido e inicia o preparo, com status atualizado automaticamente para o cliente (R34).

    Escolha da Forma de Entrega
        Marina decide a melhor forma de entrega para cada pedido:
            Para regiões próximas, utiliza seu entregador próprio (R30).
            Para distâncias maiores, conta com entregadores parceiros disponíveis no aplicativo (R28).
            Caso o cliente opte por retirada no local, o aplicativo organiza o fluxo (R29).

    Acompanhamento do Pedido
        Marina acompanha em tempo real a entrega feita pelo entregador, podendo monitorar a localização e confirmar a finalização do pedido (R15).

    Interação com os Clientes
        Após a entrega, os clientes podem avaliar os produtos e o serviço da padaria. Marina utiliza essas avaliações para ajustar seu cardápio e melhorar o atendimento (R23).

    Gestão de Relatórios e Estatísticas
        O aplicativo fornece relatórios detalhados sobre o volume de vendas, itens mais populares e horários de pico. Marina usa essas informações para planejar promoções e ajustar o estoque.

    Suporte e Consultas
        Sempre que necessário, Marina entra em contato com o suporte do aplicativo via chat para esclarecer dúvidas ou resolver problemas (R36).
**Autor:** [Davi Pierre](https://github.com/DaviPierre)

# Histórico de versão 
| Versão | Data da alteração | Comentário                                                                      | Autor(es)                                    | Revisor(es) | Data de revisão |
| ------ | ----------------- | ------------------------------------------------------------------------------- | -------------------------------------------- | ----------- | --------------- |
| 1.0    | 25/11/2024        | Criação do documento de cenários, introdução e dos cenários CNE01, CNE02, CNE03 | [Davi Pierre](https://github.com/DaviPierre) |             |                 |