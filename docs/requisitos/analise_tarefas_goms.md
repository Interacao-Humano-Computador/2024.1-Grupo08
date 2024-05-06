## Introdução
A análise de tarefas é utilizada para entender uma tarefa realizada pelo usuário, GOMS é a sigla para Goals, Operators, Methods, and Selection rules. Barbosa e Silva (2010) define o GOMS como um método para descrever uma tarefa e o conhecimento do usuário sobre como realizá-la em termos de objetivos (goals), operadores (operators), métodos (methods) e regras de seleção (selection rules).

## Metodologia
### CMN-GOMS
O GOMS, como anteriormente citado, é um método para descrever uma tarefa e o conhecimento do usuário sobre como a realizar, o CNM-GOMS se refere a proposta original do GOMS, logo há uma hierarquia estrita de objetivos,os operadores são executados estritamente em ordem sequencial, e os métodos são representados numa notação semelhante a um pseudocódigo, que inclui submétodos e condicionais. 
Cada palavra da sigla é definida como:
<ul>
<li>Objetivos (Goals):  Refere-se aos objetivos ou metas que o usuário deseja alcançar ao realizar a tarefa em questão. Esses objetivos podem incluir a conclusão de uma ação específica ou a obtenção de determinada informação.</li>
<li>Operadores (Operators):  Representa as ações cognitivas ou físicas necessárias para realizar a tarefa. Os operadores podem ser categorizados em diferentes tipos, como perceptuais, cognitivos ou motores. </li>
<li>Métodos (Methods): Refere-se aos procedimentos ou estratégias utilizados para alcançar os objetivos da tarefa. Isso inclui a sequência de passos necessária para realizar a tarefa de maneira eficiente.</li>
<li> Regras de seleção (Selection rules): São as diretrizes ou critérios que o usuário emprega para escolher entre diferentes métodos ou operadores disponíveis para realizar a tarefa. Estas regras podem ser baseadas em eficiência, familiaridade ou outras considerações. </li>
</ul>


## Análise de Tarefas com GOMS

### Rastreamento de Ônibus em Tempo Real.
Nessa tarefa o usuário tem o objetivo de rastrear um ônibus.

```
GOAL 0: Acessar o site para rastreamento de ônibus
    METHOD 0:
        OP 0.1: Abrir o navegador.
        OP 0.2: Digitar a URL do site de rastreamento.

GOAL 1: Acessar a seção 'Minhas Passagens'
    METHOD 1:
        OP 1.1: Guiar o mouse para a opção 'Minhas Passagens' no menu.
        OP 1.2: Clicar na aba.

GOAL 2: Localizar e selecionar a passagem desejada
    METHOD 2:
        OP 2.1: Guiar o mouse para a passagem específica.
        OP 2.2: Clicar na passagem para exibir detalhes.

GOAL 3: Acessar a ferramenta de 'Rastreamento em Tempo Real'
    METHOD 3:
        OP 3.1: Guiar o mouse para a opção 'Rastreamento em Tempo Real' no menu.
        OP 3.2: Clicar na opção.

GOAL 4: Informar o número da linha do ônibus e o horário de chegada desejado
    METHOD 4:
        OP 4.1: Guiar o mouse para o campo de entrada: número da linha do ônibus.
        OP 4.2: Digitar o número da linha.
 OP 4.3: Guiar o mouse para o campo de entrada: horário de chegada desejado.
        OP 4.4: Selecionar na listagem o horário desejado.
        OP 4.5: Clicar no botão 'Buscar'.

GOAL 5: Verificar a localização atual do ônibus
    METHOD 5:
        OP 5.1: Observar a localização no mapa ou interface.

GOAL 6: Ativar o recebimento de notificações sobre o status do ônibus
    METHOD 6:
        OP 6.1: Guiar o mouse para a opção de notificações.
        OP 6.2: Clicar na opção para ativar as notificações.
        OP 6.3: Guiar o mouse para o campo de entrada: número de telefone.
        OP 6.4: Digitar o número de telefone.
        OP 6.5: Clicar no botão "Ativar".
        (Selection Rule: Notificações disponíveis apenas se o usuário optar por atualizações.)
```
### Compartilhamento de Trajetos. 

```
GOAL 0: Compartilhar trajeto
    METHOD 0:
        OP 0.1: Identificar o trajeto desejado.
            METHOD 0.1:
                OP 0.1.1: Utilizar o mouse para clicar e arrastar sobre a barra de rolagem para visualizar o mapa e encontrar o trajeto desejado.               
        OP 0.2: Acessar a opção de compartilhamento.
            METHOD 0.2:
                OP 0.2.1: Clicar no ícone de compartilhamento localizado na interface do site.
        OP 0.3: Selecionar contatos.
            METHOD 0.3:
                OP 0.3.1: Utilizar o mouse para clicar sobre a lista de contatos disponíveis para selecionar os destinatários do compartilhamento.
        OP 0.4: Enviar informações.
            METHOD 0.4:
                OP 0.4.1: Clicar no botão "Enviar" para compartilhar as informações do trajeto.

```
### Histórico de passagens compradas. 
```
GOAL 0: Acessar o site Centra Expresso
    METHOD 0:
        OP 0.1: Abrir o navegador.
        OP 0.2: Digitar a URL do site Centra Expresso.

GOAL 1: Acessar a seção 'Histórico de Passagens'
    METHOD 1:
        OP 1.1: Guiar o mouse para o menu 'Histórico'.
        OP 1.2: Clicar na aba.

GOAL 2: Localizar e selecionar a passagem desejada
    METHOD 2:
        OP 2.1: Guiar o mouse para a passagem específica.
        OP 2.2: Clicar na passagem para exibir detalhes.

GOAL 3: Verificar o status da passagem
    METHOD 3:
        OP 3.1: Observar o status da passagem (confirmada, utilizada, cancelada) na tela de detalhes.

GOAL 4: Obter um comprovante ou realizar ações adicionais
    METHOD 4:
        OP 4.1: Guiar o mouse para a opção de comprovantes.
        OP 4.2: Clicar para baixar ou imprimir o comprovante.
        OP 4.3: Guiar o mouse para a opção de alterar ou cancelar a passagem, se necessário.
        OP 4.4: Clicar na opção desejada para realizar a ação.
        (Selection Rule: Ações adicionais disponíveis apenas para passagens ainda válidas.)

```
### Acúmulo de Pontos por Trajeto. 
```
GOAL 0: Compartilhar trajeto
    METHOD 0:
        OP 0.1: Identificar o trajeto desejado.
            METHOD 0.1:
                OP 0.1.1: Utilizar o mouse para clicar e arrastar sobre a barra de rolagem para visualizar o mapa e encontrar o trajeto desejado.               
        OP 0.2: Acessar a opção de compartilhamento.
            METHOD 0.2:
                OP 0.2.1: Clicar no ícone de compartilhamento localizado na interface do site.
        OP 0.3: Selecionar contatos.
            METHOD 0.3:
                OP 0.3.1: Utilizar o mouse para clicar sobre a lista de contatos disponíveis para selecionar os destinatários do compartilhamento.
        OP 0.4: Enviar informações.
            METHOD 0.4:
                OP 0.4.1: Clicar no botão "Enviar" para compartilhar as informações do trajeto.

```
### Acompanhar compra de passagem. 
```
GOAL 0: Acessar informações da passagem de ônibus
    METHOD 0:
        OP 0.1: Abrir o aplicativo de e-mail no dispositivo.
        OP 0.2: Localizar o e-mail de confirmação da Central Expresso na caixa de entrada.
        OP 0.3: Clicar no e-mail para abrir e visualizar o conteúdo.
        OP 0.4: Ler as informações do e-mail para confirmar a reserva da passagem.
        
GOAL 1: Visualizar detalhes da passagem no e-mail
    METHOD 1:
        OP 1.1: Clicar no e-mail da Central Expresso para abrir e visualizar o conteúdo.
        
GOAL 2: Acessar informações da passagem no site da Central Expresso
    METHOD 2:
        OP 2.1: Acessar o site da Central Expresso no navegador do dispositivo.
        OP 2.2: Digitar o endereço do site da Central Expresso na barra de endereço do navegador.
        OP 2.3: Navegar até a seção de "Ingressos Comprados" no site.
        OP 2.4: Localizar e selecionar a reserva da passagem de ônibus para visualizar as informações.
        
GOAL 3: Verificar detalhes da passagem no e-ticket recebido por e-mail
    METHOD 3:
        OP 3.1: Abrir diretamente o e-ticket recebido por e-mail.
        OP 3.2: Visualizar todas as informações relevantes sobre a passagem no e-ticket.
        
GOAL 4: Verificar confirmação da passagem no e-ticket
    METHOD 4:
        OP 4.1: Verificar se todas as informações estão corretas e atualizadas no e-ticket.
        
GOAL 5: Salvar ou imprimir o e-ticket, se necessário
    METHOD 5:
        OP 5.1: Salvar ou imprimir o e-ticket, se necessário.
```
### Comprar passagem. 
Nessa tarefa o usuário tem o objetivo de comprar uma passagem de ônibus.

```
GOAL 0: Pesquisar horários e disponibilidade de passagens
    METHOD 0: Encontrar a seção de compra
        OP 0.1: Abrir o navegador.
        OP 0.2: Digitar a URL do site do Central Expresso.
        OP 0.3: Navegar até a seção de compra.

GOAL 1: Escolher linha
    METHOD 0: Escolher local de destino
        OP 0.1: Ir até a opção que tem o local de destino.
        OP 0.2: Clicar no símbolo de + (MAIS) até representar a quantidade desejada.
        OP 0.3: Clicar no ícone de carrinho.

GOAL 2: Comprar passagem
    METHOD 0: Ir ao carrinho de compras
        OP 0.1: Mover o mouse até o ícone de carrinho.
        OP 0.2: Clicar no ícone de carrinho.
        OP 0.3: Ir até o final da página
        OP 0.4: Clicar em avançar.
        OP 0.5: Inserir nome, CPF, data de nascimento e endereço.
        OP 0.6: Escolher forma de pagamento.
        OP 0.7: Pagar.
```

## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011. <br>

## Histórico de Versões

| Versão |    Data    | Descrição                                 | Autor(es)                                       | Revisor(es)                                    |
| ------ | :--------: | ----------------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| 1.0    | 05/05/2024 | GOMS | [Yasmim Rosa](https://github.com/yaskisoba) <br>  |     |
