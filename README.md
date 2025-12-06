# 🩺 Análise Integrada: VIGITEL 2023 e SIM 2023  
### Estudo sobre atividades físicas, pressão alta e causas de óbito no Brasil

Este repositório contém dois estudos complementares utilizando bases oficiais de saúde brasileiras:

- **VIGITEL 2023** → Comportamentos de saúde da população adulta  
- **SIM 2023 (DO23OPEN)** → Causas de óbito no Brasil  

O objetivo é entender padrões de atividade física, prevalência de hipertensão e como esses fatores dialogam com o perfil de mortalidade do país.

Todo o processo, da limpeza dos dados às visualizações e insights, está documentado nos notebooks deste repositório.

---

## ▶️ Como Reproduzir

1. **Instale as dependências**
   ```bash
   !pip install pandas matplotlib seaborn numpy

📥 Download dos Dados

Os dados são públicos, mas muito grandes para serem armazenados no GitHub.
Baixe diretamente das fontes oficiais:

VIGITEL 2023
Arquivo: Vigitel-2023-peso-rake.xlsx
Link: (https://drive.google.com/file/d/10BB9hoax2bkMVmpkTTtOuesn3yNTo90T/view?usp=drive_link)

SIM 2023 – DO23OPEN.csv
Arquivo: DO23OPEN.csv
Link: (https://drive.google.com/file/d/1QTfJriBGu25cxXutjgyJr5run7Benh3x/view?usp=drive_link)

📓 Notebooks e Conteúdo
1️⃣ VIGITEL_2023.ipynb

Contém:

Limpeza completa da base

Conversão de códigos em variáveis interpretáveis

Criação de faixas etárias

Mapeamento dos tipos de exercício

Análise:

prática de atividade física por idade

distribuição dos tipos de exercício

hipertensão vs exercício

top exercícios entre pessoas hipertensas

Inclui explicações metodológicas em Markdown.

2️⃣ SIM_2023.ipynb

Contém:

Cálculo de faixas etárias

Identificação dos CIDs mais comuns por faixa

Top 6 CIDs por faixa etária (gráfico empilhado)

Filtros por grupos de causa

Validação das tendências observadas

Também inclui descrições claras no notebook.

📈 Principais Insights
🔹 Do VIGITEL 2023:

Adultos mais jovens praticam mais atividade física regularmente.

Caminhada, musculação e corrida são os três tipos de exercício mais prevalentes.

Pessoas com hipertensão ainda fazem atividade física, mas tendem mais a exercícios de baixo impacto (caminhada, alongamento, hidro).

Faixas acima de 50 anos apresentam maior proporção de hipertensos, independentemente da prática esportiva.

🔹 Do SIM 2023:

As causas cardiovasculares são predominantes entre idosos.

Entre jovens adultos (20–39), predominam causas externas (acidentes, violência).

A partir dos 50 anos surgem com força doenças crônicas (cardíacas, respiratórias, metabólicas).

A divisão etária por décadas evidencia mudanças bruscas no perfil de mortalidade.

Todos esses achados refletem e reforçam o relatório científico gerado no estudo.

📌 Observação

Este projeto foi produzido no contexto acadêmico e utiliza dados públicos.
Sinta-se livre para reutilizar o código para fins de estudo ou extensão analítica.
