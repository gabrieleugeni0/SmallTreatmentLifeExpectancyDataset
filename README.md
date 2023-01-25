# Análise e tratamento de dados do dataset público Life Expectancy

#### Com uso do pandas foi realizada uma análise dos dados ingeridos através do dataset público sobre expectativa de vida, obtido no Kaggle.
Também foram utilizados o Seaborn e o Matplotlib para realizar a plotagem de gráficos para análise.


##### **Sobre o dataset:**

Fonte:
[Life Expectancy (WHO)] (https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

Considerando dados de um período de 2000 a 2015 (16 anos) para todos os países, este dataset visa auxiliar na realização de uma análise preditiva a respeito da expectativa de vida. Imunizações importantes como Hepatite B, Poliomielite e Difteria também serão consideradas. Em poucas palavras, este estudo se concentrará em fatores de imunização, fatores de mortalidade, fatores econômicos, fatores sociais, além de outros fatores relacionados à saúde.

Como as observações deste conjunto de dados são baseadas em diferentes países, será mais fácil para um país determinar o fator preditivo que está contribuindo para o menor valor da expectativa de vida. Além disso, ajudará a sugerir a um país qual área deve ser dada importância para melhorar de forma eficiente a expectativa de vida de sua população. 
    
Facilitará o processo de análise de qual ou quais os fatores preditivos que estão contribuindo para diminuir o valor da expectativa de vida e também o de identificação de qual área deve receber mais atenção quanto a formas de aumento da expectativa de vida de sua população.

##### **Descrição das colunas:**

- **Country:** País
- **Year:** Ano
- **Status:** Estado Desenvolvido ou Em Desenvolvimento
- **Life Expectancy:** Expectativa de vida
- **Adult Mortality:** Taxa de mostalidade em adultos de ambos os sexos (probabilidade de morrer entre 15 e 60 anos por 1000 habitantes)
- **Infant Deaths:** Número de óbitos infantis por 1000 habitantes
- **Alcohol:** Consumo registrado por indivíduo acima de 15 anos (em litros)
- **Percentage Expenditure:** Gastos com saúde como porcentagem do Produto Interno Bruto per capita (%)
- **Hepatitis B:** Cobertura vacinal contra hepatite B (HepB) em crianças de 1 ano (%)
- **Measles:** número de casos de Sarampo notificados por 1000 habitantes
- **BMI:** Índice de Massa Corporal Médio de toda a população
- **Under-Five Deaths:** Número de mortes de menores de cinco anos por 1000 habitantes
- **Polio:** Cobertura vacinal contra pólio (Pol3) em crianças de 1 ano (%)
- **Total expenditure:** Gastos do governo geral com saúde como porcentagem do gasto total do governo (%)
- **Diphtheria:** Cobertura vacinal contra difteria, tétano e coqueluche (DTP3) em crianças de 1 ano de idade (%)
- **HIV/AIDS:** Mortes por 1 000 nascidos vivos HIV/AIDS (0-4 anos)
- **GDP:** Produto Interno Bruto per capita (em USD)
- **Population:** População do país
- **Tthinness 1-19 years:** Prevalência de magreza em crianças e adolescentes de 10 a 19 anos (%)
- **Thinness 5-9 years:**  Prevalência de magreza em crianças de 5 a 9 anos (%)
- **Income composition of resources:** Índice de Desenvolvimento Humano em termos de composição de renda dos recursos (índice variando de 0 a 1)
- **Schooling:** Número de anos de escolaridade (anos)

### Bibliotecas necessárias:
```
$ pip install pandas
```
```
$ pip install matplotlib
```
```
$ pip install seaborn
```
```
$ pip install itertools
```

###### Rodar todas as células do arquivo "life_expectancy_dataset_treatment.ipynb"