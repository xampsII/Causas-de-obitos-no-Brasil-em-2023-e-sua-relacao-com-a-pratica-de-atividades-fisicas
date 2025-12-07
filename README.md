# 🧠📊 Análise Integrada: VIGITEL 2023 e SIM 2023  
### Atividade Física, Hipertensão e Padrões de Mortalidade no Brasil

Este repositório apresenta uma análise exploratória de duas bases fundamentais para a compreensão da saúde pública brasileira:

- **VIGITEL 2023** → hábitos de saúde, prática de atividades físicas e prevalência de hipertensão na população adulta.  
- **SIM 2023 (DO23OPEN)** → causas de óbitos no Brasil, classificadas por CID-10.

Nosso objetivo foi identificar padrões de comportamento relacionados à atividade física e saúde, e entender como esses padrões se refletem nas principais causas de mortalidade.

---

## 🚀 Como Utilizar Este Repositório

1. **Baixe os arquivos originais das bases de dados:**
   - **VIGITEL 2023**  
   👉 **https://docs.google.com/spreadsheets/d/1WOcw0-7bJJoBh84R0DwxjCEdS84WfKxQ/edit?usp=drive_link&ouid=117913188683628553800&rtpof=true&sd=true**
   - **SIM 2023 – DO23OPEN.csv**  
   👉 **[LINK SIM 2023]()**

2. Coloque os arquivos na mesma pasta onde estão os notebooks.

3. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn numpy

Abra o notebook desejado:

VIGITEL_2023.ipynb

SIM_2023.ipynb

Execute as células na ordem e acompanhe as análises explicadas nos próprios notebooks.

📝 O que Cada Notebook Faz
📘 VIGITEL_2023.ipynb

Este notebook realiza:

Limpeza completa dos dados

Conversão das variáveis codificadas (q6, q7, q8a, q25…)

Construção de faixas etárias

Mapeamento de códigos de exercícios para nomes reais

Criação de indicadores:

prática de exercícios

tipo de exercício

presença de hipertensão

Geração dos gráficos:

prática de atividade física por idade

tipos de exercícios mais comuns

comparação entre hipertensos e não hipertensos

top exercícios entre hipertensos

Tudo é explicado em markdown dentro do notebook com metodologia clara.

📘 SIM_2023.ipynb

Este notebook contém:

Limpeza e reorganização da base de óbitos

Criação de faixas etárias padronizadas

Identificação dos CIDs mais frequentes por idade

Ranking geral de causas

Gráfico empilhado dos 6 CIDs mais prevalentes por faixa etária

Interpretação visual do perfil de mortalidade brasileiro

A análise conecta automaticamente idade → causa → padrão demográfico.

📊 Principais Insights da Análise
🔹 1. Prática de Atividade Física (VIGITEL)

Jovens entre 20 e 39 anos são os que mais praticam exercícios.

Comportamentos predominantes:

caminhada

musculação

corrida

A prática cai de forma consistente após os 50 anos.

🔹 2. Tipos de Exercícios por Idade

Jovens: corrida, musculação, esportes.

Meia-idade: caminhada, musculação moderada.

Idosos: caminhada e exercícios de baixo impacto (alongamento, hidro).

Isso revela uma transição natural em direção a exercícios menos intensos ao envelhecer.

🔹 3. Hipertensão

A prevalência cresce de forma acentuada a partir dos 50 anos.

Hipertensos tendem a praticar:

caminhada

hidroginástica

alongamento/pilates/ioga

Quase não aparecem em categorias de exercícios de alta intensidade.

Isso reforça um padrão preventivo ou restritivo típico de hipertensos.

⚰️ Principais Achados sobre Mortalidade (SIM 2023)
🔹 1. Jovens (10–39 anos)

Predominam:

causas externas

acidentes

agressões

intervenções legais

mortalidade por doenças é mínima

🔹 2. Adultos (40–59 anos)

Transição:

aumento de causas cardíacas

doenças metabólicas começam a aparecer

causas externas ainda têm impacto

🔹 3. Idosos (60+)

Clareza absoluta:

Doenças cardiovasculares são dominantes

Doenças respiratórias crescem

Complicações de diabetes e hipertensão aumentam fortemente

É a fase onde a mortalidade por causas evitáveis se torna mais evidente.

## 🧩 Conclusão

A integração dos dados do VIGITEL e do SIM revela uma conexão direta entre comportamento, condição de saúde e mortalidade ao longo do ciclo de vida.

- **Jovens** apresentam altos níveis de atividade física e baixa prevalência de doenças crônicas.  
- **Adultos**, especialmente após os 40, começam a reduzir a prática de exercícios e a apresentar aumento significativo nos casos de hipertensão.  
- **Idosos** concentram as maiores taxas de doenças cardiovasculares, metabólicas e respiratórias — refletindo padrões já observados nos hábitos e condições de saúde captados pelo VIGITEL.

No cruzamento com o SIM, esses padrões se confirmam de forma contundente:  
➡️ **A maior causa de morte no Brasil em 2023 foi o Infarto Agudo do Miocárdio (IAM).**

Esse achado reforça a importância da prevenção, do controle da hipertensão e da manutenção da atividade física ao longo da vida, já que os mesmos fatores que aparecem como comportamentos de risco no VIGITEL se manifestam como causas reais de mortalidade no SIM.

> **VIGITEL mostra o comportamento e os fatores de risco; SIM mostra o desfecho final.  
Ambas as bases convergem para o papel central da saúde cardiovascular no contexto brasileiro.**

