# 📊 Detecção de Anomalias em Dados de Telemetria

## 🧠 Sobre o projeto
Este projeto foi desenvolvido com o objetivo de explorar, na prática, como dados de telemetria podem ser utilizados para identificar padrões e detectar possíveis anomalias em ambientes operacionais.

A ideia surgiu a partir do interesse em entender melhor como a análise de dados pode ser aplicada em contextos industriais, como no monitoramento de equipamentos. O projeto também foi inspirado em desafios reais de análise de dados, como os propostos em programas de desenvolvimento da indústria.

A proposta consiste em simular o monitoramento de equipamentos a partir de variáveis como temperatura, vibração e uso da máquina, buscando identificar comportamentos fora do padrão.

---

## 🎯 Objetivo
Construir uma solução simples para:
- Analisar dados ao longo do tempo  
- Identificar desvios de comportamento  
- Gerar alertas básicos (Normal, Atenção e Crítico)  

---

## ⚙️ Como funciona
O projeto utiliza conceitos básicos de estatística para identificar anomalias:

- **Média** → comportamento esperado  
- **Desvio padrão** → variação dos dados  
- **Z-score** → distância de cada valor em relação ao padrão  

A análise considera múltiplas variáveis simultaneamente (temperatura, vibração e uso da máquina). Para cada instante, é avaliado o maior desvio entre elas, permitindo identificar situações de risco mesmo quando apenas um dos sensores apresenta comportamento anômalo.

Com base nisso, cada ponto é classificado como:
- 🟢 Normal  
- 🟡 Atenção  
- 🔴 Crítico  

---

## 🏭 Contexto aplicado
Em ambientes industriais, equipamentos geram dados continuamente. Variações fora do padrão podem indicar desgaste, falhas ou uso inadequado.

A identificação antecipada dessas anomalias permite:
- Reduzir falhas inesperadas  
- Melhorar a manutenção preventiva  
- Aumentar a eficiência operacional  

---

## 📊 Dados utilizados
Os dados são simulados e representam:
- Temperatura de equipamento  
- Vibração  
- Nível de utilização  

Foram inseridas anomalias artificiais para simular possíveis falhas e validar a lógica de detecção.

---

## 🛠️ Tecnologias utilizadas
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Excel (análise complementar)

---

## 📈 Resultados
A solução permite:
- Visualizar o comportamento dos dados ao longo do tempo  
- Identificar pontos fora do padrão  
- Gerar alertas simples para apoio à tomada de decisão  

---

## 📚 Aprendizados
Durante o desenvolvimento deste projeto, foram explorados conceitos como:
- Análise exploratória de dados (EDA)  
- Estatística aplicada  
- Identificação de padrões  
- Lógica de detecção de anomalias  
- Importância do contexto na análise de dados  

---

## 🚀 Possíveis melhorias
- Utilização de dados reais  
- Implementação de modelos de machine learning  
- Integração com sistemas em tempo real  
- Escalabilidade em ambientes de Big Data  

---

## 👨‍💻 Autor
João Pedro Maniezi

---

## 📷 Visualizações

### 📉 Análise em Python
![Gráfico Python](https://github.com/user-attachments/assets/88dcdfea-9989-492e-9e12-e20906bfebb1)

### 📊 Análise no Excel
![Análise Excel](https://github.com/user-attachments/assets/b0eb5dfb-a818-4689-bb42-78d130ae88b2)
