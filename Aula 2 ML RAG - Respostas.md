## Entrega do grupo (checklist)
1. Mostre o `classification_report` do modelo (print ou saída)

Resposta:
precision    recall  f1-score   support

        Alta       1.00      0.67      0.80         3
       Baixa       0.87      1.00      0.93        27
       Média       0.91      0.71      0.80        14

    accuracy                           0.89        44
   macro avg       0.93      0.79      0.84        44
weighted avg       0.89      0.89      0.88        44

Matriz de confusão:
[[ 2  0  1]
 [ 0 27  0]
 [ 0  4 10]]

2. Teste **2 ocorrências novas** e justifique a prioridade
3. Faça **1 pergunta** para o Mini‑RAG e explique o contexto recuperado
4. (Bônus) Proponha **um campo novo** no dataset e discuta impacto

## Discussão final
- Onde ML acelera triagem e melhora consistência?
- Quais riscos (viés, dado ruim, generalização)?
- Por que RAG é mais seguro do que perguntar direto para um LLM?





