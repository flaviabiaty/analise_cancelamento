# 📉 Análise de Cancelamento de Clientes

## 📌 Descrição
Este projeto tem como objetivo **analisar e reduzir a taxa de cancelamento de clientes** de uma empresa fictícia, a partir de uma base de dados realista.  
A análise identifica padrões e possíveis causas para o cancelamento, propondo ajustes que podem reduzir significativamente a taxa de churn (cancelamento).

---

## 🎯 Objetivos
- Importar e tratar a base de dados.  
- Identificar a taxa inicial de cancelamento.  
- Criar visualizações gráficas para facilitar a interpretação.
- Realizar análises por variáveis (contrato, assinaturas, uso, atrasos, ligações ao call center).    
- Propor ações e filtros que reduzam o cancelamento a um nível aceitável.  

---

## 🛠 Tecnologias Utilizadas
- **Python**
- **Pandas** → manipulação de dados  
- **Plotly Express** → criação de gráficos interativos  
- **Google Colab** → ambiente de análise

---

## 📂 Etapas do Projeto
1. **Importação da base de dados** com Pandas.  
2. **Remoção de colunas irrelevantes** (ex.: CustomerID).  
3. **Tratamento de dados**:
   - Remoção de valores nulos (`dropna`).
4. **Análise inicial**:
   - Cálculo da taxa de cancelamento total.  
5. **Análises segmentadas**:
   - Cancelamento por tipo de contrato.  
   - Cancelamento por tipo de assinatura.  
6. **Análises gráficas** com Plotly:
   - Dias de atraso.  
   - Ligações ao call center.  
7. **Aplicação de filtros** para reduzir cancelamentos:  
   - Remoção de contratos mensais.  
   - Considerar apenas clientes com menos de 5 ligações ao call center.  
   - Considerar apenas clientes com dias de atraso menores que 20.
8. **Cálculo da nova taxa de cancelamento**.

---

## 📊 Resultados
- **Taxa inicial**: 56,7%  
- Após remover contratos mensais: **46,1%**  
- Após aplicar filtros de atraso e ligações: **18,4%**  
- Ajuste adicional por idade (>50 anos): **12,1%**  
- Ajuste adicional por gasto total: **4,8%** (não viável economicamente)  

**Observação**: O foco é buscar reduções viáveis, considerando impacto real no negócio.

---

## 🚀 Conclusão
A análise mostrou que, com ajustes simples e identificação de padrões de comportamento, é possível reduzir drasticamente o cancelamento de clientes.  
A abordagem pode ser adaptada para diferentes contextos e empresas, sempre considerando a viabilidade das ações sugeridas.
*Possíveis soluções para redução da taxa de cancelamento*
Desconto nos planos trimestral e anual, uma vez que todos os clientes do contrato mensal cancelaram
Criação de um alerta quando o cliente ligar a 3ª vez pro callcenter
Criação de um alerta pro time de cobrança quando o cliente bater 10 dias de atraso.
Resolvendo esses fatores, pode ser obtida uma meta de cerca de 20% de cancelamento, muito melhor que os 50% iniciais


