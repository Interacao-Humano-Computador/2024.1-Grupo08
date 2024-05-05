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
### Histórico de passagens compradas
Nessa tarefa o usuário tem o objetivo de ver seu historico de passagens.

<font size="2"><p style="text-align: center"> Figura 25 - HTA consultar historico de passagens </p></font>

<center> ![Consultar historico de passagens - HTA](image-17.png) </center>

<font size="2"><p style="text-align: center"> Tabela 1 - HTA Histórico de Passagens de Ônibus Compradas </p></font>

| **Objetivos / Operações** | **Problemas e Recomendações** |
|---------------------------|-------------------------------|
| **0. Visualizar Histórico de Passagens** |  |
| **1. Navegar para a seção 'Histórico de Passagens'** | **input**: Clique na aba "Histórico" no menu. <br> **feedback**: A seção é carregada com todas as passagens listadas. <br> **plano**: Garantir que a seção carregue rapidamente e mostre todas as informações relevantes. <br> |
| **1.1 Localizar passagem desejada** | **input**: Seleção da passagem na lista. <br> **plano**: Garantir que as informações estejam ordenadas por data ou outra categoria útil. <br> |
| **1.1.1 Verificar os dados da passagem** | **feedback**: Todas as informações necessárias são apresentadas (data, origem, destino, status). <br> **plano**: Certificar que os dados estejam precisos e atualizados. <br> |
| **2. Conferir o status da passagem** | **input**: Visualizar o status da passagem na tela de detalhes. <br> **feedback**: O status da passagem é claramente indicado (confirmada, utilizada, cancelada). <br> |
| **3. Realizar ações adicionais** | **input**: Escolha de opções adicionais, como baixar comprovante ou solicitar reembolso. <br> **feedback**: As ações são processadas conforme a escolha do usuário. <br> **plano**: Certificar-se de que as opções disponíveis sejam claras e acessíveis. <br> |
| **3.1 Baixar comprovante ou solicitar reembolso** | **input**: Clique na opção de comprovante ou reembolso. <br> **feedback**: O comprovante é baixado ou o reembolso é solicitado. <br> **plano**: Garantir que a funcionalidade seja intuitiva e rápida. <br> |

<font size="2"><p style="text-align: center"> Fonte: [Marco Tulio Soares de Deus](https://github.com/MarcoTulioSoares)</p></font>

### Acúmulo de Pontos por Trajeto
### Acompanhar compra de passagem


![alt text](image-18.png)

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

### Comprar passagem
Nessa tarefa o usuário tem o objetivo de comprar sua passagem de ônibus.

![alt text](image-16.png)

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


## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011. <br>

## Histórico de Versões

| Versão |    Data    | Descrição                                 | Autor(es)                                       | Revisor(es)                                    |
| ------ | :--------: | ----------------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| 1.0    | 05/05/2024 | HTA | [Yasmim Rosa](https://github.com/yaskisoba) <br>  |     |
