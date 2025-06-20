# desafio_Controle-Investimentos-Excel-dio
Projeto desenvolvido como parte do bootcamp "Santander - Excel com Inteligência Artificial", proposto pela DIO.

# 📈 Simulador de Investimentos - Excel

## 📝 Descrição

Este projeto foi desenvolvido como parte do Bootcamp da DIO para criação de uma ferramenta prática no Excel que simula investimentos.  
A planilha permite ao usuário inserir parâmetros simples e visualizar projeções do total investido, patrimônio acumulado e dividendos mensais estimados de forma automatizada e intuitiva.

---

## 🚀 Funcionalidades

- Entrada de dados personalizável:
  - ✔️ Aporte Inicial (R$)
  - ✔️ Aporte Mensal (R$)
  - ✔️ Período de Investimento (Meses)
  - ✔️ Taxa de Rendimento Mensal (%)

- Cálculos automáticos:
  - ✔️ Total Investido ao final do período;
  - ✔️ Valor Futuro Total (Patrimônio acumulado);
  - ✔️ Estimativa de Dividendos Mensais baseada no rendimento informado.

---

## 🛠️ Como Utilizar a Planilha

1. Abra o arquivo **`Desafio_Excel_.xlsx`**.
2. Localize a área destacada de entrada de dados.
3. Preencha os seguintes campos:
   - Aporte Inicial (em R$);
   - Aporte Mensal (em R$);
   - Período de Investimento (em meses);
   - Taxa de Rendimento Mensal (%).
4. Os resultados serão calculados automaticamente e exibidos nos campos:
   - **Total Investido** (Aporte Inicial + Aportes Mensais);
   - **Valor Futuro Total** (considerando juros compostos);
   - **Dividendos Mensais Estimados** (com base na taxa de rendimento).

---

## 📊 Fórmulas Utilizadas

- **Valor Futuro (VF)**:

  ```
  =VF(Taxa de Rendimento; Número de Meses; -Aporte Mensal; -Aporte Inicial)
  ```

- **Total Investido**:

  ```
  =Aporte Inicial + (Aporte Mensal * Número de Meses)
  ```

- **Dividendos Mensais Estimados**:

  ```
  =Valor Futuro Total * Taxa de Rendimento
  ```

---

## 🧰 Tecnologias Utilizadas

- Microsoft Excel 
- Funções financeiras:
  - VF (Valor Futuro)
  - Cálculo de juros compostos
  - Estimativa de Dividendos

---

## 👩‍💻 Autora

**Mara Costa**  
Bootcamp: Inteligência Artificial Aplicada a Dados - DIO  
