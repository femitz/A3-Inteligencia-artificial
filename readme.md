## A3 - Inteligencia Artificial

Objetivo: Criar uma inteligencia artificial que possa classificar fetos em Normal, Suspeito e Comprometido


## Banco de dados

[Fetal Health - Kaggle](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)

A redução da mortalidade infantil está refletida em vários dos Objetivos de Desenvolvimento Sustentável das Nações Unidas e é um indicador-chave do progresso humano. A ONU espera que, até 2030, os países acabem com as mortes evitáveis de recém-nascidos e crianças menores de 5 anos, com todos os países buscando reduzir a mortalidade abaixo de 25 por 1.000 nascidos vivos.

Paralelamente à noção de mortalidade infantil, está a mortalidade materna, que contabilizou 295.000 mortes durante e após a gravidez e o parto (dados de 2017). A grande maioria dessas mortes (94%) ocorreu em contextos de baixos recursos, e a maioria poderia ter sido evitada.

Com base no que foi mencionado acima, os Cardiotocogramas (CTGs) são uma opção simples e acessível para avaliar a saúde fetal, permitindo que profissionais de saúde tomem medidas para prevenir a mortalidade infantil e materna. O equipamento funciona enviando pulsos de ultrassom e lendo sua resposta, fornecendo informações sobre a frequência cardíaca fetal (FCF), os movimentos fetais, as contrações uterinas e mais.

Dados
Este conjunto de dados contém 2.126 registros com características extraídas de exames de Cardiotocograma, que foram classificados por três obstetras especialistas em 3 classes:

	•	Normal
	•	Suspeito
	•	Comprometido

## Informações das colunas do banco de dados
### baseline value
Frequência Cardíaca Fetal (FCF) Basal

### accelerations
Número de acelerações por segundo

### fetal_movement
Número de movimentos fetais por segundo

### uterine_contractions 
Número de contrações uterinas por segundo

### light_decelerations
Número de desacelerações leves por segundo

### severe_decelerations
Número de desacelerações severas por segundo

### prolongued_decelerations
Número de desacelerações prolongadas por segundo

### abnormal_short_term_variability
Porcentagem de tempo com variabilidade anormal de curto prazo

### mean_value_of_short_term_variability
Valor médio da variabilidade de curto prazo

### percentage_of_time_with_abnormal_long_term_variability
Porcentagem de tempo com variabilidade anormal de longo prazo