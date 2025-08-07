# 📊 Análise de Segmentos de Clientes - Global Superstore

Este projeto realiza uma análise exploratória detalhada dos segmentos de clientes da base de dados Global Superstore, com o objetivo de identificar **quais segmentos são mais lucrativos para a empresa** e como eles se comportam em diferentes regiões e categorias de produto.

---

## 🎯 Objetivo

Investigar o desempenho dos diferentes segmentos de clientes (Consumer, Corporate, Home Office) com base em indicadores como lucro, volume de vendas, ticket médio e localização geográfica, a fim de **propor insights que ajudem a direcionar estratégias de marketing e vendas**.

---

## 🧩 Base de Dados

- **Nome:** Global Superstore
- **Origem:** Kaggle ([Global Superstore Dataset](https://www.kaggle.com/datasets))
- **Tamanho:** ~50.000 registros
- **Período:** 2011 a 2014
- **Campos principais:**
  - `Segment`, `Category`, `Sub-Category`
  - `Sales`, `Profit`, `Quantity`, `Discount`
  - `Order Date`, `Ship Date`, `Country`, `City`, `Region`

---

## 🧠 Metodologia

Segui a metodologia **CRISP-DM (Cross-Industry Standard Process for Data Mining)**:

1. **Entendimento do Negócio:**  
   Compreender o objetivo de negócio: identificar segmentos mais lucrativos e gerar insights estratégicos.

2. **Entendimento dos Dados:**  
   Análise dos campos, verificação de tipos, valores nulos e variáveis relevantes.

3. **Preparação dos Dados:**  
   - Conversão de datas
   - Criação de colunas auxiliares (ano, mês, ticket médio, lead time)
   - Agrupamentos por segmento, região e categoria

4. **Análise Exploratória (EDA):**  
   Foram respondidas perguntas-chave com gráficos e estatísticas descritivas.

5. **Avaliação:**  
   Interpretação dos resultados e identificação dos principais insights para o negócio.

---

## ❓ Perguntas de Negócio

Foram elaboradas e respondidas perguntas estratégicas como:

1. **Qual segmento traz mais lucro para a empresa?**  
   → O segmento **Consumer** se destaca com quase metade do lucro total.

2. **O segmento mais lucrativo também é o mais frequente?**  
   → Sim, o segmento Consumer possui o maior número de pedidos (~26.500).

3. **O comportamento dos segmentos muda entre regiões?**  
   → Apesar da liderança geral do segmento Consumer, há variações regionais.

4. **Qual o lucro por categoria e subcategoria?**  
   → Subcategorias como `Chairs`, `Phones` e `Copiers` são extremamente lucrativas.

5. **Existe relação entre volume de vendas e lucro?**  
   → Nem sempre. Algumas subcategorias com alto volume não trazem alto lucro.

6. **O tempo de entrega afeta o volume ou lucro?**  
   → Lead Time elevado pode reduzir lucro e impactar a satisfação.

7. **Há cidades com destaque em lucratividade?**  
   → Cidades como **New York**, **Los Angeles** e **Seattle** se destacam.

---

## 📈 Principais Gráficos

- Barras horizontais: Número de pedidos por segmento
- Pizza: Participação do lucro por segmento
- Gráficos de barras por subcategoria e categoria
- Boxplots: Distribuição de lucro por segmento
- Mapas e análises geográficas por cidade

---

## 🧰 Tecnologias Utilizadas

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Google Colab**
- **GitHub** para versionamento e portfólio

---

## 💡 Insights Gerados

- **Segmento Consumer** é o principal motor de lucro e vendas.
- Algumas subcategorias têm alto volume mas baixo retorno.
- Diferenças regionais devem ser consideradas em campanhas locais.
- Fatores logísticos, como tempo de entrega, influenciam o desempenho.

---

## 🧭 Próximos Passos

- Aplicar modelos de clusterização para segmentação avançada.
- Criar dashboard interativo no Power BI ou Tableau.
- Avaliar impacto de descontos no lucro por segmento.

---

## 👨‍💼 Sobre o Autor

**Douglas Soares**  
Analista de Dados em formação | Excel • Power BI • Python • SQL  
[LinkedIn](https://www.linkedin.com/in/douglassoares13) | [Portfólio no GitHub](https://github.com/DouglasSoares13)

---

## ⭐ Contribua

Se gostou do projeto, deixe uma ⭐ no repositório!



