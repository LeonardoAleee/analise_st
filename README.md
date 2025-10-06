# Modelagem da variável 'Volume'

Este repositório contém todo o material de apoio — código, dados e o relatório  — resultante da análise e modelagem da variável `volume`.

---

## Objetivo Principal

O projeto visa desenvolver um **modelo preditivo robusto e interpretável** para a variável `volume`, abordando suas características temporais, sazonalidade e tendências.

## Metodologia Aplicada

O trabalho seguiu um *pipeline* metodológico rigoroso e validado em Séries Temporais:
1.  **Pré-processamento:** Aplicação da **Transformação Box-Cox** para estabilização da variância.
2.  **Análise Estrutural:** Uso da **Decomposição STL** (*Seasonal-Trend decomposition using Loess*) para identificar e isolar os componentes de tendência e sazonalidade.
3.  **Modelagem:** Desenvolvimento de **Modelos Baseline** e posterior construção de uma **Regressão Linear Múltipla (RLM)** utilizando *features* derivadas.

**O resultado final foi um modelo com $\mathbf{R^2 = 0.983}$ e resíduos estatisticamente bem comportados.**
