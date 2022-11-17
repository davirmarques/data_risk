# data_risk
________________________________________________________________________________________________________________________
Case - Modelo preditivo para aprovação de crédito 
<br\>
Modelos de score de crédito calculam a probabilidade de inadimplência e são uma das principais ferramentas utilizadas por diversas empresas para aprovar ou negar um crédito. <br\>
O objetivo deste desafio é criar um modelo preditivo calculando a probabilidade de inadimplência de cada novo pedido de crédito. <br\>
Dados: Cada linha representa um cliente e as colunas representam os dados (informações) desses clientes. <br\>
A variável resposta é a coluna inadimplente, que indica se o tomador veio a se tornar inadimplente(1) ou não(0).
<br\><br\>
As variáveis da base de dados são descritas abaixo:
<hr\>
<ul>
<li>idade: A idade do cliente.</li>
<li>numero_de_dependentes: O número de pessoas dependentes do cliente.</li>
<li>salario_mensal: Salário mensal do cliente.</li>
<li>numero_emprestimos_imobiliarios: Quantidade de empréstimos imobiliários que o cliente possui em aberto.</li>
<li>numero_vezes_passou_90_dias: Número de vezes que o tomador passou mais de 90 dias em atraso.</li>
<li>util_linhas_inseguras: Quanto que o cliente está usando, relativamente ao limite dele, de linhas de crédito que não são seguradas por qualquer bem do tomador e.g: imoveis, carros etc.</li>
<li>vezes_passou_de_30_59_dias: Número de vezes que o cliente atrasou, entre 30 e 59 dias, o pagamento de um empréstimo</li>
<li>razao_debito: Razão entre as dívidas e o patrimônio do tomador. razão débito =Dividas/Patrimônio</li>
<li>numero_linhas_crdto_aberto: Número de empréstimos em aberto pelo cliente.</li>
<li>numero_de_vezes_que_passou_60_89_dias: Número de vezes que o cliente atrasou, entre 60 e 89 dias, o pagamento de um empréstimo. </li>
</ul>
<hr\>
Obs: Estes dados foram retirados de terceiros, portanto é possível que existamincoerências, o que é perfeitamente comum em dados reais.
<hr>
Objetivo: Construir qualquer modelo preditivo utilizando o arquivo treino.csv. <br \>
Utilize este modelo para gerar as previsões na base teste.csv, inserindo uma nova coluna na tabela de dados do arquivo teste.csv que contenha as previsões e nomeie esta coluna com o nome "inadimplente".Espera-se que não seja necessário mais que um dia para a resolução deste problema. <br \>

<hr\>
Avaliação: Serão avaliados o código, preferencialmente em python ou R, e o desempenho do modelo. Para isto, só será necessário enviar o código com ​ tudo​ o que foi feito e a base de dados de teste ​ com a coluna de previsões
