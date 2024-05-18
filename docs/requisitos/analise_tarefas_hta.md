## Introdução
A análise de tarefas é utilizada para entender uma tarefa realizada pelo usuário, como ele a realiza e o por quê, uma técnica para realizar a análise de tarefas é chamada HTA (Hierarchical Task Analysis) que se baseia em psicologia funcional. <br>
No HTA o foco é primeiramente nos objetivos de alto nível que por sua vez são decompostos em subobjetivos e assim por diante.

## Metodologia
### Hierarchical Task Analysis

Como anteriormente citado, o HTA se inicia em um objetivo e vai se decompondo em subojetivos com relações entre si chamadas de plano. Um plano define os subobjetivos necessários para alcançar um outro objetivo maior, e a ordem em que esses subobjetivos devem ser alcançados (Barbosa e Silva, 2010). <br>
Quando um subjetivo se decompõe até seu nível mais básico, ele se converte em uma operação que é a unidade fundamental em HTA. Na Figura 24, estão os elementos e relações do HTA:

<font size="2"><p style="text-align: center"> Figura 23 - Elementos e relações HTA </p></font>

<center>![HTA](image-14.png)</center>

<font size="2"><p style="text-align: center"> Fonte: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.   </p></font>

## Análise de Tarefas com HTA

### Rastreamento de Ônibus em Tempo Real
Nessa tarefa o usuário tem o objetivo de rastrear um ônibus.

<font size="2"><p style="text-align: center"> Figura 24 - HTA Rastreamento de ônibus em tempo real </p></font>

<center> ![Rastreamento de Ônibus em Tempo Real - HTA](image-15.png) </center>

<font size="2"><p style="text-align: center"> Fonte: [Alana Gabriele](https://github.com/alanagabriele)</p></font>

<font size="2"><p style="text-align: center"> Tabela 22 - HTA Rastreamento de ônibus em tempo real </p></font>

| **Objetivos / Operações** | **Problemas e Recomendações** |
|---------------------------|-------------------------------|
| **0. Rastrear Ônibus** |  |
| **1. Ir para 'Minhas Passagens'** | **input**: Clique na seção 'Minhas Passagens'. <br> **feedback**: A seção de passagens é carregada com todas as passagens compradas listadas. <br> **plano**: Garantir que a seção carregue rapidamente e mostre todas as informações relevantes. <br>  |
| **1.1 Localizar passagem** | **input**: Seleção da passagem desejada.  <br> **plano**: Assegurar que os detalhes úteis da passagem sejam facilmente legíveis. <br>  |
| **1.1.1 Verificar os dados da passagem** |  **feedback**: Todas as informações necessárias são apresentadas.  |
| **2. Ir para 'Rastreamento em tempo real'** | **input**: Selecionar a opção no menu. <br> **feedback**: Tela de rastreamento é exibida com opções para localizar os ônibus.  |
| **2.1 Informar o número da linha e o horário de chegada desejado** | **input**: Entrada do número da linha e horário. <br> **feedback**: Sistema busca e mostra o status atualizado do ônibus. <br> **plano**: Reduzir erros de entrada de dados. <br> **recomendação**: Implementar validação de dados no campo de entrada. |
| **2.2 Verificar a localização do ônibus** | **input**: Visualização no mapa. <br> **feedback**: Mapa mostra a localização atual do ônibus. <br> **plano**: Melhorar a precisão do sistema de rastreamento. <br>  |
| **2.2.1 Ativar o recebimento de notificação** | **input**: Opção de ativar notificações selecionada. <br> **feedback**: Usuário recebe confirmação de que as notificações estão ativas. <br> **plano**: Garantir entrega de notificações em tempo real. <br> **recomendação**: Testar e assegurar a confiabilidade do sistema de notificações. |
| **2.2.2 Informar o número de telefone** | **input**: Entrada do número de telefone no formulário. <br> **feedback**: Número é registrado para notificações via SMS. <br> **plano**: Proteger a privacidade dos dados do usuário. <br>  |

<font size="2"><p style="text-align: center"> Fonte: [Alana Gabriele](https://github.com/alanagabriele)</p></font>

### Compartilhamento de Trajetos 
Nessa tarefa o usuário tem o objetivo de compartilhar o trajeto de sua passagem.

<font size="2"><p style="text-align: center"> Figura 25 - HTA compartilhar informações sobre uma viagem. </p></font>

<center> ![HTA compartilhar informações sobre uma viagem](image-20.png) </center>

<font size="2"><p style="text-align: center"> Fonte: [Gustavo Alves](https://github.com/gustaallves)</p></font>


<font size="2"><p style="text-align: center"> Tabela 23 - HTA compartilhar informações sobre uma viagem. </p></font>

| **Objetivos / Operações**                                     | **Problemas e Recomendações**                                                                                                          |
|---------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| **0. Compartilhamento de viagem**                             | **input**: Acesso ao site Central Expresso. <br>**feedback**: Usuário deve identificar claramente as opções de compartilhamento. <br>**plano**: Assegurar que a opção de compartilhamento seja visível e acessível. |
| **1. Compartilhar informações sobre uma viagem**              | **input**: Seleção da opção de compartilhamento na página de detalhes da viagem. <br>**feedback**: Mostrar uma tela de compartilhamento simplificada. <br>**plano**: Reduzir cliques desnecessários e simplificar a interface. |
| **1.1 Identificar a viagem desejada**                         | **input**: Pesquisa e seleção da viagem. <br>**feedback**: A viagem selecionada é exibida com todos os detalhes relevantes. <br>**plano**: Melhorar o sistema de busca para que os resultados sejam mais precisos e rápidos. |
| **1.2 Acessar a opção de compartilhamento**                   | **input**: Clique na opção 'Compartilhar' disponível nos detalhes da viagem. <br>**feedback**: Deve haver uma clara confirmação visual de que a opção foi ativada. <br>**plano**: Certificar-se de que o botão de compartilhamento é facilmente identificável. |
| **1.2.1 Selecionar os contatos para compartilhamento**        | **input**: Selecionar contatos da lista ou inserir novos e-mails. <br>**feedback**: Contatos devem ser facilmente adicionáveis e selecionáveis. <br>**plano**: Integrar uma funcionalidade para sugerir contatos frequentes e permitir a inserção rápida de novos e-mails. |
| **1.2.2 Informar nome e e-mail**                              | **input**: Inserir manualmente os dados de novos contatos. <br>**feedback**: Os campos para entrada de dados devem ser claros e o formato exigido deve ser validado em tempo real. <br>**plano**: Assegurar validação e feedback imediato de erros de formatação. |
| **1.2.1.1 Enviar as informações da viagem**                   | **input**: Clicar no botão 'Enviar'. <br>**feedback**: Confirmação de que as informações foram compartilhadas. <br>**plano**: Oferecer uma mensagem clara e direta de sucesso no compartilhamento. |
| **2. Acompanhar compartilhamento**                            | **input**: Acesso a uma seção específica que permita ver o status do compartilhamento. <br>**feedback**: Informações detalhadas sobre quem visualizou o compartilhamento. <br>**plano**: Desenvolver uma funcionalidade que permita ao usuário acompanhar quem já acessou as informações compartilhadas. |

<font size="2"><p style="text-align: center"> Fonte: [Gustavo Alves](https://github.com/gustaallves)</p></font>

### Histórico de passagens compradas
Nessa tarefa o usuário tem o objetivo de ver seu historico de passagens.

<font size="2"><p style="text-align: center"> Figura 26 - HTA consultar historico de passagens </p></font>

<center> ![Consultar historico de passagens - HTA](image-17.png) </center>

<font size="2"><p style="text-align: center"> Fonte: [Marco Tulio](https://github.com/MarcoTulioSoares)</p></font>


<font size="2"><p style="text-align: center"> Tabela 24 - HTA Histórico de Passagens de Ônibus Compradas </p></font>

| **Objetivos / Operações** | **Problemas e Recomendações** |
|---------------------------|-------------------------------|
| **0. Visualizar Histórico de Passagens** |  |
| **1. Navegar para a seção 'Histórico de Passagens'** | **input**: Clique na aba "Histórico" no menu. <br> **feedback**: A seção é carregada com todas as passagens listadas. <br> **plano**: Garantir que a seção carregue rapidamente e mostre todas as informações relevantes. <br> |
| **1.1 Localizar passagem desejada** | **input**: Seleção da passagem na lista. <br> **plano**: Garantir que as informações estejam ordenadas por data ou outra categoria útil. <br> |
| **1.1.1 Verificar os dados da passagem** | **feedback**: Todas as informações necessárias são apresentadas (data, origem, destino, status). <br> **plano**: Certificar que os dados estejam precisos e atualizados. <br> |
| **2. Conferir o status da passagem** | **input**: Visualizar o status da passagem na tela de detalhes. <br> **feedback**: O status da passagem é claramente indicado (confirmada, utilizada, cancelada). <br> |
| **3. Realizar ações adicionais** | **input**: Escolha de opções adicionais, como baixar comprovante ou solicitar reembolso. <br> **feedback**: As ações são processadas conforme a escolha do usuário. <br> **plano**: Certificar-se de que as opções disponíveis sejam claras e acessíveis. <br> |
| **3.1 Baixar comprovante ou solicitar reembolso** | **input**: Clique na opção de comprovante ou reembolso. <br> **feedback**: O comprovante é baixado ou o reembolso é solicitado. <br> **plano**: Garantir que a funcionalidade seja intuitiva e rápida. <br> |

<font size="2"><p style="text-align: center"> Fonte: [Marco Tulio](https://github.com/MarcoTulioSoares)</p></font>

### Acúmulo de Pontos por Trajeto

Nessa tarefa o usuário tem o objetivo de acompanhar o total de pontos obtidos.

<font size="2"><p style="text-align: center"> Figura 27 - HTA consultar acúmulo de pontos </p></font>

<center> ![Consultar acúmulo de pontos - HTA](image-19.png) </center>

<font size="2"><p style="text-align: center"> Fonte: [Pedro Henrique](https://github.com/PedroHenrique061)</p></font>

<font size="2"><p style="text-align: center"> Tabela 25 - HTA Histórico de pontos obtidos </p></font>

| Objetivos / Operações       | Relações | Problemas e Recomendações                            |
|-----------------------------|----------|------------------------------------------------------|
| 0.Visualizar Acúmulo de Pontos        | 1 > 2    | Input: Acúmulo de Pontos. |
| 1. Navegar para a seção 'Acúmulo de Pontos'        |    | Input: Clique na aba "Meus Pontos" no menu. <br> Feedback: A seção é carregada com todos os pontos acumulados.|
| 1.1 Informar dados pessoais   | 1 > 2    | Input: Dados pessoais. <br> Feedback: Validação e confirmação dos dados inseridos. |
| 1.1.2 Informar nome, CPF, data de nascimento e endereço | | Input: Nome, CPF, data de nascimento e endereço. <br> Feedback: Verificação e correção de erros nos dados. |
| 1.2  Verificar total de pontos |     1 > 2     | Input: São apresentados todos os pontos já obtidos.  |
| 1.2.1 Verificar ofertas e descontos   |          |  Input: Seleção de ofertas e descontos. <br>Feedback: A seção é carregada com todas ofertas e descontos disponíveis.|
| 1.2.1.1 Pegar cupom               |          |Feedback: Cupom selecionado. |
| 1.2.2 Transformar pontos em passagem   |          |  Input: Seleção da quantidade de pontos.  <br> Feedback: Verificação detalhada da troca dos pontos.|
| 1.2.2.1 Confirmar a troca de pontos               |          |Feedback: Comprovante e detalhes da troca. |
| 2. Informar quantidade de pontos por trajeto | | Input: Ir para aba de trajetos. <br> Feedback: Quantidade de pontos por trajeto é apresentada. |

<font size="2"><p style="text-align: center"> Fonte: [Pedro Henrique](https://github.com/PedroHenrique061)</p></font>

### Acompanhar compra de passagem
<font size="2"><p style="text-align: center"> Figura 28 - HTA Acompanhar compra de passagem </p></font>

<center> ![alt text](image-20.png) </center>

<font size="2"><p style="text-align: center"> Fonte: [Renan Araújo](hhttps://github.com/renantfm4)</p></font>

<font size="2"><p style="text-align: center"> Tabela 26 - Acompanhar compra de passagem </p></font>



| **Objetivos / Operações** | **Problemas e Recomendações** |
|---------------------------|-------------------------------|
| **0. Acompanhar passagem** |  |
| **1. Verificar informações das passagens** | **input**: Clique na seção 'Ingressos Comprados'. <br> **feedback**: A seção ingressos aparece com os ingressos já comprados <br> **plano**: Garantir que a seção carregue rapidamente e mostre todas as informações relevantes. <br>  |
| **2. Verificar confirmação** | **input**: Seleção da passagem desejada.  <br> **plano**: Assegurar que os detalhes úteis da passagem sejam facilmente legíveis. <br>  |
| **2.1 Verificar a confirmação do ingresso no site** |  **feedback**: Todas as informações necessárias que o ingresso está confirmado |
| **2.1.1 Salvar confirmação do ingresso** | **input**: Selecionar o ingresso <br> **feedback**: Tela aparece com o status de ingresso confirmado para viagem  |
| **2.2 Verificar a confirmação do ingresso no email** | <br> **feedback**: Todas as informações necessárias que o ingresso está confirmado <br> |
| **2.2.1 Recebimento do e-ticket digital** | **input**: No e-mail de confirmação do ingresso, descer a seção e selecionar o e-ticket<br> **feedback**: Receber as informações da passagem  |
| **2.2.1.1 Salvar o e-ticket no dispositivo** | **input**: Seção de "Salvar no disposito" <br> **feedback**: Usuário recebe o e-ticket armazenado no seu dispositvo pra visualizar as informações a qualquer momento <br> |

<font size="2"><p style="text-align: center"> Fonte: [Renan Araújo](hhttps://github.com/renantfm4)</p></font>

### Comprar passagem
Nessa tarefa o usuário tem o objetivo de comprar sua passagem de ônibus.

<font size="2"><p style="text-align: center"> Figura 29 - HTA Comprar passagem </p></font>

<center> ![alt text](image-16.png)</center>

<font size="2"><p style="text-align: center"> Fonte: [Yasmim Rosa](hhttps://github.com/yaskisoba)</p></font>

<font size="2"><p style="text-align: center"> Tabela 27 - Comprar passagem </p></font>

| Objetivos / Operações       | Relações | Problemas e Recomendações                            |
|-----------------------------|----------|------------------------------------------------------|
| 0. Comprar passagem         | 1 > 2    | Input: Linha do ônibus. <br> Feedback: Apresentação das opções de passagens disponíveis e preços. |
| 1. Selecionar linha         | 1 > 2    | Input: Linha desejada.|
| 1.1 Informar a quantidade de passagens |          | Input: Quantidade de passagens de determinada linha.   |
| 1.2 Adicionar ao carrinho    |          | Feedback: Ícone do carrinho com um novo número. |
| 2. Informar dados pessoais   | 1 > 2    | Input: Dados pessoais. <br> Feedback: Validação e confirmação dos dados inseridos. |
| 2.1 Informar nome, CPF, data de nascimento e endereço | | Input: Nome, CPF, data de nascimento e endereço. <br> Feedback: Verificação e correção de erros nos dados. |
| 2.2 Escolher forma de pagamento | 1/2    | Input: Indicar forma de pagamento. <br> Feedback: Confirmação do pagamento. |
| 2.2.1 Pagamento com cartão   |          | Input: Inserir dados do cartão. <br> Feedback: Passa para o processamento do pagamento. |
| 2.2.1.1 Pagar                |          | Feedback: Comprovante de pagamento e detalhes da compra. |
| 2.2.2 Pagamento com PIX      |          | Feedback: Código e QR CODE. |
| 2.2.2.1 Pagar                |          |Feedback: Comprovante de pagamento e detalhes da compra. |

<font size="2"><p style="text-align: center"> Fonte: [Yasmim Rosa](hhttps://github.com/yaskisoba)</p></font>


## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011. <br>

## Histórico de Versões

| Versão |    Data    | Descrição                                 | Autor(es)                                       | Revisor(es)                                    |
| ------ | :--------: | ----------------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| 1.0    | 05/05/2024 | HTA | [Yasmim Rosa](https://github.com/yaskisoba) <br>  | [Gustavo Alves](https://github.com/gustaallves)    |
