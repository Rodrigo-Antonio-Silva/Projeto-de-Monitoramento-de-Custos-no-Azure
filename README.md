"# Projeto-de-Monitoramento-de-Custos-no-Azure" 

Este projeto tem como objetivo implementar práticas de **governança de custos no Azure**, utilizando políticas de marcação, criação de orçamentos, alertas e análise de custos em tempo real.  

As etapas realizadas foram registradas em imagens para ilustrar o processo.

---

## 🔹 Estrutura do Projeto

### 1. Análise de Custos  
Foi realizada a análise de custos consolidados da assinatura, identificando os principais serviços que impactam o orçamento.  

![Análise de Custos](imagens\01-cost-analysis.png)

---

### 2. Orçamento Definido  
Criado um orçamento no valor de **10 USD/mensal** com validade de 2 anos (01/09/2025 a 31/08/2027).  

![Orçamento](imagens\02-budget.png)

---

### 3. Marcação de Recursos (Tags)  
Aplicadas **tags obrigatórias** para garantir rastreabilidade e governança dos recursos.  
- `project: lab`  
- `owner: Rodrigo`  

![Tags](imagens\03-tags.png)

---

### 4. Política de Governança (Azure Policy)  
Implementada a política **exigirTag** para impedir a criação de novos recursos sem as devidas marcações.  

![Policy](imagens\05-policy.png)

---

### 5. Alertas de Custos  
Configurados alertas para monitorar o consumo e evitar estouro do orçamento definido.  

![Alertas](imagens\04-advisor.png)

---

## 📊 Resultados Obtidos

- Visualização detalhada dos custos por **serviço**, **região** e **assinatura**.  
- Orçamento definido com **alertas preventivos**.  
- Aplicação de **tags obrigatórias** para melhor controle de custos.  
- Política de governança configurada, garantindo conformidade na criação de novos recursos.  

---

## 🚀 Conclusão

Este projeto demonstrou a aplicação de **boas práticas de FinOps no Azure**, envolvendo:  
- Governança com **Azure Policy**  
- Controle de custos com **Budget e Alerts**  
- Organização com **tags obrigatórias**  
- Monitoramento com **Cost Analysis**  

Essa estrutura é um passo importante para **otimizar gastos em nuvem** e manter a previsibilidade financeira dos recursos do Azure.

