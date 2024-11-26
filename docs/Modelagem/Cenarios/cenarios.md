# Cenários Produzidos

## Introdução 
Neste documento serão apresentados os cenários produzidos.

| ID | Titulo |
|------|---------|
| CN1 | Cliente cadastra uma conta |
| CN2 | Cliente faz login |
| CN3 | Cliente pesquisa um produto |
| CN4 | Cliente verifica produtos de uma loja |
| CN5 | Cliente adiciona item aos favoritos |
| CN6 | Cliente remove item dos favoritos |
| CN7 | Cliente solicita suporte |
| CN8 | Cliente adiciona produto ao carrinho |
| CN9 | Cliente remove produto ao carrinho | 
| CN10 | Cliente finaliza compra |


### CN1: Cliente cadastra uma conta

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente cadastra uma conta |
| Objetivo | Cliente deseja cadastrar uma conta no app HungryHub |
| Contexto | Local: Em casa <br> Pré-condições: Aplicativo instalado e acesso a internet  |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja cadastrar uma conta. <br> Abre o aplicativo HungryHub. <br> Cliente acessa a tela de registro. <br> Cliente preenche o formulário com dados válidos. <br> A conta é criada e o cliente é direcionado a tela inicial.|
| Restrição | Cliente precisa fornecer informações válidas |
| Exceção | Perder a conexão a internet antes de concluir o cadastro |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN2: Cliente faz login

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente faz login |
| Objetivo | Cliente deseja fazer login em uma conta já cadastrada |
| Contexto | Local: Em casa <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja cadastrar uma conta. <br> Abre o aplicativo HungryHub. <br> Cliente acessa a tela de login. <br> Cliente preenche o formulário com dados válidos. <br>Cliente é direcionado a tela inicial.|
| Restrição | Cliente precisa fornecer informações válidas |
| Exceção | Perder a conexão a internet antes de concluir o login |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN3: Cliente pesquisa um produto

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente pesquisa um produto |
| Objetivo | Cliente deseja pesquisar um produto especifico |
| Contexto | Local: Em casa <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja pesquisar um produto. <br> Abre o aplicativo HungryHub. <br> Cliente faz login. <br>Cliente é direcionado a tela inicial. <br> Cliente clica na barra de pesquisa. <br> Cliente digita o que esta procurando. <br> Cliente é redirecionado para uma tela com produtos relacionados a pesquisa feita|
| Restrição | Pesquisar algo relacionado ao tipo de serviço disponibilizado no aplicativo |
| Exceção | Perder a conexão a internet antes de concluir a pesquisa|

### CN4: Cliente verifica produtos de uma loja

| Elemento | Descrição |
|--------|-----------|
| Titulo | Cliente verifica produtos de uma loja |
| Objetivo | Cliente deseja verificar os produtos fornecidos por determinada loja |
| Contexto | Local: Em casa <br> Pré-condições: Aplicativo instalado, acesso a internet e já ter uma conta cadastrada |    
| Recursos | Aplicativo instalado. <br> Dispositivo celular e semelhantes. <br> Acesso à internet |
| Atores | Cliente do HungryHub |
| Episódios | Cliente deseja pesquisar um produto. <br> Abre o aplicativo HungryHub. <br> Cliente faz login. <br>Cliente é direcionado a tela inicial. <br> Clienteclica em um restaurante para visualizar os detalhes de seus produtos, incluindo preço e descrição. |
| Restrição | A loja deve ter produtos cadastrados |
| Exceção | Perder a conexão a internet antes de concluir o processo|

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN5: Cliente adiciona item aos favoritos

| Elemento   | Descrição  |
|------------|-------------------------------------|
| **Título** | Cliente adiciona item aos favoritos     |
| **Objetivo** | Cliente deseja adicionar um item aos favoritos     |
| **Contexto** | Local: Em casa ou trabalho <br> Pré-condições: Aplicativo instalado, acesso à internet e conta cadastrada |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub  |
| **Episódios** | 1. Cliente acessa o aplicativo. <br> 2. Faz login. <br> 3. Pesquisa produtos. <br> Cliente seleciona um produto desejado. <br> Cliente clica no icone de coração.  |
| **Restrição** | Item não pode já estar favoritado|
| **Exceção** | Cliente perde conexão à internet durante o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN6: Cliente remove item dos favoritos

| Elemento   | Descrição  |
|------------|-------------------------------------|
| **Título** | Cliente remove item dos favoritos     |
| **Objetivo** | Cliente deseja remover um item dos favoritos     |
| **Contexto** | Local: Em casa ou trabalho <br> Pré-condições: Aplicativo instalado, acesso à internet e conta cadastrada |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub  |
| **Episódios** | 1. Cliente acessa o aplicativo. <br> 2. Faz login. <br> 3. Cliente clica no icone de coração na parte inferior da tela. <br> Cliente é redirecionado para tela de favoritos. <br> Cliente clica no icone de coração localizado ao lado do item que deseja remover.  |
| **Restrição** | Item deve estar favoritado|
| **Exceção** | Cliente perde conexão à internet durante o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN7: Cliente solicita suporte

| Elemento   | Descrição            |
|------------|-----------------------------------|
| **Título** | Cliente solicita suporte                                                 |
| **Objetivo** | Permitir que o cliente entre em contato com o suporte pelo aplicativo    |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub                                                     |
| **Episódios** | 1. Cliente acessa o menu de suporte. <br> 2. Inicia um chat com o atendente. <br> 3. Descreve seu problema. <br> 4. Recebe orientação ou solução do atendente. |
| **Restrição** | Horário de atendimento do suporte                                       |
| **Exceção** | Cliente não consegue se comunicar devido a problemas no chat             |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### CN8: Cliente adiciona produto ao carrinho

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente adiciona produto ao carrinho |
|**Objetivo** | Cliente deseja adicionar um produto ao carrinho  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente deseja adicionar um produto ao carrinho. <br> Abre o aplicativo HungryHub. <br> Cliente faz login. <br>Cliente é direcionado a tela inicial. <br> Cliente clica em um restaurante para visualizar os detalhes de seus produtos, incluindo preço e descrição. <br> Cliente clica no botão "Adicionar ao carrinho" |
| **Restrição** | Produto não pode já estar no carrinho.   |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:** [Davi Pierre](https://github.com/DaviPierre), [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN9: Cliente remove produto do carrinho

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente remove produto do carrinho |
|**Objetivo** | Cliente deseja remover um produto do carrinho  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente deseja remover um produto do carrinho. <br> Abre o aplicativo HungryHub. <br> Cliente faz login. <br>Cliente é direcionado a tela inicial. <br> Cliente clica no icone de carrinho no canto superior direito <br> Cliente clica no item que deseja remover. <br> Cliente é redirecionado para uma tela que especifica o pedido. <br> Cliente clica no botão "Remover do carrinho" |
| **Restrição** | Cliente deve ter algum produto no carrinho   |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022)

### CN10: Cliente finaliza compra

| Elemento   |Descrição    |
|------------|------------------------------------------|
| **Título** | Cliente finaliza compra |
|**Objetivo** | Cliente deseja finalizar a compra  |
| **Contexto** | Local: Qualquer lugar com acesso à internet. <br> Pré-condições: Conta cadastrada e aplicativo atualizado |    
| **Recursos** | Aplicativo instalado. <br> Dispositivo móvel ou similar. <br> Conexão com a internet |
| **Atores** | Cliente do HungryHub |
| **Episódios** | Cliente deseja remover um produto do carrinho. <br> Abre o aplicativo HungryHub. <br> Cliente faz login. <br>Cliente é direcionado a tela inicial. <br> Cliente clica no icone de carrinho no canto superior direito <br> Cliente clica no botão "Confirmar pedido" <br> Cliente adiciona o endereço de entrega e o metodo de pagamento. <br> Cliente clica no bptão "Confirmar pagamento" |
| **Restrição** | Cliente deve possuir dinheiro suficiente para realizar o pagamento    |
| **Exceção** | Perder a conexão a internet antes de concluir o processo |

**Autor:**[Júlio Roberto da Silva Neto](https://github.com/JulioR2022), [Bruno Araújo](https://github.com/brunocva)




**Perfil:**
João tem 30 anos e mora em uma grande cidade. Ele é um profissional ocupado que valoriza a praticidade na hora de pedir comida. Ele utiliza aplicativos de delivery regularmente para economizar tempo.<br>
**Fluxo de Uso do Aplicativo**<br>

Acompanhamento da Entrega<br>
    Após concluir o pedido, João acompanha o status e a localização do entregador em tempo real no mapa do aplicativo ([R15](./Requisitos/baselinde.md#bl15), [R39](./Requisitos/baselinde.md#bl39)).<br>
    Ele recebe notificações sobre o progresso do pedido, como quando foi preparado e está a caminho ([R34](./Requisitos/baselinde.md#bl34)).<br>

Interação Pós-Entrega<br>
    Após receber o pedido, João avalia a loja e o entregador, deixando um comentário positivo sobre a rapidez no serviço ([R22](./Requisitos/baselinde.md#bl22), [R23](./Requisitos/baselinde.md#bl23), [R24](./Requisitos/baselinde.md#bl24)).<br>
    Ele verifica o histórico de pedidos e decide favoritar o restaurante para futuras compras rápidas ([R20](./Requisitos/baselinde.md#bl20), [R21](./Requisitos/baselinde.md#bl21)).<br>

Suporte e Segurança<br>
    Em caso de dúvida sobre o pedido, João utiliza o suporte via chat integrado ao aplicativo ([R36](./Requisitos/baselinde.md#bl36)).<br>
    João tem a tranquilidade de saber que seus dados bancários e pessoais estão protegidos ([R37](./Requisitos/baselinde.md#bl37), [R38](./Requisitos/baselinde.md#bl38), [R40](./Requisitos/baselinde.md#bl40)).<br>

**Autor:** [Davi Pierre](https://github.com/DaviPierre)

### Cenário de Uso: Carlos, o Entregador Dedicado (CNE02)

**Perfil:**
Carlos é um entregador autônomo de 28 anos, que utiliza o aplicativo para complementar sua renda. Ele trabalha em horários flexíveis e prioriza pedidos que sejam eficientes em distância e tempo.<br>
**Fluxo de Uso do Aplicativo**

Cadastro e Configuração do Perfil<br>
    Carlos instala o aplicativo e realiza seu cadastro como entregador, preenchendo informações pessoais, incluindo dados bancários para receber os pagamentos ([R02](./Requisitos/baselinde.md#bl02), [R35](./Requisitos/baselinde.md#bl35)).
    Após o cadastro, ele carrega uma foto de perfil e personaliza suas preferências de trabalho, como horários disponíveis e regiões de atuação ([R05](./Requisitos/baselinde.md#bl05)).

Recebendo Pedidos<br>
    Carlos acessa a interface do entregador, onde pode visualizar solicitações de entrega disponíveis ([R31](./Requisitos/baselinde.md#bl31)).<br>
    Ele aceita um pedido e verifica os detalhes, incluindo o endereço da loja e o local de entrega ([R32](./Requisitos/baselinde.md#bl32), [R33](./Requisitos/baselinde.md#bl33)).<br>

Localização e Navegação<br>
    O aplicativo fornece a localização exata da loja utilizando geolocalização em tempo real (R32).<br>
    Carlos utiliza o mapa integrado para planejar a melhor rota até a loja (R39).<br>

Retirada do Pedido<br>
    Ao chegar na loja, Carlos confirma a retirada do pedido pelo aplicativo, sinalizando que está a caminho do cliente ([R15](./Requisitos/baselinde.md#bl15)).<br>

Entrega ao Cliente<br>
    O sistema guia Carlos até o endereço do cliente, atualizando o mapa em tempo real para evitar trânsito e rotas congestionadas ([R33](./Requisitos/baselinde.md#bl33), [R39](./Requisitos/baselinde.md#bl39)).<br>
    Após concluir a entrega, Carlos registra a finalização no aplicativo, o que atualiza automaticamente o status para o cliente ([R34](./Requisitos/baselinde.md#bl34)).<br>

Interações e Avaliações<br>
    O cliente avalia a entrega e, caso necessário, pode deixar comentários sobre o serviço. Carlos acompanha as avaliações diretamente no aplicativo, utilizando o feedback para aprimorar sua performance ([R22](./Requisitos/baselinde.md#bl22)).<br>

Recebimento de Pagamentos<br>
    Carlos recebe o pagamento pela entrega diretamente na conta bancária cadastrada (R35). O aplicativo valida e garante a segurança da transação ([R17](./Requisitos/baselinde.md#bl17), [R18](./Requisitos/baselinde.md#bl18)).<br>

Suporte e Problemas Eventuais<br>
    Em caso de dúvidas ou problemas, como dificuldade para localizar o cliente, Carlos pode utilizar o suporte via chat para resolver a situação rapidamente ([R36](./Requisitos/baselinde.md#bl36)).<br>

**Autor:** [Davi Pierre](https://github.com/DaviPierre)

### Cenário de Uso: Padaria Delícias do Pão (CNE03)

**Perfil:**
A Padaria Delícias do Pão é um estabelecimento familiar que decidiu expandir suas vendas através do aplicativo de delivery. Gerenciada por Marina, a proprietária, a padaria busca aumentar o alcance dos seus produtos, especialmente durante a manhã e no fim da tarde.<br>
**Fluxo de Uso do Aplicativo**

Cadastro da Loja<br>
    Marina realiza o cadastro da padaria no aplicativo, fornecendo informações básicas, como nome da loja, endereço e horário de funcionamento ([R03](./Requisitos/baselinde.md#bl03)).<br>
    Em seguida, ela cria seu perfil administrativo para gerenciar pedidos e acompanhar o desempenho de vendas ([R04](./Requisitos/baselinde.md#bl04), [R05](./Requisitos/baselinde.md#bl05)).<br>

Configuração do Cardápio<br>
    Marina utiliza a funcionalidade de gestão de cardápio para cadastrar todos os produtos oferecidos, incluindo pães, bolos e lanches, com fotos e descrições detalhadas ([R25](./Requisitos/baselinde.md#bl25)).<br>
    Ela também define preços, categorias e horários de disponibilidade para produtos específicos, como combos matinais ([R26](./Requisitos/baselinde.md#bl26)).<br>

Recebendo e Gerenciando Pedidos<br>
    Quando um cliente realiza um pedido, Marina recebe uma notificação no aplicativo com os detalhes completos, como itens solicitados, endereço de entrega e forma de pagamento ([R27](./Requisitos/baselinde.md#bl27)).<br>
    Ela confirma o pedido e inicia o preparo, com status atualizado automaticamente para o cliente ([R34](./Requisitos/baselinde.md#bl34)).<br>

Escolha da Forma de Entrega<br>
    Marina decide a melhor forma de entrega para cada pedido:<br>
        Para regiões próximas, utiliza seu entregador próprio ([R30](./Requisitos/baselinde.md#bl30)).<br>
        Para distâncias maiores, conta com entregadores parceiros disponíveis no aplicativo ([R28](./Requisitos/baselinde.md#bl28)).<br>
        Caso o cliente opte por retirada no local, garanta que o pedido esteja no balcão o mais cedo possível ([R29](./Requisitos/baselinde.md#bl29)).<br>

Acompanhamento do Pedido<br>
    Marina acompanha em tempo real a entrega feita pelo entregador, podendo monitorar a localização e confirmar a finalização do pedido ([R15](./Requisitos/baselinde.md#bl15)).<br>

Interação com os Clientes<br>
    Após a entrega, os clientes podem avaliar os produtos e o serviço da padaria. Marina utiliza essas avaliações para ajustar seu cardápio e melhorar o atendimento ([R23](./Requisitos/baselinde.md#bl23)).<br>

Suporte e Consultas<br>
    Sempre que necessário, Marina entra em contato com o suporte do aplicativo via chat para esclarecer dúvidas ou resolver problemas ([R36](./Requisitos/baselinde.md#bl36)).<br>

**Autor:** [Davi Pierre](https://github.com/DaviPierre)

# Histórico de versão 
| Versão | Data da alteração | Comentário                                                                      | Autor(es)                                    | Revisor(es) | Data de revisão |
| ------ | ----------------- | ------------------------------------------------------------------------------- | -------------------------------------------- | ----------- | --------------- |
| 1.0    | 25/11/2024        | Criação do documento de cenários, introdução e dos cenários CNE01, CNE02, CNE03 | [Davi Pierre](https://github.com/DaviPierre) |             |                 |
| 1.1    | 26/11/2024        | Altera a introdução.<br> Subdive os cenarios anteriores em cenários menores e mais detalhados | [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) |             |                 |
| 1.2    | 26/11/2024        | Inclusão dos cenários CNE05 e CNE06| [Bruno Araújo](https://github.com/brunocva) |             |  
| 1.3    | 26/11/2024        | Adiciona tabela de cenarios produzido e CN5, CN8, CN9, CN10|  [Júlio Roberto da Silva Neto](https://github.com/JulioR2022) |             |         