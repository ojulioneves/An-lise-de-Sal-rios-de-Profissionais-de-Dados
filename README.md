# Analise-de-Salarios-de-Profissionais-de-Dados
Análise de dados dos salários de profissionais de dados utilizando bibliotecas pandas, matplotlib e seaborn

**Resultado das Análises**

📊 Medidas de Tendência Central

Média: $137.570

Mediana: $135.000

📈 Medidas de Dispersão

Desvio Padrão: $63.056

Valor Mínimo: $5.132

Valor Máximo: $450.000

🧮 Distribuição Geral

O histograma mostra a distribuição assimétrica dos salários, com muitos valores concentrados abaixo de $200.000 e uma cauda longa à direita (salários muito altos).

📦 Comparação por Grupos (Boxplot)

O boxplot por nível de experiência (experience_level) mostra:

MI (Mid-Level) e SE (Senior) concentram a maioria dos salários médios/altos.

EN (Entry-Level) possui salários visivelmente mais baixos.

EX (Executive-Level) apresenta valores mais altos e maior dispersão.


🔍 Análise da Correlação das variáveis Númericas

✅ Existe alguma tendência de aumento salarial com os anos (work_year)?

Correlação positiva, mas fraca entre salary_in_usd e work_year (~0.18). Isso indica que os salários aumentaram levemente ao longo dos anos, mas não é uma tendência muito forte.

✅ Quanto maior o tempo de experiência, maior o salário?

Correlação moderada e positiva entre salary_in_usd e years_of_experience (~0.48). Isso sugere que, em geral, profissionais com mais experiência tendem a ganhar mais, embora não seja uma relação perfeita.
