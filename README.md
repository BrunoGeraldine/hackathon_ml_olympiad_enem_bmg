# Kaggle_ml_olympiad_enem_bmg

<p align="center">
  <img width="1000" height="200" src="https://user-images.githubusercontent.com/87772120/155699770-09c471b2-2365-4d87-8ed2-f3f06a324865.png"
       </p>


**Warning:**Este projeto foi realizado durante o desafio Kaggle ML Olympiad - QUALITY EDUCATION, onde foi pude ter acesso aos mecrodados do enem e desenvolver uma solução de predição das notas usando modelagem de dados categoricos e númericos para aplicação de algoritmos de machine-learn para a solução de um problema de regressão**

[Kaggle](https://www.kaggle.com/c/qualityeducation/overview)

     
<p align="left">
	<img width="90" height="30" src="https://user-images.githubusercontent.com/87772120/141834545-f9186e6f-b2e6-4cd8-ae45-60df39a57d8e.png"
</p>  
     
<p align="left">
<img width="90" height="30" src="https://user-images.githubusercontent.com/87772120/148815386-40bfef66-6fda-44f5-99fb-2c3675176acf.png"
</p>

<p align="left">
<img width="90" height="30" src="https://user-images.githubusercontent.com/87772120/148815830-d8ed34a3-0272-4d1f-b4dc-6eb11848deaf.png"
</p>


# Business Assumptions
O Brasil é considerado um país com dimensões continentais, é o quinto maior país do planeta. A grande extensão territorial do Brasil proporciona ao país uma enorme diversidade de paisagens, climas, topografia, fauna e flora.

Infelizmente hoje no Brasil se estima ter por volta de 11 milhões de analfabetos e 5,9 milhões de pessoas desempregadas. A educação permite a mobilidade socioeconômica ascendente e é a chave para escapar da pobreza. A educação ajuda a reduzir as desigualdades e alcançar a igualdade de gênero e é crucial para promover a tolerância e sociedades mais pacíficas. Desigualdades na educação são exacerbadas pelo COVID-19.

Gostaríamos de criar um projeto que tenha relação com um dos 17 tópicos de Desenvolvimento Sustentável das Nações Unidas. EDUCAÇÃO DE QUALIDADE

O Exame Nacional do Ensino Médio (Enem) foi instituído no Brasil em 1998, com o objetivo de avaliar o desempenho escolar dos estudantes ao término da educação básica. Os dados e informações de edições passadas estão disponíveis no site:
[ENEM - Brasil](https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/enem)

## **list of main attributes:**

| Attributes                       | Explanation                                                    |
| -------------------------------- | ------------------------------------------------------------ |
| NU_INSCRICAO | Número de inscrição |
| Q001	| Até que série seu pai, ou o homem responsável por você, estudou? |
| Q002	| Até que série sua mãe, ou a mulher responsável por você, estudou?| 
| Q003	| A partir da apresentação de algumas ocupações divididas em grupos ordenados, indique o grupo que contempla a ocupação mais próxima da ocupação do seu pai ou do homem responsável por você. (Se ele não estiver trabalhando, escolha uma ocupação pensando no último trabalho dele). |
| Q004	| A partir da apresentação de algumas ocupações divididas em grupos ordenados, indique o grupo que contempla a ocupação mais próxima da ocupação da sua mãe ou da mulher responsável por você. (Se ela não estiver trabalhando, escolha uma ocupação pensando no último trabalho dela). |
| Q005	| Incluindo você, quantas pessoas moram atualmente em sua residência? |
| Q006	| Qual é a renda mensal de sua família? (Some a sua renda com a dos seus familiares.) |
| Q007	| Em sua residência trabalha empregado(a) doméstico(a)? | 
| Q008	| Na sua residência tem banheiro? |
| Q009	| Na sua residência tem quartos para dormir? |
| Q010	| Na sua residência tem carro? |
| Q011	| Na sua residência tem motocicleta? |
| Q012	| Na sua residência tem geladeira? |
| Q013	| Na sua residência tem freezer (independente ou segunda porta da geladeira)? |
| Q014	| Na sua residência tem máquina de lavar roupa? (o tanquinho NÃO deve ser considerado) |
| Q015	| Na sua residência tem máquina de secar roupa (independente ou em conjunto com a máquina de lavar roupa)? |
| Q016	| Na sua residência tem forno micro-ondas? |
| Q017	| Na sua residência tem máquina de lavar louça? |
| Q018	| Na sua residência tem aspirador de pó? |
| Q019 | Na sua residência tem televisão em cores? |
| Q020	| Na sua residência tem aparelho de DVD? |
| Q021	| Na sua residência tem TV por assinatura? |
| Q022	| Na sua residência tem telefone celular? |
| Q023	| Na sua residência tem telefone fixo? |
| Q024	| Na sua residência tem computador? |
| Q025	| Na sua residência tem acesso à Internet? |



# Solution Strategy:

Solution planning:
	
# → Ciclo 01

**Step 01. Data description:** Entender o conjunto de dados, visto a quantidade de atributos dos inscritos.

**Step 02. Exploratory Data Analysis:** Explore the data to find insights and better understand the impact of variables on model learning.

**Step 03. Feature Engineering:** Melhoria na visualização dos dados.

**Step 04. Hypoteses Test:** Testar correlações e influências dos atributos nas notas

**Step 05. Data Preparation:** Preparação dos dados para eliminar impurezas do conjunto de dados

**Step 06. Selection of resources/Machine Learning Modeling:** Separação dos dados para teste e treino e aplicação do modelo.

  
  
# Top 5 Data Insights

**H1** - H1. A condição socio-economica influencia nos resultados das notas?
**TRUE**: Perceptivel aumento de notas comforma a condição socio-economica também sobe.
	
<p align="left">
  <img width="1000" height="400" src="https://user-images.githubusercontent.com/87772120/155704365-e8cad625-061d-453c-a970-57fc6a529f81.png"
</p>
	 
**H2**. H2. Alunos com acesso a TV em casa obtem melhores resultados?
**TRUE**: Aqui, um insight com um "Q" de curiosidade,até onde o acesso a informações audio-visual influencia no desenvolvimento cognitivo das pessoas? 
<p align="left">
  <img width="1000" height="400" src="https://user-images.githubusercontent.com/87772120/155704735-f6eeab88-6d4e-4f15-a2bd-eb3219120bc6.png"
</p>

  
# Machine Learning Models Applied
Testing were performed using the following algorithms:

**Average Model**

**Linear Regression Model**

**Linear Regression Regularized Model - Lasso**
  # Resultado segundo amostragem de 5% do conjunto de dados
<p align="left">
  <img width="1000" height="400" src="https://user-images.githubusercontent.com/87772120/155698686-c15a785c-856e-45aa-8505-58301f6f760c.png"
</p>
  # Resultado segundo amostragem de 30% do conjunto de dados
  
**Random Forest Regressor**

**XGBoost Regressor**

# 6. Machine Learning Model Performance

**Single Performance**

| Model Name	| MAE	| MAPE	| RMSE |
|-----------|---------|-----------|---------|
| Random Forest Regressor	| 684.564904	| 0.100777	| 1019.742124 |
| XGBoost Regressor	| 843.112293	| 0.122609	| 1250.952637 |
| Average Model	| 1354.800353	| 0.206400	| 1835.135542 |
| Linear Regression	| 1867.089774	| 0.292694	| 2671.049215 |
| Linear Regression - Lasso	| 1891.704881	| 0.289106	| 2744.451737 |
 
**Real Performance - Cross Validation**

| Model Name | MAE CV   | MAPE CV      | RMSE CV |
|-----------|---------|-----------|---------|
|  Random Forest Regressor	| 847.78 +/- 224.47	| 0.12 +/- 0.02 | 1271.62 +/- 328.74 |
|  XGBoost Regressor	| 1030.28 +/- 167.19	| 0.14 +/- 0.02	| 1478.26 +/- 229.79 |
|  Linear Regression	  |	2081.73 +/- 295.63	| 0.3 +/- 0.02	| 2952.52 +/- 468.37 |
|  Linear Regression - Lasso  |2116.38 +/- 341.5	| 0.29 +/- 0.01	| 3057.75 +/- 504.26 |
 

Although the Random Forest model has proven to be superior to the others, in some cases this model ends up requiring a lot of space to be published, resulting in an extra cost for the company to keep it running. Therefore, the chosen algorithm was the **XGBoost Regressor** which in sequence passed to the Hyperparameter Fine Tunning step.


**Final Performance - Hyperparameter Fine Tunning Cross Validation**

Após encontrar os melhores parâmetros para o modelo através do metódo Random Search as métricas finais para o modelo foram as seguintes:

| Model Name | MAE CV   | MAPE CV      | RMSE CV |
|-----------|---------|-----------|---------|
|  XGBoost Regressor	  | 1030.28 +/- 167.19 | 0.14 +/- 0.02 | 1478.26 +/- 229.79 |
	

**Model with XGBoost Regressor**

| Scenario | Values  |                              
|-----------|---------|
| Predictions	| €286,381,809.29 |
| Worst Scenario | €285,609,778.34 |
| Best Scenario	| €287,153,840.24 | 

#  Next steps

Start a second cycle to analyze the problem, seeking different approaches, especially considering stores with behavior that is difficult to predict.

Possible points to be addressed in the second cycle:

-**Transformar dados categoricos em númericos para extrair melhores resultados**

-**Reescalando e Encodando melhor essas variaveis categoricas com metodos mais acurativos**

-**Trabalhando melhorias no passo Feature Engineering**



Ref.: 
  - Imagem disponible on [Google Imagens](https://www.google.com/imgres?imgurl=https%3A%2F%2Fd1hbpr09pwz0sk.cloudfront.net%2Flogo_url%2Frossmann-czech-republic-e86d67e6&imgrefurl=https%3A%2F%2Frocketreach.co%2Frossmann-czech-republic-profile_b55ebaf6f68b0522&tbnid=DgzEqnZWCD-1zM&vet=12ahUKEwji6_XZ9pr0AhWWK7kGHb5PDqYQMyg5egQIARBF..i&docid=ZLc7upQS0jcYKM&w=200&h=200&itg=1&q=Rossmann%20Marketing&ved=2ahUKEwji6_XZ9pr0AhWWK7kGHb5PDqYQMyg5egQIARBF#imgrc=HCCKxz-5W3rzJM&imgdii=RysZEEX_uQ6jyM)




# Kaggle ML Olympiad - QUALITY EDUCATION, by. Geraldine, Bruno

[Kaggle](https://www.kaggle.com/c/qualityeducation/overview)


Ps.: Correcting erro install requeriments.txt:
Inside this file there are two versions of sklearn, delete both and reinstall scikit-learn==0.24.2
