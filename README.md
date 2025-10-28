# Projeto Integrador IV - Universidade Virtual do Estado de São Paulo

## Previsão de acidentes típicos, de trajeto e doenças ocupacionais no setor petroquímico por meio de algoritmos de aprendizagem de máquinas 

O presente projeto integrador tem como objetivo desenvolver um sistema de previsão de acidentes de trabalho no setor petroquímico, utilizando algoritmos de aprendizagem de máquina aplicados a registros históricos de acidentes. A relevância do estudo se evidencia diante dos riscos significativos presentes nas operações petroquímicas, nos quais a prevenção de incidentes é essencial para garantir a segurança dos trabalhadores, reduzir custos operacionais e fortalecer a sustentabilidade organizacional. 

A metodologia adotada envolve a coleta de dados públicos reais do governo de São Paulo, com extração de variáveis relevantes, análise exploratória de dados (EDA), organização e tratamento dos registros de acidentes, garantindo a consistência e a confiabilidade dos dados utilizados. Essa etapa possibilitou a identificação de padrões e fatores de risco associados à ocorrência de acidentes, que se encontram presentes no jupyter notebook [tratamento_dados_pi_4](https://github.com/telmacarvalho/pi-4-univesp/blob/main/tratamento_dados_pi_4.ipynb). 

Dando continuidade nesse processo, foi treinado o algoritmo de machine learning multi-target RandomForestRegressor com validação cruzada para estimar a probabilidade de acidentes típicos e de trajeto no notebook [treinamento_ml_pi_4](https://github.com/telmacarvalho/pi-4-univesp/blob/main/treinamento_ml_pi_4.ipynb).

Após a obtenção das melhores métricas do modelo na fase de validação, foi realizada a inferência com a predição de uma série temporal para os três anos seguintes, por meio de previsões interativas, no notebook [inferencia_ml_pi_4](https://github.com/telmacarvalho/pi-4-univesp/blob/main/inferencia_ml_pi_4.ipynb). 

Por fim, o resultado foi exportado para um dashboard dinâmico no [Looker Studio Overview](https://lookerstudio.google.com/reporting/5ba91fa1-ca5d-471c-a9f9-3107203bbabb).

Este sistema desenvolvido funciona como uma ferramenta estratégica de apoio à tomada de decisão para gestores de Segurança e Saúde no Trabalho (SST), permitindo a adoção de medidas preventivas mais eficazes. Além de contribuir para a redução da ocorrência de acidentes, o projeto visa aprimorar as práticas de gestão de riscos no setor petroquímico, promovendo ambientes de trabalho mais seguros e fortalecendo a cultura de prevenção e responsabilidade corporativa.

