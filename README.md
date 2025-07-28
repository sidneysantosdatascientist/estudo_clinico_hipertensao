#   Estudo Clínico Simulado de Hipertensão
Este repositório apresenta um estudo clínico simulado sobre hipertensão arterial, com foco em gerenciamento de dados, visualização analítica e predição de riscos. O projeto foi desenvolvido com o objetivo de demonstrar habilidades em ETL com Python, análise interativa com Power BI, integração simulada com REDCap e machine learning aplicado à saúde.

---

##  Objetivos

- Integrar dados clínicos simulados de pacientes, visitas e eventos adversos
- Automatizar o processo de ETL com Python
- Criar dashboards interativos com Power BI
- Construir um modelo preditivo para identificar pacientes com maior risco
- Simular o uso de REDCap como sistema de coleta eletrônica de dados

---

##  Pipeline de ETL (Python)

- Leitura e limpeza dos dados
- Padronização e formatação de colunas
- Unificação das tabelas
- Conversão de variáveis categóricas e temporais
- Pronto para consumo no Power BI


---

##  Dashboard Power BI

O painel interativo foi dividido em 4 seções principais:

1. **Perfil dos Pacientes**: idade, sexo, etnia, faixa etária  
2. **Evolução da Pressão Arterial**: evolução da pressão arterial e glicemia ao longo do tempo  
3. **Eventos Adversos**: Frequência, tipo e severidade de eventos registrados
4. **Visão Geral **: Visão Geral do estudo clínico

---

##  Modelo Preditivo de Risco de Complicações

### Objetivo  
Desenvolver um modelo de machine learning para prever risco de complicações em pacientes, utilizando dados clínicos e demográficos, com aplicação em apoio à decisão médica.

### Metodologia  
- **Algoritmo**: Random Forest (100 árvores, balanceamento automático)  
- **Dados**: 3 datasets combinados com 9 variáveis clínicas e demográficas  
- **Divisão**: 70% treino / 30% teste  

### Resultados  
-  Acurácia: 85%  
-  AUC-ROC: 0.87  
-  Variáveis mais influentes:  
  - Pressão arterial sistólica (28%)  
  - Idade (22%)  
  - Glicemia (19%)  

### Aplicações Práticas  
- Triagem automatizada de pacientes prioritários  
- Sistema de alertas para alto risco  
- Otimização do uso de recursos hospitalares  

---

##  Integração com REDCap 

O projeto foi estruturado de forma compatível com a plataforma REDCap, que é amplamente utilizada em estudos clínicos.

- Estrutura de dados baseada em formulários longitudinais do REDCap  
- Possibilidade de importar/exportar dados via CSV
- Coleta simulada poderia ser feita por formulários web no REDCap  


  ##  Geração de Dados Sintéticos
Os dados foram gerados com algoritmos em Python para simular um cenário realista, porém com segurança e privacidade:

Idades e pressões com distribuição normal
Eventos adversos gerados com lógica probabilística
Sem uso de dados reais ou sensíveis




📌 Tecnologias Utilizadas
Python (Pandas, Scikit-learn, Matplotlib)
Power BI
REDCap 
Git / GitHub



Sidney Pereira Santos
Analista de Dados • Rio de Janeiro – RJ
sidneysantosdatascientist@gmail.com
LinkedIn
