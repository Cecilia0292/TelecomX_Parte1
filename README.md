# 📡 Telecom X – Análise de Evasão de Clientes (Churn)-Parte 1

## 📌 Propósito da Análise

Este projeto realiza uma análise exploratória dos dados da empresa fictícia **Telecom X**, que enfrenta altos índices de cancelamento de clientes (churn). O objetivo é identificar os principais fatores que influenciam a evasão, utilizando Python e bibliotecas como Pandas, Plotly e Seaborn. Os insights obtidos servirão de base para estratégias de retenção e futuros modelos preditivos.

---

## 🗂️ Estrutura do Projeto
## 📊 Exemplos de Gráficos e Insights

### 👥 Perfil Demográfico e Evasão
- Clientes com parceiro e dependentes tendem a permanecer mais tempo.
- Indivíduos com 65 anos ou mais têm maior propensão à evasão.
- Gênero não influencia significativamente o churn.

![Perfil Demográfico](imagens/perfil_demografico.png)

### 📄 Evasão por Tipo de Contrato
- Contratos **Anual** e **Bienal** apresentam maior fidelização.
- Contratos **Mensais** têm maior risco de cancelamento.

![Tipo de Contrato](imagens/Evasao_tipocontrato.png)

## 📊 Gráfico Interativo: Evasão por Tempo de Contrato
- A evasão é mais intensa nos primeiros meses, especialmente no 1º.
- A partir do 12º mês, a taxa se estabiliza abaixo da média de 22,01%.

👉 Você pode visualizar o gráfico interativo diretamente pelo GitHub Pages:
🔗 [Acesse o gráfico interativo aqui](https://cecilia0292.github.io/TelecomX_Parte1/tempo_contrato.html))

### 💳 Forma de Pagamento
- Cartão de crédito, transferência bancária e cheque enviado → alta retenção.
- Cheque eletrônico → taxa de evasão de 45,3%, indicando menor engajamento.

![Forma de Pagamento](imagens/Proporcaoevasao_formapagamento.png)

---

## ✅ Conclusões e Recomendações

### Principais Conclusões:
- Contratos curtos e pagamentos manuais estão associados ao churn.
- Clientes com menor valor de cobrança tendem a cancelar mais.
- Formas de pagamento automáticas favorecem a retenção.

### Recomendações Estratégicas:
- Incentivar contratos mais longos com benefícios progressivos.
- Oferecer planos personalizados para clientes de baixo valor.
- Monitorar clientes nos primeiros meses com ações específicas.
- Promover o uso de cartão de crédito ou débito automático.

---

## ⚙️ Instruções para Executar o Notebook

1. Acesse o notebook no [Google Colab](link_para_o_colab).
2. Certifique-se de que os dados estão disponíveis via API ou upload.
3. Instale as bibliotecas necessárias:

```python
!pip install pandas plotly seaborn

