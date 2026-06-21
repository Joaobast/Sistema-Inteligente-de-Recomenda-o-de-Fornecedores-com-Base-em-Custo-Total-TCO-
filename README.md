#  Sistema Inteligente de Recomendação de Fornecedores com Base em Custo Total (TCO)


##  Sobre o Projeto
Este projeto consiste no desenvolvimento de um sistema de Inteligência Artificial aplicado ao setor de suprimentos. O objetivo principal é otimizar a escolha de fornecedores utilizando dados históricos de compras para recomendar as melhores opções com base no **Custo Total de Aquisição (TCO)**, indo muito além da tradicional e limitada análise baseada apenas no menor preço unitário.

A solução foca em democratizar o uso da inteligência analítica para pequenas e médias empresas, oferecendo uma ferramenta de apoio à decisão estratégica que avalia fatores logísticos, operacionais e históricos de forma automatizada.

---

##  O Problema vs. A Solução

**O Problema:** 
O setor de compras frequentemente decide alocações de recursos baseando-se no menor preço de etiqueta. Essa prática ignora custos ocultos e fatores de risco críticos, como fretes abusivos, atrasos constantes na entrega e falta de confiabilidade do fornecedor, o que no fim gera prejuízos e ineficiência na cadeia produtiva.

**A Solução:** 
A implementação de modelos de aprendizado de máquina (Machine Learning) que analisam a base histórica de compras para prever o TCO futuro. O sistema cruza dados financeiros e logísticos para gerar um ranking dinâmico (Top 3) com os fornecedores que realmente representam o melhor custo-benefício e menor risco para a organização.

---

## Principais Funcionalidades

* **Cálculo Preditivo de TCO:** Avaliação simultânea de preço, custo de frete, prazo médio de entrega, histórico de atrasos e índice de confiabilidade.
* **Motor de Recomendação Baseado em ML:** Geração automática de rankings justificando o motivo da escolha de cada fornecedor.
* **Módulo de Aprendizado Contínuo:** O algoritmo recalibra suas previsões conforme novos dados de compras e entregas são inseridos no banco de dados, adaptando-se a mudanças no comportamento dos fornecedores.
* **Dashboard Interativo (Apoio à Decisão):** Uma interface web clara e intuitiva para que gestores consultem recomendações sem necessidade de conhecimentos técnicos em dados.
* **Análise Comparativa:** Diferente de softwares corporativos de alto custo (como SAP Ariba e Oracle Fusion), este sistema tem baixo atrito de implantação e foco direto na recomendação analítica.

---

##  Arquitetura e Tecnologias Utilizadas

O sistema foi estruturado em camadas (Apresentação, Aplicação e Inteligência Artificial) garantindo escalabilidade e facilidade de manutenção.

**Inteligência Artificial e Processamento de Dados:**
* **Python:** Linguagem base do projeto.
* **Scikit-Learn:** Construção e treinamento dos modelos preditivos (Regressão, Random Forest, Gradient Boosting).
* **Pandas & NumPy:** Limpeza, manipulação, pré-processamento e normalização dos dados históricos.
* **Matplotlib:** Análise exploratória e visualização gráfica dos resultados experimentais.

**Backend & Banco de Dados:**
* **PostgreSQL:** Armazenamento estruturado de entidades (fornecedores, produtos, pedidos, logística).
* **Flask / FastAPI:** Criação da API REST para comunicação entre a inteligência artificial e a interface.

**Frontend:**
* **HTML, CSS e JavaScript:** Interface limpa e responsiva para interação do usuário final.

---

##  Autor

**João Vitor da Silva Bast**  
*Desenvolvedor com forte base em Python, focado em pesquisa operacional, modelagem matemática e construção de soluções inteligentes baseadas em dados.*


* [E-mail](mailto:joao.bast@catolicasc.edu.br)
* Universidade Católica de Santa Catarina
