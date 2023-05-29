![image](https://user-images.githubusercontent.com/87772120/136675995-17cf9a2f-4d03-4630-bff4-56a8918e0777.png)

  # [HACKATHON CER + Brasil](https://www.hackathoncermaisbr.com.br/)
 
 ## "Esse projeto foi criado durante o projeto Hackathon CER+BRASIL 2021, realizado pela Projeto CER+BRASIL”.
  
  Este evento compõe um conjunto de etapas de Tradução do Conhecimento e é parte do projeto de Pesquisa e Inovação vencedor único de Chamada Pública nº 27/2019 do Conselho Nacional de Desenvolvimento Científico dos e parâmetros Tecnológico de (CNPq): cobertura para “CER+Brasil: os Centros Especializados em Reabilitação (CER) e Oficinas Ortopédicas orientados ao modelo Biopsicossocial”. O projeto que contou com apoio financeiro do Conselho Nacional de Desenvolvimento Científico e Tecnológico e do Ministério da Saúde tem como instituição proponente, o Instituto Federal de Educação, Ciência e Tecnologia do Rio de Janeiro (IFRJ). 
  A proposta deste evento de ciência de dados é reunir análises qualificadas de tecnologias de análise de bases de dados primários e secundários com desfechos sobre a Rede de Cuidados à Pessoa com Deficiência no Sistema Único de Saúde (SUS).

  Objetivo do Projeto: **utilizar-se da ciência de dados para construir propostas de parâmetros assistenciais e epidemiológicos para implantação de novos serviços CER e Oficinas Ortopédicas no Brasil.**
  
  A Convenção sobre os Direitos das Pessoas com Deficiência (ONU/2007) ratificada pelo Brasil traz a definição: pessoas com deficiência são aquelas que têm impedimentos de longo prazo de natureza física, mental, intelectual ou sensorial, os quais, em interação com diversas barreiras, podem obstruir sua participação plena e efetiva na sociedade em igualdades de condições com as demais pessoas. - Pessoas com deficiência auditiva foram assim classificadas quando tiveram "alguma dificuldade", "grande dificuldade" ou "não conseguiam de modo nenhum" como respostas para a pergunta "tem dificuldade permanente de ouvir? (se utiliza aparelho auditivo, faça sua avaliação quando o estiver utilizando)" (IBGE-a,2021).
  
  Em 2019, segundo a Pesquisa Nacional de Saúde (PNS), 17,3 milhões de pessoas com dois anos ou mais de idade (8,4% dessa população) tinham algum tipo de deficiência. 
  Um levantamento do Instituto Brasileiro de Geografia e Estatística (IBGE) aponta que quase metade dessa parcela (49,4%) é de idosos. 
  As informações fazem parte da Pesquisa Nacional de Saúde (PNS) de 2019, divulgada nesta quinta-feira (26). O levantamento, feito em parceria pelo Ministério da Saúde, traz informações sobre as condições de saúde da população brasileira (IBGE-b,2021).

 
![image](https://user-images.githubusercontent.com/87772120/136675985-3db92bb7-5db0-4082-a5de-ed995a6b8869.png)

 O CER é um ponto de atenção ambulatorial especializado em reabilitação. Tem como parâmetros assistenciais a construção individual para cada usuário do SUS de Projeto Terapêutico Singular (PTS) que inclua o acesso a Tecnologia Assistiva, constituindo-se em referência para a Rede de Atenção à Saúde. 
  
  
  Problema identificado: **"Quantos são e onde estão as pessoas com deficiência no Brasil?"**

**Parâmetros e métricas**:

Métrica: 
 - Denotada no mapa pela cor e tamanho das bolhas centradas em cada município. Se trata da combinação linear da taxa de PCDs (acompanhada do peso 1) e do IBP a nível municipal (acompanhado do peso 2), isto é:

        Métrica = Taxa PCDs * Peso 1 + IBP * Peso 2

 Cada uma das grandezas figura na métrica de forma normalizada**, e a soma dos pesos 1 e 2 deve ser 1.
 A amplitude observada da métrica pode ser regulada pelo filtro mais à esquerda, enquanto que o peso 1 pode ser setado no controle deslizante - o peso 2 fica automaticamente determinado no visual ao lado.

 Parâmetro sugerido:
 - Se 'Métrica > 0.18' , então é sugestível ter um CER na cidade em questão. 

 Taxa de PCDs: 
 - Incidência de pessoas com necessidade de reabilitação relativo ao respectivo UF.

      **Ao aplicar a normalização temos por objetivo manter os valores dos coeficientes entre 0 e 1. A normalização MinMaxScale aplicada está detalhada neste [link](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.minmax_scale.html). (ScikitLearn, 2021)
       
     

 **Entregável**: [**Dashboard CER+Brasil - Data Studio**](https://datastudio.google.com/reporting/c2b5121e-cee8-4eb6-b370-d350f795ffa7)

**Planejamento da solução**:

# Etapas do Projeto:

**Etapa 01. Descrição dos dados:** Coleta e análise primaria dos dados.

**Etapa 02. Feature Engineering:** Limpeza e tratamento dos dados.

**Passo 03. Filtragem de Dados:** Seleção de dados relativos as patologias por município.

**Etapa 04. Análise exploratória de dados:** Exploração dos dados para descobrir insights e novas métricas.

**Etapa 05. Preparação dos dados:** Prepare os dados para visualização do dashboard.

**Etapa 06. Submissão do projeto:** 10/out/2021.


**Projeto desenvolvido por**:  
 - Nataniel Pereira dos Santos
 - Felipe Provezano Coutinho
 - Cleiton de Oliveira Ambrosio
 - Bruno Martins Geraldine
                              
**Referências Bibliográficas**:

**IBGE - a**. Instituto Brasileiro de Geografia e Estatística. Estatísticas de gênero. Acesso em 09 de outubro de 2021. Disponível em:<https://www.ibge.gov.br/apps/snig/v1/?loc=0&cat=-1,-2,-3,128&ind=4643>. 

**IBGE - b**. Instituto Brasileiro de Geografia e Estatística. Agência Notícias IBGE – PNS 2019: país tem 17,3 milhões de pessoas com algum tipo de deficiência -. Acesso em 09 de outubro de 2021. Disponível em:<https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/31445-pns-2019-pais-tem-17-3-milhoes-de-pessoas-com-algum-tipo-de-deficiencia#:~:text=PNS%202019%3A%20pa%C3%Ads%20tem%2017,defici%C3%Aancia%20%7C%20Ag%C3%Aancia%20de%20Not%C3%Adcias%20%7C%20IBGE>.  

**GITHUB**. Dados "Lat", "Long" dos municípios brasilerios. Kelvins/Municipios-Brasileiros. Acesso em 09 de outubro de 2021. Disponível em:<https://github.com/kelvins/Municipios-Brasileiros>. 

**ScikitLearn**. sklearn.preprocessing.minmax_scale. Acesso em 09 de outubro de 2021. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.minmax_scale.html

Tecnologias aplicadas:

[![image](https://user-images.githubusercontent.com/87772120/136676881-9942f3bc-2866-4bfb-b3bc-162a529b8409.png)](https://jupyter.org/)

[![image](https://user-images.githubusercontent.com/87772120/136676889-67b6c0e3-7f8a-497c-b02b-25947b1e3d70.png)](https://datastudio.google.com/)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)




            
