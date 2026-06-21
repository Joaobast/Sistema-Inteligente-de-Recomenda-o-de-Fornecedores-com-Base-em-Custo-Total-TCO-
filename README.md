# [cite_start]Sistema Inteligente de Recomendação de Fornecedores com Base em Custo Total (TCO) [cite: 5]

## 📌 Sobre o Projeto
[cite_start]Este projeto consiste no desenvolvimento de um sistema de Inteligência Artificial aplicado ao setor de suprimentos, visando otimizar a escolha de fornecedores[cite: 8]. 

[cite_start]Tradicionalmente, a seleção é feita apenas pelo menor preço unitário[cite: 16]. [cite_start]A proposta desta solução é utilizar dados históricos de compras para recomendar os melhores fornecedores com base no **Custo Total de Aquisição (TCO)**, considerando fatores logísticos e operacionais, como frete, prazo de entrega e confiabilidade[cite: 9, 11]. [cite_start]O objetivo é garantir uma tomada de decisão mais eficiente, estratégica e orientada por dados[cite: 9, 112].

## 🚀 Principais Funcionalidades
* [cite_start]**Motor de Recomendação Baseado em TCO:** Cálculo automático do custo preditivo e geração de um ranking (Top 3) com as melhores opções para uma necessidade de compra[cite: 36, 58, 66].
* [cite_start]**Análise Multicritério:** Integração simultânea de variáveis como preço unitário, custo de frete, prazo médio de entrega, índice de atrasos e confiabilidade[cite: 54, 65, 79].
* [cite_start]**Dashboard Interativo:** Interface web simples que exibe os resultados e os indicadores que justificam a recomendação do algoritmo, garantindo transparência[cite: 67, 71, 86].
* [cite_start]**Aprendizado Contínuo:** Utilização de modelos de Machine Learning que aprendem e adaptam suas previsões conforme novos dados são incorporados à base histórica[cite: 81, 82].

## 🛠️ Arquitetura e Tecnologias
[cite_start]O sistema foi estruturado em camadas (apresentação, aplicação e inteligência artificial) para facilitar a escalabilidade[cite: 85, 90]. 

* [cite_start]**Linguagem Principal:** Python [cite: 96]
* [cite_start]**Machine Learning & Processamento de Dados:** Scikit-Learn, Pandas, NumPy [cite: 91, 97, 99]
* [cite_start]**Banco de Dados:** PostgreSQL [cite: 97]
* [cite_start]**Backend:** API desenvolvida com framework Flask ou FastAPI [cite: 93]
* [cite_start]**Frontend / Interface:** HTML, CSS e JavaScript [cite: 98]

## 📊 Avaliação de Desempenho
[cite_start]Para garantir a confiabilidade das recomendações, os modelos preditivos (como Random Forest e Gradient Boosting) são avaliados por métricas estatísticas rigorosas[cite: 57, 59, 60], incluindo:
* [cite_start]Erro Absoluto Médio (MAE) [cite: 59]
* [cite_start]Raiz do Erro Quadrático Médio (RMSE) [cite: 59]
* [cite_start]Coeficiente de Determinação ($R^{2}$) [cite: 59]

## 💡 Inovação e Diferencial
[cite_start]Enquanto as grandes plataformas corporativas de gestão de compras exigem implantações complexas e de alto custo, este projeto busca **democratizar o uso da Inteligência Artificial no setor de suprimentos**[cite: 47, 83]. [cite_start]Ele oferece uma alternativa simples e acessível, focada estritamente no apoio à decisão estratégica por meio de análise preditiva automatizada[cite: 48, 78].
