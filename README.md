# Planejamento Fatorial \(2^3\) e Modelagem por Regressão Linear Múltipla no Fresamento CNC

##  Descrição
Este projeto explora a influência de três fatores principais do processo de fresamento CNC:
- **Velocidade do eixo (Spindle speed)**
- **Taxa de avanço (Feed rate)**
- **Profundidade de corte (Depth of cut)**

Utilizando um planejamento fatorial completo \(2^3\), o estudo busca compreender os efeitos individuais e interações desses fatores sobre a variável dependente **Dimensão da Moagem (D)**. Um modelo de regressão linear múltipla foi ajustado para explicar a variabilidade da variável resposta.

---

##  Metodologia
### 1. **Planejamento Experimental**
- Modelo fatorial completo \(2^3\) com 125 combinações experimentais.
- Objetivo: Identificar efeitos significativos e otimizar os parâmetros do processo.

### 2. **Análises Estatísticas**
- Análise descritiva dos dados coletados.
- Testes de significância para identificar variáveis relevantes.

### 3. **Modelagem**
- Aplicação de regressão linear múltipla:
  \[
  D = \beta_0 + \beta_1 \cdot \text{Depth of cut} + \beta_2 \cdot \text{Spindle speed} + \beta_3 \cdot \text{Feed rate}
  \]
- Avaliação com métricas como \(R^2\) ajustado, valores \(p\), e testes de significância.

---

##  Resultados Principais
- **Fatores significativos**: "Depth of cut" e "Spindle speed" apresentaram impacto estatisticamente relevante na variável resposta.
- **R² Ajustado**: 30.76% da variabilidade foi explicada pelo modelo.
- **Interpretação dos resultados**:
  - **Depth of cut**: Principal fator influenciador na resposta.
  - **Feed rate**: Não apresentou significância estatística.

---

##  Conclusões
- O planejamento fatorial e a regressão múltipla forneceram insights sobre como otimizar os parâmetros de fresamento CNC.
- Sugestões incluem:
  - Aplicação de técnicas como delineamento fatorial fracionado.
  - Validação cruzada para maior robustez do modelo.

---

##  Referências
- Sahoo, P., Barman, T.K. "ANN modelling of fractal dimension in machining." *Woodhead Publishing* (2012).
- Montgomery, D.C. "Design and Analysis of Experiments." 2ª edição, Wiley (1984).
