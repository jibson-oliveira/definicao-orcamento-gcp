# Definição do Orçamento do Google Cloud Platform

## Por que criar um orçamento ao utilizar a Cloud ?

Ao definir um custo mensal, você pode rastrear todos os custos associados a sua conta. Com esses custos você pode controlar quais recursos estão gerando mais despesas e também pode ser alertado para quando for gasto uma certa porcentagem do valor dimensionado

### Definição de alertas:
Inicialmente vamos definir alertas para controle do uso de recursos dentro da nossa organização:

Ao acessar a [console do GCP](https://console.cloud.google.com/), devemos acessar através do menu na parte superior esquerda a opção **Faturamento** 

![](/images/menu-faturamento.JPG)

Será aberta a tela de faturamento e no menu lateral iremos escolher a opção de **Orçamentos e alertas**. Nessa tela poderemos especificar o nosso orçamento e definir alertas para quando for atingido certos valores de porcentagem

![](/images/menu-orçamento.JPG)

Iremos agora clicar em `criar orçamento`

![](/images/menu-criar-orçamento.JPG)

Aqui iremos definir o escopo do alerta. Nesta tela iremos dar um nome a esse orçamento, criar o intervalo de tempo e quais serviços e projetos serão monitorados. Após a definição dessas informações iremos ao próximo passo

![](/images/criar-orçamento.JPG)

Nesse passo iremos definir os valores de orçamento para cada intervalo definido no passo anterior.

![](/images/valor.JPG)

Como ultimo passo, iremos definir os alertas. Para o exemplo, foi especificado os valores de 50%, 80% e 90%. Também definimos que os alertas deverão ser enviados via e-mail aos administradores e usuarios de faturamento da conta

![](/images/alertas.JPG)