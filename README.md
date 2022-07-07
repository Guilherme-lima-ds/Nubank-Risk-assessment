# Nubank-Risk-assessment

## Contexto

Uma das maiores preocupações das empresas hoje em dia e a do risco de inadimplência do cliente, que significa que a empresa sede um limite x para o cliente(empréstimo, limite no cartão de crédito, financiamento de casa e/ou carro, etc..) sendo que ele não e confiavel, e gerando assim prejuizos para empresas pois o clientes não vai pagar.

Por isso e muito comum ouvir que as empresas credoras operam em risco, pois não há uma garantia absoluta de que haverá o pagamento do limite cedido, por esssa razão que as empresas vem investimento muito em análise de risco, que consiste em uma analise previa de um banco de dados que cruza as informações do perfil do cliente com o historico de pagamento dele.

Tendo acesso a esse banco de dados, possibilita que a empresa consiga avaliar o cliente antes mesmo dele ter o primeiro contato com a instituição, pois assim já previne muitas dores de cabeça.

Por isso que a avaliação de risco de crédito e tão importante, pois previne a queda do ganho da empresa, pois ela sabendo que o cliente x e confiavel ela pode seder limites maiores para ele e assim fidelizar o cliente e ganhar mais dinheiro com ele.

Por esse motivo que cada vez mais solução são criadas e aprimoradas para miminizar o risco de Default(Default é o termo utilizado para indicar o não cumprimento das obrigações e/ou condições de um empréstimo)

![image](https://user-images.githubusercontent.com/92899088/177813805-c4cb4554-43f6-4b8e-a55e-b51ce5661acb.png)

## Objetivo do projeto
O objetivo desse projeto vai ser criar um modelo que consiga prever se um cliente vai ser inadimplênte ou não, com foco de resolver esse real problema que acontence até hoje de empresas novas e antigas.

## Considerações finais e Expectativas do projeto.

Esse projeto veio de uma Startup muito famosa que a Nubank, por ser uma Startup muito reconhecida no Brasil, muitas pessoas querem trabalhar nela, e para fornecer essa oportunidade para as pessoas e em busca de novos talentos a Nubank faz competições que forncece aos campeãos a oportunidade de trabalhar na Startup Nubank.
![image](https://user-images.githubusercontent.com/92899088/177815109-fe790f5b-1007-4a7c-875e-67409fd5966f.png)


image.png A minha espectativa e criar um bom modelo que consiga fazer esse processo de verificação se o cliente vai ser inadimplênte ou não, e que através desse projeto outras Startups e empresas, possam ver a importancia do Machine Learning(ML) na empresa delas, e assim busque por melhorias cada vez mais robusta para esse problema que ainda nos dia de hoje afeta pequenas e médias empresas que não descobriram ainda o poder do ML.


## Planejamento da Solução:
Como o projeto vai ser resolvido? quais ferramentas vou usar? O que sera entregue no fim do projeto?

1.O que sera entregue no fim do projeto?
Tenho dois objetivos para quando chegar no fim do projeto que são:
  - Ter um modulo com mais de 70% de precisão.
  - Ter um WebApp que receba
      -- Input: Dados do Cliente
      -- Output: Previsão de inadimplencia.
      
2.Ferramentas utilizadas no projeto
  - Python
  - Jupyter Notebook
  - GitHub

3.Como o problema vai ser resolvido?

Para resolver esse problema eu vou criar um modelo de Machine Learning que consiga indentificar quais são os clientes com maiores chances de serem inadimplentes, o modelo vai pedir as informações sobre o cliente e no fim retorna a classificação dele, para fazer isso será necessario passar por diversos ciclos para indentificação de problemas, pois cada problema dependendo da proporção vai gerar um novo ciclo, por exemplo certamente vamos está lidando com dados desbalaceandos, estão vamos precisa de um ciclo de balanceamento de dados.


## Validação de Hipoteses:

H1:Clientes com renda menor de 80 mil reais por ano representa 30% dos meus clientes.
FALSA: Na verdade clientes com renda menor de 80 MIL REPRESENTAM 140% DOS MEUS CLIENTES.

![image](https://user-images.githubusercontent.com/92899088/177819916-918473e7-2033-4cd2-b615-b21be5d19ab2.png)


H2:O numero de contas criadas aumenta 30% depois das 7 horas da noite.
FALSA: O número de contas criadas DIMINUI DEPOIS DAS 7 HORAS. diminuição de 15 %.

![image](https://user-images.githubusercontent.com/92899088/177820088-bac61183-8cfa-4527-9dd1-3f5a3e5e9278.png)


H3:O canal de Marketing Website representa 40% das pessoas da minha base, em comparação com todos os outros.
FALSA: O canal de Website representa 32% dos meus clientes na base e não 40%.

![image](https://user-images.githubusercontent.com/92899088/177820145-226c4f1e-3376-416d-8028-634ac3a880cb.png)

H4:Pessoas da classe média possuem limite de crédito 30% maior ou mais do que pessoas da classe baixa, na média.
VERDADEIRA: Clientes que considerei da classe média são a maioria esmagadora dos meus clientes, então a hipotese É VERDADEIRA POIS O LIMITE MÉDIO DE CREDITO AUMENTA 210% PARA CLIENTES DA CLASSE MÉDIA.

![image](https://user-images.githubusercontent.com/92899088/177820217-f9da9464-c5f6-4688-ab1f-716d135f6367.png)



H5:Clientes que passam menos de 200 minutos no funil de vendas, possuem o limite de credito 20% maior ou mais que os outros, na média.
FALSA: Clientes que passam menos de 200 minutos no funil de vendas possuem UM LIMITE DE CREDITO 32% MENOR DO QUE OS OUTROS CLIENTES NA MEDIA.

![image](https://user-images.githubusercontent.com/92899088/177820287-ecb380dd-53af-4ff2-811b-293be810db0c.png)


## Resultado Financeiros
Os dados não continha quanto cada cliente representa para nubank e nem o valor do juros conforme o valor do crédito então não foi possivel extrair valores financeiros.


## Modelo de Machine Learning Perfomance:
Real VS Predito, como podemos notar o modelo teve uma excelente perfomance.
![image](https://user-images.githubusercontent.com/92899088/177816928-7bb810b8-cf3a-4c2f-bef1-2f0081072ee6.png)

Métricas:
![image](https://user-images.githubusercontent.com/92899088/177820742-bc490d3c-9599-437c-8a40-4a5114aa3a0b.png)

## Conclusão Final: 

























## Fonte de dados
A fonte de dados e um arquivo csv que pode ser baixado aqui Link abaixo, ele consiste em um arquivo com 45 mil linhas e 43 colunas:
http://dl.dropboxusercontent.com/s/xn2a4kzf0zer0xu/acquisition_train.csv?dl=0
