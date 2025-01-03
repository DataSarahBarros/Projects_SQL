## O que Encarece um Notebook? Uma Análise Detalhada

### Visão Geral

Já se perguntou por que um notebook pode custar o dobro do outro, mesmo parecendo muito semelhantes? Eu também! Para te ajudar a entender melhor porquê isso acontece, analisando diferentes modelos e descobrindo o que realmente influencia o preço de um notebook. A análise foi feita na plataforma Databricks com base nos dados obtidos do Kaggle.


[![](laptopsales.gif)](https://github.com/user-attachments/assets/f3547ef1-88fa-4d64-afc8-0f1955e920a3)

**Link para o projeto:** [databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1095832313552270/1432661428716512/1323315511525775/latest.html)


### Conjunto de Dados
Os dados usados para essa análise incluem informaçoes de diferentes marcas que fornecem laptops no mercado. Os dados contém informaçóes de diferentes modelos, de diferentes marcas, contém também suas especificacoes como por exemplo, o tipo de memorias, processadoor e outras caracteristicas que afetam a precificaçao dos produtos.

# Exploração e Desenvolvimento

*A análise dos dados são feitas com base em perguntas:*

*Média de preço por marcas*
- Ao compararmos a média de preço de diferentes marcas, observamos que a Alienware se destaca como a marca com preços consideravelmente mais altos que a média do mercado. A Apple também apresenta preços elevados estando apenas abaixo da Alienware. 
Na outra extremidade, a Iball se posiciona como a marca mais acessível, oferecendo notebooks a preços mais baixos. A Samsung, por sua vez, embora seja uma marca famosa, apresenta preços competitivos, ficando em segundo lugar entre as marcas mais econômicas.

*Participação em percentual das memórias (DDR3, DDR4 e DDR5)*
- A análise dos tipos de memória revelou que o DDR4 é o tipo que mais influencia o preço dos notebooks, com uma diferença de cerca de 2000 unidades monetárias em relação aos outros tipos. 
Essa diferença pode ser explicada pela necessidade de componentes de maior qualidade e pela maior demanda por dispositivos com DDR4, que oferecem melhor desempenho.

*Participação dos processadores intel core*
- O processador Core i9 tem o maior percentual de market share, tendo a maior fatia de participaçáo do mercado sugerindo uma alta demanda dado ao alto desempenho do produto. O Core i7 não fica muito para tras sua participaçáo em percentual no mercado indica certa popularidade.
Os modelos Core i5 e Core i3 sáo opçóes acessiveis que ainda sim forncem um bom desempenho. Differente do Core m3, Dual Core e Hexa Core que tem uma participaçáo menor e menos populares.

*Média de preços por marca de processadores*

*Total preço dos produtos que possuem ou não touchcreen*



### Ferramentas e Técnicas Utilizadas
- **Databricks:** Plataforma utilizada para análise de dados e execução de consultas SQL.
- **SQL:** Linguagem utilizada para realizar a análise descritiva e consultas nos dados.
- **Análise Descritiva:** Análise dos dados que tem como objetivo identificar padrões e tendências.

### Conclusão (rever)
Este projeto proporciona uma análise detalhada de vários fatores que influenciam os preços dos computadores portáteis. Através das análises realizadas, é possível entender como a marca, tipo de memória, processador e presença de touchscreen afetam os preços. Esses insights são valiosos para consumidores, fabricantes e revendedores na tomada de decisões informadas sobre a compra e venda de laptops.