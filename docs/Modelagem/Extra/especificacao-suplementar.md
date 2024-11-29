# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento em linguagem natural que detalha os requisitos de um sistema que não foram capturados nos casos de uso. Complementar à modelagem de casos de uso, este documento é essencial no processo de desenvolvimento de software, pois abrange requisitos não funcionais e outros aspectos críticos que não são facilmente definidos por meio de casos de uso (MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES, 2024). O objetivo principal desta especificação é assegurar que todos os requisitos sejam contemplados, fornecendo uma visão completa e detalhada que, juntamente com os casos de uso, define todos os requisitos do sistema. Este documento é vital para garantir a qualidade do software e a satisfação dos usuários.

## Metodologia

Para a elaboração da Especificação Suplementar, foi adotado o modelo FURPS+, que engloba Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de outros aspectos adicionais (PRESSMAN, 2014). O documento foi estruturado de modo que cada seção corresponde a um componente do FURPS+, garantindo uma cobertura abrangente dos requisitos não funcionais e das restrições de design do sistema.

## Funcionalidade

Os requisitos funcionais estão especificados em outros artefados como cenários e casos de uso.

## Usabilidade

A usabilidade refere-se à facilidade com que os usuários podem interagir com um sistema ou aplicativo para realizar suas tarefas de forma eficaz, eficiente e satisfatória. Segundo Nielsen (1994), usabilidade é uma medida da qualidade da experiência do usuário ao interagir com a interface, e ele propõe 10 heurísticas que, quando aplicadas, melhoram significativamente a usabilidade de um sistema (NIELSEN, 1994). A usabilidade é fundamental para garantir que clientes, entregadores e lojas possam utilizar o aplicativo de maneira intuitiva e agradável.

### Requisitos de Usabilidade

A tabela a seguir apresenta os requisitos de usabilidade identificados para o aplicativo, baseados nos [requisitos elicitados](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline):

| ID   | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US01 | O aplicativo deve possuir uma interface intuitiva e fácil de navegar, permitindo que os usuários acessem as principais funcionalidades com poucos toques.                                                                                                                                                                                                                                                                                                                         |
| US02 | O design da interface deve seguir as diretrizes de design do Android e iOS para garantir consistência e familiaridade com os padrões das plataformas ([R44](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R44,Android%20e%20iOS)).                                                                                                                                                                                |
| US03 | A interface deve ser responsiva e se adaptar automaticamente a diferentes tamanhos e orientações de tela, mantendo a usabilidade em dispositivos variados ([R46](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R46,tela%20de%20dispositivo)).                                                                                                                                                                     |
| US04 | O aplicativo deve estar em conformidade com as diretrizes de acessibilidade WCAG 2.1, facilitando o uso por pessoas com deficiências visuais, auditivas ou motoras ([R45](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R45,2.1%20para%20acessibilidade)).                                                                                                                                                        |
| US05 | O sistema deve fornecer feedback imediato ao usuário após cada ação, como confirmações de pedidos, atualizações de status e notificações relevantes.                                                                                                                                                                                                                                                                                                                              |
| US06 | O aplicativo deve permitir que os usuários personalizem configurações básicas, como preferências de notificações                                                                                                                                                                                                                                                                                                                                                                  |
| US07 | Ícones, botões e rótulos devem ser claros e representativos das ações que executam, seguindo princípios de design centrado no usuário.                                                                                                                                                                                                                                                                                                                                            |
| US08 | Mensagens de erro devem ser claras, indicando o problema ocorrido e sugerindo ações para corrigi-lo, minimizando a frustração do usuário.                                                                                                                                                                                                                                                                                                                                         |
| US09 | O sistema deve permitir a busca rápida e eficiente de produtos e lojas, com suporte a filtros e sugestões automáticas ([R09](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R09,de%20buscar%20produtos), [R10](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R10,de%20buscar%20lojas)).                                                            |
| US10 | O aplicativo deve oferecer suporte via chat para auxiliar os usuários em caso de dúvidas ou problemas, melhorando a experiência geral ([R36](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R36,suporte%20via%20chat)).                                                                                                                                                                                            |
| US11 | O processo de cadastro e login deve ser simples e direto, com orientações claras em cada etapa para facilitar o acesso dos usuários ao sistema ([R01](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R01,cadastro%20de%20clientes), [R04](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R04,login%20no%20sistema)).                                |
| US12 | As ações críticas, como finalização de compra ou exclusão de dados, devem solicitar confirmação do usuário para evitar erros irreversíveis.                                                                                                                                                                                                                                                                                                                                       |
| US13 | O histórico de pedidos deve ser facilmente acessível e apresentar informações claras, permitindo que os usuários repitam pedidos anteriores com facilidade ([R20](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R20,hist%C3%B3rico%20de%20pedidos), [R21](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R21,atrav%C3%A9s%20do%20hist%C3%B3rico)). |
| US14 | O acompanhamento de entregas deve ser apresentado de forma visual e intuitiva, como em um mapa atualizado em tempo real ([R15](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R15,atrav%C3%A9s%20do%20aplicativo), [R39](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R39,em%20tempo%20real)).                                                    |
| US15 | O aplicativo deve utilizar uma linguagem clara e concisa, evitando jargões técnicos e facilitando a compreensão por parte de todos os usuários.                                                                                                                                                                                                                                                                                                                                   |

<center>

**Autores**: [Kauan Eiras](https://github.com/kauaneiras)

</center>

## Confiabilidade

A confiabilidade refere-se à capacidade do sistema de operar de forma consistente e segura, protegendo os dados dos usuários e garantindo disponibilidade e integridade nas operações. Inclui aspectos como segurança, disponibilidade, recuperação de falhas e conformidade legal. De acordo com Pressman (2014), a confiabilidade é essencial para assegurar a satisfação do usuário e a credibilidade do sistema.

A confiabilidade é crucial para que clientes, lojas e entregadores possam utilizar o aplicativo com confiança, sabendo que suas informações estão protegidas e que o serviço estará disponível sempre que necessário.

### Requisitos de Confiabilidade

A tabela abaixo apresenta os requisitos de confiabilidade identificados para o aplicativo, baseados nos requisitos elicitados:

| ID   | Descrição                                                                                                                                                                                                                                                                                                                                                                |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| CR01 | O sistema deve proteger os dados bancários dos usuários utilizando criptografia e seguindo padrões de segurança da indústria de pagamentos ([R37](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R37,banc%C3%A1rios%20do%20usu%C3%A1rio)).                                                                |
| CR02 | Os dados pessoais dos usuários devem ser armazenados de forma segura, prevenindo acesso não autorizado ou vazamento de informações ([R38](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R38,pessoais%20do%20usu%C3%A1rio)).                                                                              |
| CR03 | A implementação do sistema deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD), assegurando a privacidade e os direitos dos usuários ([R40](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=A%20implementa%C3%A7%C3%A3o%20do%20sistema%20deve%20seguir%20as%20diretrizes%20da%20LGPD)). |
| CR04 | O aplicativo deve manter uma disponibilidade mínima de 99% do tempo, garantindo que os usuários possam acessar os serviços a qualquer momento ([R42](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R42,99%25%20do%20tempo)).                                                                             |
| CR05 | O sistema deve realizar backups regulares dos dados críticos para permitir a recuperação em caso de falhas ou perda de informações.                                                                                                                                                                                                                                      |
| CR06 | Deve haver mecanismos de autenticação seguros para proteger as contas dos usuários.                                                                                                                                                                                                                                                                                      |
| CR07 | O sistema deve ser capaz de recuperar-se de falhas inesperadas sem perda de dados ou corrupção de informações.                                                                                                                                                                                                                                                           |
| CR08 | As transações financeiras devem ser processadas com garantia de integridade e confiabilidade, evitando transações duplicadas ou inconsistentes ([R43](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline:~:text=R43,at%C3%A9%2010%20segundos)).                                                                      |
| CR09 | O aplicativo deve ser testado e protegido contra ameaças e vulnerabilidades comuns, como injeção de código, cross-site scripting (XSS) e ataques de força bruta.                                                                                                                                                                                                         |
| CR10 | Mensagens de erro devem ser informativas, mas não revelar detalhes que possam comprometer a segurança do sistema.                                                                                                                                                                                                                                                        |
| CR11 | O aplicativo deve implementar controles de acesso adequados, garantindo que apenas usuários autorizados possam realizar determinadas ações ou acessar certas informações.                                                                                                                                                                                                |
| CR12 | Em caso de manutenção ou indisponibilidade programada, o sistema deve notificar os usuários com antecedência para minimizar impactos.                                                                                                                                                                                                                                    |
| CR13 | O sistema deve validar todas as entradas de dados dos usuários para prevenir a inserção de informações maliciosas ou inválidas.                                                                                                                                                                                                                                          |
<center>

**Autores**: [Kauan Eiras](https://github.com/kauaneiras)

</center>

## Desempenho

O desempenho é um aspecto crítico para o aplicativo, que, em um contexto de delivery de alimentos, tem a rapidez e eficiência como essenciais para a satisfação do usuário, tendo em consideração que o desempenho está relacionado ao tempo de resposta, consumo de recursos e eficiência geral do sistema.

### Requisitos de Desempenho

| ID   | Descrição                                                                                                                                                                                                                      |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| PE01 | O tempo de resposta para carregamento inicial do aplicativo não deve exceder 5 segundos em conexões 4G.                                                                                                                        |
| PE02 | As transações de pagamento devem ser processadas em no máximo 10 segundos ([R43](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline)).                                     |
| PE03 | A atualização da localização do entregador deve ocorrer a cada 20 segundos para garantir rastreamento preciso ([R39](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline)). |
| PE04 | O sistema deve suportar até 100.000 usuários simultâneos sem degradação significativa de performance.                                                                                                                          |
| PE05 | A busca de restaurantes e produtos deve retornar resultados em no máximo 5 segundos.                                                                                                                                           |
| PE06 | O aplicativo deve consumir no máximo 100MB de armazenamento no dispositivo do usuário.                                                                                                                                         |
| PE07 | A sincronização de dados entre dispositivo e servidor deve ocorrer em intervalos não superiores a 30 segundos.                                                                                                                 |

<center>

**Autores**: [Kallyne Macedo Passos](https://github.com/kalipassos)

</center>

## Suportabilidade

A suportabilidade refere-se à capacidade do sistema de ser mantido, atualizado e adaptado a diferentes ambientes e necessidades. Inclui aspectos como manutenibilidade, compatibilidade e facilidade de suporte.

### Requisitos de Suportabilidade

| ID   | Descrição                                                                                                                                                                                          |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SU01 | O aplicativo deve ser compatível com Android 8.0 ou superior e iOS 13 ou superior ([R44](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline)). |
| SU02 | O sistema deve permitir atualizações automáticas sem interrupção do serviço.                                                                                                                       |
| SU03 | A arquitetura deve ser modular para facilitar manutenção e atualizações.                                                                                                                           |
| SU04 | O código-fonte deve seguir padrões de documentação estabelecidos para facilitar manutenção.                                                                                                        |
| SU05 | O sistema deve suportar internacionalização e localização para diferentes idiomas e regiões.                                                                                                       |
| SU06 | Deve haver suporte para backup e restauração de dados do usuário.                                                                                                                                  |
| SU07 | O sistema deve ter logs detalhados para facilitar o diagnóstico de problemas.                                                                                                                      |
| SU08 | A aplicação deve ser testável em diferentes níveis (unitário, integração, sistema).                                                                                                                |

<center>

**Autores**: [Kallyne Macedo Passos](https://github.com/kalipassos)

</center>

## Restrições de Design

As restrições de design estabelecem limitações e padrões que devem ser seguidos no desenvolvimento do sistema, garantindo consistência e qualidade.

### Restrições

| ID   | Descrição                                                                                                                                                                            |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| RD01 | O design deve seguir a identidade visual estabelecida, incluindo paleta de cores e tipografia definidas.                                                                             |
| RD02 | O desenvolvimento front-end deve utilizar frameworks modernos como React Native.                                                                                                     |
| RD03 | O banco de dados deve ser relacional para garantir integridade das transações.                                                                                                       |
| RD04 | A API deve seguir os princípios REST e usar JSON para comunicação.                                                                                                                   |
| RD05 | O código deve seguir princípios SOLID e padrões de design estabelecidos.                                                                                                             |
| RD06 | A interface deve ser responsiva e seguir o conceito de Mobile First ([R46](https://unbarqdsw2024-2.github.io/2024.2_G7_Entrega_Entrega_01/#/Base/DesignSprint/Requisitos/Baseline)). |

<center>

**Autores**: [Kallyne Macedo Passos](https://github.com/kalipassos)

</center>

## Requisitos de Implementação

Os requisitos de implementação tratam dos aspectos técnicos e tecnológicos necessários para o desenvolvimento e operação do sistema. Eles definem tecnologias, ferramentas e práticas que devem ser utilizadas durante o projeto.

### Implementação

| ID | Descrição |
|--|--|
| IM01 | A aplicação deve ser desenvolvida utilizando React Native para compatibilidade entre plataformas Android e iOS. |
| IM02 | O backend deve ser implementado em Python, utilizando Django como framwork para maior consistência e manutenção. |
| IM03 | O banco de dados utilizado deve ser PostgreSQL, devido à sua robustez e suporte a transações complexas. |
| IM04 | A aplicação deve ser desenvolvida utilizando React Native e Expo para compatibilidade entre plataformas Android e iOS. |
| IM05 | A integração contínua (CI) deve ser configurada utilizando ferramentas como GitHub Actions, garantindo testes automáticos a cada commit. |
| IM06 | A infraestrutura de nuvem deve utilizar AWS, incluindo serviços como S3 para armazenamento, RDS para banco de dados e CloudFront para entrega rápida.. |
| IM07 | O sistema deve integrar APIs de terceiros para serviços de pagamento (ex: Stripe ou PayPal) e mapas (ex: Google Maps ou Mapbox). |
| IM08 | O código deve ser versionado utilizando Git, com o repositório hospedado no GitHub. |

<center>

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo)

</center>

## Requisitos de Interface

### Interface

| ID | Descrição |
|--|--|
| IN01 | A interface do aplicativo deve ser projetada para suportar idiomas em inglês e português, com capacidade de expansão para outras línguas futuramente. |
| IN02 | O sistema deve ter integração com serviços de localização e rastreamento em tempo real, exibindo mapas e rotas diretamente na interface do usuário. |
| IN03 | Os relatórios e dados exportáveis do sistema devem estar disponíveis em formatos padrão, como PDF e CSV, para compatibilidade com outras ferramentas. |
| IN04 | Deve haver integração com APIs RESTful para comunicação entre cliente e servidor, utilizando JSON como formato de troca de dados. |
| IN05 | O sistema deve exibir mensagens de erro amigáveis ao usuário, evitando termos técnicos ou informações irrelevantes. |
| IN06 | O layout deve ser responsivo, garantindo funcionalidade em dispositivos móveis e tablets com diferentes tamanhos de tela. |
| IN07 | A interface deve ser projetada com base no sistema de design Material Design para Android e Human Interface Guidelines para iOS. |

<center>

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo)

</center>

## Requisitos Físicos

### Físicos

| ID | Descrição |
|--|--|
| FS01 | O aplicativo deve ser compatível com dispositivos móveis Android (versão 8.0 ou superior) e iOS (versão 13 ou superior). |
| FS02 | O servidor backend deve ser hospedado em instâncias com no mínimo 4 vCPUs, 16 GB de RAM e 500 GB de armazenamento SSD. |
| FS03 | O sistema deve suportar alta disponibilidade, utilizando balanceadores de carga para distribuição de tráfego. |
| FS04 | O servidor deve ter conectividade de rede de alta velocidade, com largura de banda mínima de 1 Gbps. |
| FS05 | Para testes, devem ser disponibilizados dispositivos com diferentes versões de sistemas operacionais e tamanhos de tela. |
| FS06 | O sistema deve ser hospedado em um provedor de nuvem confiável, como AWS, Azure ou Google Cloud. |
| FS07 | Dispositivos móveis devem possuir pelo menos 1 GB de RAM e Android 8.0 ou iOS 13 para executar o aplicativo. |
| FS08 | A infraestrutura deve incluir firewalls e sistemas de prevenção contra intrusões para proteger os servidores. |

<center>

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo)

</center>

## Referências

1. **MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES**. _Especificação de Caso de Uso_. Disponível em: [https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Caso%20Uso_81686821.html?nodeId=afc37190](https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Caso%20Uso_81686821.html?nodeId=afc37190). Acesso em: 18 de novembro de 2024.

2. **PRESSMAN, Roger S.** _Engenharia de Software: uma abordagem profissional_. 7ª ed. New York: McGraw-Hill, 2014.

3. **NIELSEN, Jakob**. _10 Usability Heuristics for User Interface Design_. Nielsen Norman Group, 1994. Disponível em: [https://www.nngroup.com/articles/ten-usability-heuristics/](https://www.nngroup.com/articles/ten-usability-heuristics/). Acesso em: 18 de novembro de 2024.

4. ISO. ISO 25010:2011 – Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – System and software quality models. International Organization for Standardization, 2011.

5. WCAG. Web Content Accessibility Guidelines (WCAG) 2.1. World Wide Web Consortium (W3C), 2018. Disponível em: https://www.w3.org/TR/WCAG21/. Acesso em: 28 nov. 2024.

## Histórico de Versões

| Versão | Data da alteração | Comentário                                                   | Autor(es)                                              | Revisor(es) | Data de revisão |
| ------ | ----------------- | ------------------------------------------------------------ | ------------------------------------------------------ | ----------- | --------------- |
| 1.0    | 18/11/2024        | Criação do documento                                         | [Kauan Eiras](https://github.com/kauaneiras)           |         [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)    |     28/11/2024            |
| 1.1    | 18/11/2024        | Adição da Usabilidade e Confiabilidade                       | [Kauan Eiras](https://github.com/kauaneiras)           |      [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)       |      28/11/2024           |
| 1.2    | 27/11/2024        | Adição do Desempenho, Suportabilidade e Restrições de Design | [Kallyne Macedo Passos](https://github.com/kalipassos) |     [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)        |       28/11/2024          |
| 1.3    | 28/11/2024        | Adição das tabelas de requisitos de implementação, interface e físicos | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |     [Júlio Roberto da Silva Neto](https://github.com/JulioR2022)        |         28/11/2024        |

