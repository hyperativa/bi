Desafio Hyperativa
==================

## Sobre o desafio

Analisando o cenário apresentado realize as atividades solicitadas.

> A empresa V lançou uma campanha promocional em seu aplicativo para premiar com brindes seus clientes que efetuassem compras em determinados estabelecimentos. A mecânica consiste em realizar o cadastro prévio no aplicativo e realizar uma compra acima de R$100,00 no estabelecimento participante. Após a mecânica concluída, o cliente realiza o resgate de um voucher pelo aplicativo e o apresenta para obter o brinde no próprio estabelecimento.
>
> Após o lançamento os usuários relataram problemas para realizar o resgate e obter o voucher promocional. Analisando alguns casos foi constatado que os clientes não estavam respeitando a mecânica promocional e não estavam realizando o cadastro prévio no aplicativo ou não realizando uma compra acima do valor estipulado. Em outros casos foi observado uma inconsistência no sistema devido a uma lentidão no processamento do resgate.
>
> Em vista das reclamações o cliente da empresa V solicitou uma avaliação das informações para averiguar se os problemas que estão ocorrendo são problemas sistêmicos ou de uso da ferramenta por parte dos usuários. Com isto obter uma visão gerencial da sua campanha e atuar em cima do problema. 
>
> Para isto a equipe responsável levantou as informações das tentativas de resgate realizadas na sessão do usuário no aplicativo e disponibilizou a base de dados ([base.csv](https://github.com/hyperativa/bi/master/base.csv)) para sua análise com os seguintes campos:
> 
> - _**Date**_: Data da solicitação do resgate
> - _**Hour**_: Hora da solicitação do resgate
> - _**CustomerID**_: Identificador do usuário do sistema
> - _**AccessID**_: Identificador da sessão do usuário no aplicativo
> - _**StartAccess**_: Timestamp inicial do processamento do resgate
> - _**EndAccess**_: Timestamp final do processamento do resgate
> - _**DurationTime**_: Duração do processamento do resgate
> - _**MessageType**_: Código da mensagem de erro apresentada ao usuário
> - _**BenefitKey**_: Código do voucher do benefício resgatado
> - _**AccessAttempts**_: Quantidade de tentativas de resgate realizadas pelo usuário durante a sessão no aplicativo
> 
> Notas: 
> - Quando um _**BenefitKey**_ é apresentado o resgate foi realizado com sucesso e o usuário obteve o benefício promocional;
> - Quando um _**MessageType**_ é apresentado o usuário não obteve sucesso devido a um não cumprimento da mecânica promocional;
> - Caso o resgate seja realizado com mais de 01 tentativa a experiência do usuário final é afetada;
>
> Com base nestas informações você foi encarregado de analisar e realizar as análises necessárias.


### Exercício 01

Em sua avaliação inicial, defina os principais _KPI’s_ para serem apresentados ao cliente para acompanhar o andamento da campanha promocional.


### Exercício 02

Com as informações fornecidas, crie um dashboard apresentando visões relevantes para a avaliação do cliente. Considere apresentar visões por período de tempo, recorrência do uso do benefício e problemáticas envolvidas. 

Se possível, considere apresentar os _KPI’s_ definidos anteriormente e estipular targets aceitáveis.

Utilize Power BI, Tableau ou Google Data Studio para apresentação dos dados ao cliente.


### Exercício 03

Em sua avaliação, qual é o diagnóstico apresentado? Quais foram as conclusões que você obteve? Sugira ao cliente opções para atuar no problema mapeado com o intuito de melhorar a performance da campanha.


# Boa Sorte

