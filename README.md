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



## Solution Strategy:

Solution planning:
	
### → Ciclo 01

**Step 01. Data description:** Entender o conjunto de dados, visto a quantidade de atributos dos inscritos.

**Step 02. Exploratory Data Analysis:** Explore the data to find insights and better understand the impact of variables on model learning.

**Step 03. Feature Engineering:** Melhoria na visualização dos dados.

**Step 04. Hypoteses Test:** Testar correlações e influências dos atributos nas notas

**Step 05. Data Preparation:** Preparação dos dados para eliminar impurezas do conjunto de dados

**Step 06. Selection of resources/Machine Learning Modeling:** Separação dos dados para teste e treino e aplicação do modelo.

  
  
### The Best Data Insights

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

<p align="left">
  <img width="1000" height="400" src="https://user-images.githubusercontent.com/87772120/155708625-a4af7085-4809-47d1-b3a1-e7018b3fc778.png"
</p>
  
**Lasso Regressor Model - scikit-learn**

**XGBoost Regressor**


#  Next steps

Start a second cycle to analyze the problem, seeking different approaches, especially considering stores with behavior that is difficult to predict.

Possible points to be addressed in the second cycle:

-**Transformar dados categoricos em númericos para extrair melhores resultados**

-**Reescalando e Encodando melhor essas variaveis categoricas com metodos mais acurativos**

-**Trabalhando melhorias no passo Feature Engineering**


# Kaggle ML Olympiad - QUALITY EDUCATION, by. Geraldine, Bruno

[Kaggle](https://www.kaggle.com/c/qualityeducation/overview)
