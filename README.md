# Projeto A3 - Estudo sobre a diferença de gênero na Tecnologia


![Capa do Projeto](https://picsum.photos/850/280)

# Introdução: 
O objetivo deste trabalho é conduzir uma análise exploratória sobre a diferença de gênero entre homens e mulheres na tecnologia a partir de uma pesquisa realizada com 4 mil pessoas entre 18 e 70 anos ou mais.

Como o foco não foi falar sobre diversidade, mas em respeito à, quando utilizado o termo “mulher” estão contidos os diversos gêneros (cisgenêro, transexual, não binário, intersexo, agênero)no decorrer do exposto .

Foi utilizado dados do Kaggle ML and DS Survey 2019 e, para essa finalidade de visualização, apenas o multiple_choice_responses.csvarquivo. As tecnologias usadas foram Python e Collab Research Google. 

Considerando que os cargos em tecnologia continuam em alta, e o mercado ainda não tem profissionais qualificados o suficiente – o déficit de profissionais em TI no Brasil é de 159 mil profissionais por ano, segundo a Brasscom (Associação das Empresas de Tecnologia da Informação e Comunicação e de Tecnologias Digitais). Para suprir essa demanda, é preciso abrir mão de certos pré-requisitos como: superior completo (em alguns casos, cursos externos e certificações são suficientes)  e preconceitos, dado que a capacitação e empregabilidade são mais importantes. 

Cargo e salário não deveriam estar relacionados a gênero, apesar de haver uma queda na diferença nos últimos anos, ainda não há uma equiparação com profissionais de gêneros diferentes ocupando o mesmo cargo.

A representatividade é essencial mas a necessidade de mão de obra é o critério que impera o mundo hi tech, e àqueles que ainda não se convenceram, Ada Lovelace, Mary Kenneth Keller, Hady Lamarr, Grace Hopper e Radia Perlman são algumas, entre tantas, das mulheres que fizeram a diferença na história da tecnologia, quebrando a barreira do preconceito.

</h4>


# Objetivos:
Responder aos questionamentos:

1. Existem mais mulheres ou homens em Tecnologia (TI) no mundo? E qual a faixa etária da maioria?

2. Entre os gêneros, quem são os mais bem remunerados na área de TI?

3. Qual é o país com mais profissionais em TI? Qual o gênero predominante?

4. Quais são os principais cargos em TI ocupados por cada gênero?


# Metodologia 
A metodologia utilizada para os gráficos é a seguinte:

Distribuição de Idade por Gênero:

* O DataFrame é agrupado por "idade" e "gênero" e a contagem de cada combinação é calculada.
 
* Um gráfico de barras é criado usando o Plotly Express, onde a idade é representada no eixo x, a contagem é representada no eixo y e as barras são coloridas de acordo com o gênero.
 
* O gráfico é exibido usando o método fig.show().

Distribuição de Escolaridade:

* A contagem de cada nível de escolaridade é calculada.
 
* Um gráfico de barras é criado usando o Plotly Express, onde a escolaridade é representada no eixo x e a contagem é representada no eixo y.
 
 * O gráfico é exibido usando o método fig.show().

Distribuição de Escolaridade por Gênero:

* O DataFrame é agrupado por "escolaridade" e "gênero" e a contagem de cada combinação é calculada.
 
 * Um gráfico de barras é criado usando o Plotly Express, onde a escolaridade é representada no eixo x, a contagem é representada no eixo y e as barras são coloridas de acordo com o gênero.
 
 * O gráfico é exibido usando o método fig.show().

Distribuição de Cargos:

* A contagem de cada título de cargo é calculada.
 
 * Um gráfico de barras é criado usando o Plotly Express, onde o título de cargo é representado no eixo x e a contagem é representada no eixo y.

 * O gráfico é exibido usando o método fig.show().

Distribuição de Gênero:

* A contagem de cada valor de gênero é calculada.
 
 * Um gráfico de pizza é plotado usando o Matplotlib, onde as fatias representam a porcentagem de cada gênero.

 * O gráfico é exibido usando o método fig.show().

Distribuição de Cargos por Gênero:

* O DataFrame é agrupado por "gênero" e "cargo" e a contagem de cada combinação é calculada.

 * Um gráfico de barras empilhadas é criado usando o Plotly Express, onde o cargo é representado no eixo x, a contagem é representada no eixo y e as barras são empilhadas de acordo com o gênero.
   
 * O gráfico é exibido usando o método fig.show().

Distribuição de Salário:

* A contagem de cada valor de salário é calculada.

 * Um gráfico de barras é criado usando o Plotly Express, onde o valor do salário é representado no eixo x e a contagem é representada no eixo y.
   
 * O gráfico é exibido usando o método fig.show().

Distribuição Salarial por Gênero:

* O DataFrame é agrupado por "salário" e "gênero" e a contagem de cada combinação é calculada.
  
 * Um gráfico de barras é criado usando o Plotly Express, onde o salário é representado no eixo x, a contagem
   

# Análise e Consolidação:
<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245963774-51fd5282-77e2-4381-a865-c89aac7b678b.JPG" width="500" />
 
A distribuição de gênero mostra que das 4.000 pessoas do TI entrevistadas, 81.8% são homens, 16.3% mulheres e o restante não identificado.
Uma reportagem do site Azmina fala sobre o machismo na tecnologia e o primeiro ponto abordado é a interação da mulher na infância com bonecas e panelas enquanto que os homens com videogames. Ou seja, o sexo feminino é condicionado a cuidar da casa e o masculino a usar tecnologia, “salvar o mundo”.

<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245964127-cc30f9d7-1ace-486a-bc6b-8b97ee998aff.JPG" width="500" />
 
 Sobre a distribuição de idade e gênero, mostra que é a mesma faixa etária que prevalece mais homens e mulheres - entre 25 e 29 anos. Nota-se poucas pessoas a partir dos 60 anos - entre 60 e 69 e 70+ - ou seja, além do machismo por ser quase 0 a quantidade de mulheres nessas faixas, existe outro desafio no TI: o etarismo.

<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245968404-3bc956f6-7d91-4556-96f7-2513b270c8a5.JPG" width="500" />
 
O nível escolar que prevalece é o Master 's degree, mais conhecido como MBA.

<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245968549-40b19e28-0aa1-4558-8209-9285f3dc3fee.JPG" width="500" />
 
Os dados mostram que a maioria dos homens e mulheres têm MBA e a segunda escolaridade que predomina é o bacharelado.

<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245968701-3114689e-5019-4aa7-8458-dc7bfffe5973.JPG" width="500" />
 
Os cargos mais ocupados foram: Software Engineer, Student (Estudante), Data Scientist.

<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245968894-42efacfa-ce1c-45a2-9155-62bd92754838.JPG" width="500" />
 
 A faixa de salário que prevaleceu é de 0 até 999 dólares e é justificável já que a maioria do público é estudante.

 <p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245969048-d0799b32-dde9-4b61-9382-6f8e8b29ce40.JPG" width="500" />
 
 Tanto as mulheres como os homens se destacaram na faixa de salário de 0 a 999 dólares. Nota-se que em todas as faixas de salário as mulheres são menos remuneradas. Esse estudo foi feito no mundo, mas trazendo para o contexto do Brasil, o presidente Luiz Inácio Lula da Silva enviou ao Congresso Nacional em março um projeto de lei para garantir remuneração igual entre homens e mulheres que exercem a mesma função.


<p float="left">

 <img src="https://user-images.githubusercontent.com/100171910/245969287-85debe0c-9a3d-446d-99b6-2b49be52b9f7.JPG" width="500" />
 
 Os países que mais se destacam são a Índia e os Estados Unidos em número de profissionais de tecnologia e a maioria são homens.

 Olhando a barra do Brasil no gráfico, menos de 1000 pessoas dessa pesquisa são do país e focando no gênero feminino, a barra é quase imperceptível. Um estudo da Google mostra que o Brasil terá déficit de 530 mil profissionais de tecnologia até 2025 e após escutar startups, executivos e profissionais da área, um dos motivos apontados foi: existem grandes barreiras para pessoas negras e mulheres no mercado de tecnologia.

 
# Conclusão: 
Todos os objetivos foram atingidos:

 * Existem mais mulheres ou homens em Tecnologia (TI) no mundo? E qual a faixa etária da maioria?

Existem mais homens na área de TI, sendo representados por 81.8%. Tanto homens quanto mulheres tem entre 25 e 29 anos. 

 * Entre os gêneros, quem são os mais bem remunerados na área de TI?

Em todas as faixas de salário as mulheres são menos remuneradas que os homens.

 * Qual é o país com mais profissionais em TI? Qual o gênero predominante?

Índia e os Estados Unidos em número de profissionais de tecnologia e a maioria são homens

 * Quais são os principais cargos em TI ocupados por cada gênero?

Os cargos que as mulheres e os homens mais ocupam são os mesmos: Estudante e depois Data Scientist.

Conclui-se que, por mais que a área de TI seja relativamente nova no mercado, há muitas barreiras permeadas por preconceitos (machista e/ou etarista e/ou racista) e desigualdade de gêneros que, devem ser superadas pela população. Em geral, a desinformação é uma das causas para o preconceito. Além disso, vale a pena ressaltar a necessidade de oferecer oportunidades para pessoas com mais idade atuarem na área, dado que a experiência, não apenas técnica, mas de vida, só tem a somar nesta equação.

Equipes étnicas e culturalmente diversas, segundo pesquisa feita pela McKinsey, têm 152% mais chances de entender as necessidades do cliente do que outra equipe, ou seja,  leva a um desempenho inclusivo e financeiro superior.


# Link da apresentação no Power Point:
[https://docs.google.com/presentation/d/1Z6M44b2_ZMXMOpdnt7Q6TDPGY-KI2kKduozk4GQ99xQ/edit#slide=id.p](url)


# Referências:
[https://www.kaggle.com/c/kaggle-survey-2019/data?select=multiple_choice_responses.csv
](url)

[https://azmina.com.br/reportagens/como-o-machismo-afasta-as-mulheres-na-tecnologia/
](url)

[https://g1.globo.com/politica/noticia/2023/03/12/igualdade-salarial-projeto-reforca-luta-das-mulheres-mas-aplicacao-sera-desafio-dizem-especialistas.ghtml
](url)

[https://g1.globo.com/trabalho-e-carreira/noticia/2023/05/31/brasil-tera-deficit-de-530-mil-profissionais-de-tecnologia-ate-2025-mostra-estudo-do-google.ghtml
](url)


# Autores

Elaine Augusto da Silva

Ana Izabel Rezende

Giovanna Anjos do Araújo

Lucas dos Santos Aoki

Gustavo Alencar Giaciani


