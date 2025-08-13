# Desafio Telecom_X_parte_2

Esta segunda fase do projeto consistiu na análise de prevenção de evasão de clientes (churn) por meio da utilização de modelos de aprendizado de máquina (Machine Learning).

# Objetivo

Este projeto teve como foco principal a análise dos dados da empresa Telecom X para:

- Identificar os principais fatores que causam a evasão de clientes.

- Criar modelos preditivos para prever o perfil dos clientes que cancelam o serviço.

- Fornecer insights estratégicos para aumentar a retenção de clientes.

# Análise de Importância das Variáveis

# Regressão Logística

- O modelo de Regressão Logística demonstrou uma melhor capacidade de identificação de cancelamentos, apresentando um Recall de 0.81. Isso indica que o modelo é eficiente em capturar a maioria dos clientes que realmente cancelam.

- No entanto, a precisão de 0.52 sugere que, das vezes em que o modelo previu um cancelamento, ele errou quase metade das vezes.

- O desempenho geral do modelo é considerado bom, conforme indicado pelo ROC AUC de 0.845.

# Random Forest
- O modelo Random Forest apresentou uma acurácia e precisão superiores em comparação com a Regressão Logística, sugerindo uma maior confiabilidade em suas previsões.

- Contudo, o Recall para a classe positiva (churn) foi de 0.60, o que evidencia uma fraqueza do modelo: ele falha em identificar um número significativo de clientes que efetivamente cancelaram seus serviços.

# Conclusão da Análise

- A Regressão Logística é a opção mais adequada para cenários onde a prioridade é identificar o maior número possível de clientes em risco de evasão, permitindo que a empresa tome medidas proativas de retenção.

- Já o modelo Random Forest é mais indicado quando a precisão é o fator mais crítico, ou seja, quando se deseja ter maior certeza de que a previsão de cancelamento está correta, evitando intervenções desnecessárias com clientes que não iriam cancelar.

- Adicionalmente, a análise revelou que os pagamentos por cheque eletrônico e o serviço de fibra óptica são os dois principais fatores associados ao cancelamento. Por outro lado, contratos de dois anos e a ausência de serviço de internet estão relacionados a uma menor taxa de cancelamento.
