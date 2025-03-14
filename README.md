![image](https://user-images.githubusercontent.com/87772120/136675995-17cf9a2f-4d03-4630-bff4-56a8918e0777.png)

  # [HACKATHON CER + Brasil](https://www.hackathoncermaisbr.com.br/)

[Hackathon Certificate]([https://example.com/meu-arquivo.pdf](https://drive.google.com/file/d/1ilwcbsJYNg83ngBGO84wZFXg28EDojbt/view?usp=sharing))


 ## "This project was created during the Hackathon CER+BRASIL 2021, organized by Projeto CER+BRASIL."

This event is part of a series of Knowledge Translation stages and is included in the Research and Innovation project that won the **Public Call No. 27/2019** from the **National Council for Scientific and Technological Development (CNPq)**: coverage for **“CER+Brasil: the Specialized Rehabilitation Centers (CER) and Orthopedic Workshops guided by the Biopsychosocial model.”**  

The project, which received financial support from the **National Council for Scientific and Technological Development** and the **Ministry of Health**, was proposed by the **Federal Institute of Education, Science, and Technology of Rio de Janeiro (IFRJ).**  

The purpose of this data science event is to bring together qualified analyses of **primary and secondary database technologies**, generating outcomes related to the **Care Network for People with Disabilities** in the **Unified Health System (SUS)**.

### **Project Objective**  
**Utilize data science to develop proposals for care and epidemiological parameters for the implementation of new CER services and Orthopedic Workshops in Brazil.**  

The **United Nations Convention on the Rights of Persons with Disabilities (UN/2007)**, ratified by Brazil, defines persons with disabilities as those who have **long-term physical, mental, intellectual, or sensory impairments** which, in interaction with various barriers, **may hinder their full and effective participation in society on an equal basis with others.**  

Hearing-impaired individuals were classified as those who responded **“some difficulty,” “great difficulty,” or “unable to hear at all”** to the question:  
*"Do you have a permanent hearing impairment? (If you use a hearing aid, assess your condition while using it)."* (IBGE-a, 2021).  

### **Context and Statistics**  
In **2019**, according to the **National Health Survey (PNS)**, **17.3 million people aged two years or older (8.4% of this population) had some type of disability.**  

A study by the **Brazilian Institute of Geography and Statistics (IBGE)** indicates that almost half of this group (49.4%) are elderly.  

These findings are part of the **2019 National Health Survey (PNS)**, published on **November 26, 2021**. This survey, conducted in partnership with the **Ministry of Health**, provides insights into the health conditions of the Brazilian population (IBGE-b, 2021).


 
![image](https://user-images.githubusercontent.com/87772120/136675985-3db92bb7-5db0-4082-a5de-ed995a6b8869.png)



The **CER (Specialized Rehabilitation Center)** is an **outpatient care unit specialized in rehabilitation**. Its care parameters include the **individualized construction of a Singular Therapeutic Project (PTS) for each SUS user**, ensuring access to Assistive Technology and serving as a reference point for the **Healthcare Network (Rede de Atenção à Saúde).**  

### **Identified Problem:**  
**"How many people with disabilities are there in Brazil, and where are they located?"**  

## **Parameters and Metrics**  

### **Metric:**  
- Represented on the map by the **color and size of the bubbles** centered on each municipality.  
- It is based on the **linear combination of the PCD (People with Disabilities) rate** (assigned a weight of 1) and the **IBP at the municipal level** (assigned a weight of 2), as follows:  

        Metric = PCD Rate * Weight 1 + IBP * Weight 2

- Each of these variables is **normalized**, and the sum of **weights 1 and 2 must equal 1**.  
- The **observed range** of the metric can be adjusted using the **leftmost filter**, while **weight 1 can be set using the slider control**—weight 2 is automatically determined in the adjacent visualization.  

### **Suggested Parameter:**  
- If **Metric > 0.18**, then establishing a **CER (Specialized Rehabilitation Center)** in the given city is recommended.  

### **PCD Rate:**  
- The incidence of people requiring rehabilitation relative to their respective **state (UF).**  

**By applying normalization, we aim to keep coefficient values between 0 and 1. The applied MinMaxScale normalization is detailed in this**  
[link](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.minmax_scale.html). (ScikitLearn, 2021)
       
     

 ## **Deliverable**: [**Dashboard CER+Brasil - Data Studio**](https://datastudio.google.com/reporting/c2b5121e-cee8-4eb6-b370-d350f795ffa7)  

## **Solution Planning**  

# **Project Stages:**  

**Stage 01. Data Description:** Primary data collection and analysis.  

**Stage 02. Feature Engineering:** Data cleaning and processing.  

**Stage 03. Data Filtering:** Selection of data related to pathologies by municipality.  

**Stage 04. Exploratory Data Analysis:** Data exploration to uncover insights and new metrics.  

**Stage 05. Data Preparation:** Preparing data for dashboard visualization.  

**Stage 06. Project Submission:** October 10, 2021.  

## **Project Developed By:**  
- Nataniel Pereira dos Santos  
- Felipe Provezano Coutinho  
- Cleiton de Oliveira Ambrosio  
- Bruno Martins Geraldine  

## **Bibliographic References:**  

**IBGE - a**. Brazilian Institute of Geography and Statistics. Gender statistics. Accessed on October 9, 2021. Available at: <https://www.ibge.gov.br/apps/snig/v1/?loc=0&cat=-1,-2,-3,128&ind=4643>.  

**IBGE - b**. Brazilian Institute of Geography and Statistics. IBGE News Agency – PNS 2019: The country has 17.3 million people with some type of disability. Accessed on October 9, 2021. Available at:  
<https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/31445-pns-2019-pais-tem-17-3-milhoes-de-pessoas-com-algum-tipo-de-deficiencia#:~:text=PNS%202019%3A%20pa%C3%Ads%20tem%2017,defici%C3%Aancia%20%7C%20Ag%C3%Aancia%20de%20Not%C3%Adcias%20%7C%20IBGE>.  

**GITHUB**. Data on "Lat", "Long" of Brazilian municipalities. Kelvins/Municipios-Brasileiros. Accessed on October 9, 2021. Available at: <https://github.com/kelvins/Municipios-Brasileiros>.  

**ScikitLearn**. sklearn.preprocessing.minmax_scale. Accessed on October 9, 2021. Available at: <https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.minmax_scale.html>.  

## **Applied Technologies:**  


[![image](https://user-images.githubusercontent.com/87772120/136676881-9942f3bc-2866-4bfb-b3bc-162a529b8409.png)](https://jupyter.org/)

[![image](https://user-images.githubusercontent.com/87772120/136676889-67b6c0e3-7f8a-497c-b02b-25947b1e3d70.png)](https://datastudio.google.com/)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)




            
