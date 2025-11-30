# GA4 Analyst Bot: Inteligência Autônoma de Marketing

Bem-vindo à documentação técnica do **GA4 Analyst Bot** (nome de projeto "NanoAnalytics"), um agente autônomo projetado para transformar dados brutos de tráfego em inteligência de negócios acionável.

!!! abstract "O Problema"
    Dashboards do Google Analytics 4 são excelentes para mostrar *o que* aconteceu, mas falham em explicar *por que* aconteceu ou *o que fazer* a seguir. Analistas de marketing perdem horas valiosas diariamente apenas tentando identificar anomalias em meio ao ruído dos dados.

## A Solução

Este projeto não é apenas mais um dashboard. É um sistema de engenharia de dados "hands-off" que automatiza o ciclo de análise:

1.  **Extrai** dados brutos do GA4 diariamente via API em janelas de comparação dinâmicas.
2.  **Processa** e normaliza os dados, calculando variações estatísticas (DoD% e WoW%).
3.  **Analisa** os resultados usando um LLM (GPT-4) equipado com um "System Prompt" de engenharia avançada, simulando um analista sênior.
4.  **Entrega** um briefing executivo focado em ações diretamente no Slack da equipe antes do início do expediente.

---

*Nota: O código-fonte principal deste projeto (os scripts de automação e os prompts exatos da IA) é mantido em um repositório privado para proteção de propriedade intelectual durante a fase de MVP. Esta documentação serve como uma visão geral da arquitetura do sistema.*
