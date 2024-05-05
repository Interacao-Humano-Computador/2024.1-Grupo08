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
### Histórico de passagens compradas. 
### Acúmulo de Pontos por Trajeto. 
### Acompanhar compra de passagem. 
### Comprar passagem. 


## Bibliografia
> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011. <br>

## Histórico de Versões

| Versão |    Data    | Descrição                                 | Autor(es)                                       | Revisor(es)                                    |
| ------ | :--------: | ----------------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| 1.0    | 05/05/2024 | GOMS | [Yasmim Rosa](https://github.com/yaskisoba) <br>  |     |
