## Uma análise detalhada de o ‘que encarece um Notebook?

### Visão Geral

Já se perguntou por que um notebook pode custar o dobro do outro, mesmo parecendo muito semelhantes? Eu também! Para te ajudar a entender melhor porque isso acontece, analisando diferentes modelos e descobrindo o que realmente influencia o preço de um notebook. A análise foi feita na plataforma Databricks com base nos dados obtidos do Kaggle.

[![](laptopsales.gif)](https://github.com/user-attachments/assets/f3547ef1-88fa-4d64-afc8-0f1955e920a3)

**Link para o projeto:** [databricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1095832313552270/1432661428716512/1323315511525775/latest.html)

### Conjunto de Dados
Os dados usados para essa análise incluem informações de diferentes marcas que fornecem laptops no mercado. Os dados contêm informações de diferentes modelos, de diferentes marcas, contém também suas especificações como por exemplo, o tipo de memória, processador e outras características que afetam a precificação dos produtos.

# Exploração e Desenvolvimento

*A análise dos dados é feita com base em perguntas:*

*Média de preço por marcas*
- Ao compararmos a média de preço de diferentes marcas, observamos que a Alienware se destaca como a marca com preços consideravelmente mais altos que a média do mercado. A Apple também apresenta preços elevados estando apenas abaixo da Alienware. 
Na outra extremidade, a Iball se posiciona como a marca mais acessível, oferecendo notebooks a preços mais baixos. A Samsung, por sua vez, embora seja uma marca famosa, apresenta preços competitivos, ficando em segundo lugar entre as marcas mais econômicas.

*Participação em percentual das memórias (DDR3, DDR4 e DDR5)*
- A análise dos tipos de memória revelou que o DDR4 é o tipo que mais influência o preço dos notebooks, com uma diferença de cerca de 2000 unidades monetárias em relação aos outros tipos. 
Essa diferença pode ser explicada pela necessidade de componentes de maior qualidade e pela maior demanda por dispositivos com DDR4, que oferecem melhor desempenho.

*Participação dos processadores intel core*
- O processador Core i9 tem o maior percentual de Market Share, tendo a maior fatia de participação do mercado sugerindo uma alta demanda dado ao alto desempenho do produto. O Core i7 não fica muito para trás, sua participação em percentual no mercado indica certa popularidade.
Os modelos Core i5 e Core i3 são opções acessíveis que ainda sim fornecem um bom desempenho. Diferente do Core m3, Dual Core e Hexa Core que tem uma participação menor e menos populares.

*Média de preços por marca de processadores*
- Além do preço é importante considerar outros fatores ao escolher um processador, como compatibilidade com a placa-mãe, consumo de energia e desempenho. 
Mas se tratando da precificação, o chip M1 da Apple tem as maiores médias de preço, assegurando a qualidade do produto e reforçando a fama da marca por seus preços elevados. A concorrência entre Intel e AMD beneficia os consumidos já que tem preços mais competitivos e acessíveis dado a qualidade dos produtos.

*Total preço dos produtos que possuem ou não touchscreen*
- É notável que a presença do touchscreen nos produtos acrescenta um custo considerável, por isso é importante entender a demanda do cliente, se suas necessidades vão além de seu orçamento, é interessante levar em conta o uso do touchscreen, caso não haja necessidade dessa funcionalidade e o orçamento esteja arrojado, as opções sem touchscreen é mais viável.

### Ferramentas e Técnicas Utilizadas
- **Excel:** É muito importante que o analista de dados critique sua própria análise, por isso usei o Excel para converter o arquivo csv em formato de tabela, e criei uma tabela dinâmica para criticar as análises.
- **Databricks:** Plataforma utilizada para análise de dados e execução de consultas SQL.
- **SQL:** Linguagem utilizada para realizar a análise descritiva e consultas nos dados.
- **Análise Descritiva:** Análise dos dados que tem como objetivo identificar padrões e tendências.

### Conclusão 
Após todas as análises da viabilidade dos produtos, é importante entender a demanda dos consumidos para a decisão de compra. Esse material fornece diversos insights de diferentes contextos no momento da comprar de um notebook, levando em conta orçamento e funcionalidades.
