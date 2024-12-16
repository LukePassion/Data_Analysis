# Óculos de Realidade Virtual na Educação: Projeto de Análise de Dados

Este repositório contém um projeto abrangente de análise de dados que explora o impacto, desafios e oportunidades do uso da Realidade Virtual (VR) como uma ferramenta educacional em escolas e universidades em várias partes do mundo.
A análise foi conduzida utilizando PySpark no Databricks, com foco em seis áreas principais:

1. **Perfis e Demografia dos Usuários**
2. **Eficácia e Engajamento**
3. **Intensidade e Frequência de Uso**
4. **Impacto Criativo e Interesse em Continuar com os óculos VR**
5. **Suporte Institucional e Feedback dos Professores**
6. **Distribuição Geográfica e Suporte Regional**

---

## Tabela de Conteúdos
- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Detalhamento da Análise](#detalhamento-da-análise)
  - [1. Perfis e Demografia dos Usuários](#1-perfis-e-demografia-dos-usuários)
  - [2. Eficácia e Engajamento](#2-eficácia-e-engajamento)
  - [3. Intensidade e Frequência de Uso](#3-intensidade-e-frequência-de-uso)
  - [4. Impactos Criativos e o Interesse por Continuar o uso dos óculos VR](#4-impactos-criativos-e-o-interesse-em-continuar-o-uso-dos-óculos-vr)
  - [5. Suporte Institucional e Feedback dos Professores](#5-suporte-institucional-e-feedback-dos-professores)
  - [6. Distribuição Geográfica e Suporte Regional](#6-distribuição-geográfica-e-suporte-regional)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instruções de Configuração](#instruções-de-configuração)
- [Principais Insights](#principais-insights)

---

## Introdução
A Realidade Virtual (VR) está transformando a educação ao aumentar o engajamento, a criatividade e a colaboração entre os estudantes.
Este projeto investiga como a VR está sendo usada em instituições educacionais, analisando seu impacto e os desafios enfrentados pelos envolvidos.

## Objetivo
Analisar e interpretar as tendências, benefícios e desafios da adoção da VR na educação, utilizando insights baseados em dados.
Sendo assim, tendo uma noção se a VR é de fato uma ferramenta com boa utilidade ou não.


## Detalhamento da Análise

### 1. Perfis e Demografia dos Usuários
Analisou-se a distribuição dos usuários por idade, gênero e área de estudo para compreender a diversidade na adoção da VR.
Obs: Foi estabelecido como parâmetro para analise somente os dados dos alunos de "Gender": "Male" e "Female".

**Código:** [Análise de Perfis de Usuários](scripts/user_profiles_analysis.py)

---

### 2. Eficácia e Engajamento
Mediu-se a correlação entre o uso da VR e seu impacto nos resultados de aprendizado e níveis de engajamento.

**Código:** [Análise de Eficácia](scripts/effectiveness_analysis.py)

---

### 3. Intensidade e Frequência de Uso
Examinou-se a relação entre horas de uso de VR e níveis de estresse, focando em padrões entre diferentes grupos demográficos.

**Código:** [Análise de Uso](scripts/usage_analysis.py)

---

### 4. Impactos Criativos e o Interesse por Continuar com o Uso dos óculos VR
Explorou-se entre qual dos gêneros o óculos VR teve mais impacto com relação à criatividade, e quantos alunos teriam interesse ou não em continuar
estudando através dos óculos VR.

**Código:** [Análise de Colaboração e Criatividade](scripts/collaboration_analysis.py)

---

### 5. Suporte Institucional e Feedback dos Professores
Foi explorado se o uso dos óculos VR trazem algum beneficio e destaque ao currículo dos alunos, e qual a opinião dos professores com relação
ao uso deles no processo de aprendizagem.

**Código:** [Análise de Desafios Institucionais](scripts/challenges_analysis.py)

---

### 6. Distribuição Geográfica e Suporte Regional
Mapeou-se as tendências de adoção da VR entre as regiões, destacando disparidades e áreas com forte suporte institucional.

**Código:** [Análise de Distribuição Geográfica](scripts/geographic_analysis.py)

---

## Tecnologias Utilizadas
- **PySpark**: Para processamento escalável de dados.
- **Databricks**: Como plataforma principal de desenvolvimento e execução.
- **Python**: Para manipulação e análise de dados.

## Instruções de Configuração
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/vr-education-project.git
   ```
2. Faça upload do conjunto de dados para seu workspace do Databricks.
3. Execute os scripts na ordem listada na seção "Detalhamento da Análise".
4. Revise os resultados nos notebooks correspondentes.

## Principais Insights
- A VR aumenta significativamente os níveis de engajamento entre os estudantes mais jovens.
- A colaboração e criatividade melhoram com uso moderado de VR.
- Os desafios institucionais variam por região, sendo o financiamento uma barreira crítica em escolas com poucos recursos.

---

Sinta-se à vontade para explorar o código, relatar problemas e contribuir para este repositório. Vamos inovar juntos na educação!

---

### Autor
Lucas Paixão | Aspirante a Engenheiro de Dados
