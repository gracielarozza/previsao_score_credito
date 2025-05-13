# 📈 Previsão de Score de Crédito

O objetivo deste projeto é aplicar técnicas de pré-processamento para preparar uma base de dados bancária com foco na futura previsão do **score de crédito**, que é um sistema de pontuação que reflete o histórico de crédito e a probabilidade de um indivíduo pagar suas dívidas. Trata-se de uma métrica essencial para auxiliar instituições financeiras na tomada de decisão sobre a concessão de crédito.

## Bibliotecas utilizadas

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

## Arquivos

1. **`previsao_credito_pre_processamento.ipynb`**  
   Etapas realizadas:
   - Verificação e ajuste dos tipos de dados  
   - Tratamento de valores ausentes  
   - Padronização de variáveis categóricas  
   - Análise exploratória univariada e bivariada  
   - Cálculo de correlação entre variáveis  
   - Separação da base em treino e teste
   - Balanceamento da variável alvo na base de treino

## Principais conclusões da análise

- A maioria dos clientes possui pontuação de crédito alta, graduação ou pós-graduação, casa própria e não tem filhos.
- Clientes com maior escolaridade tendem a ter score de crédito mais alto.
- Clientes com mestrado ou doutorado apresentam, em média, maiores salários e altas pontuações de crédito.
- Clientes com maior idade possuem maiores salários e consequentemente maior pontuação de crédito.
- Clientes com casa própria tendem a ter score de crédito de médio a alto.
- Clientes do gênero feminino apresentaram, em média, scores de crédito mais baixos em relação aos homens.

## Autora

**Graciela Rozza**  
Projeto desenvolvido como parte dos estudos em **Ciência de Dados**, com foco no **tratamento, análise exploratória e preparação de dados para modelagem preditiva**.

## Licença

MIT
