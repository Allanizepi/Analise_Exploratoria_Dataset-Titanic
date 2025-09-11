# An-lise-explorat-ria-Dataset-Titanic
Foi realizada uma análise exploratória dos dados sobre o desastre do navio Titanic, e assim, foi possível chegar a boas conclusões e entendimentos sobre o assunto.
## 📊 Análise Exploratória dos Dados (EDA)

A análise exploratória teve como objetivo compreender melhor as características do dataset do Titanic e identificar padrões que possam estar relacionados à sobrevivência dos passageiros.  

### 🔎 1. Inspeção inicial
- Verificação do número de linhas e colunas.  
- Identificação dos tipos de dados de cada coluna.  
- Contagem de valores ausentes (`Age`, `Cabin` e `Embarked` apresentam nulos).  

### ⚰️ 2. Distribuição de sobreviventes
- Aproximadamente **38% dos passageiros sobreviveram** e **62% não sobreviveram**, evidenciando um forte desbalanceamento.  
- Essa distribuição foi representada em gráficos de barras e pizza.  

### 👩‍🦱 3. Relação entre sobrevivência e variáveis categóricas
- **Sexo:** A taxa de sobrevivência foi significativamente maior entre mulheres do que entre homens.  
- **Classe (Pclass):** Passageiros da primeira classe tiveram maior chance de sobrevivência do que os da segunda e terceira classes.  

### 🎂 4. Idade dos passageiros
- A maioria dos passageiros tinha entre **20 e 40 anos**.  
- Crianças pequenas apresentaram uma taxa de sobrevivência relativamente mais alta.  

### 💰 5. Tarifa paga (Fare)
- Sobreviventes tendiam a ter pago tarifas mais altas, o que sugere associação entre maior poder aquisitivo e chance de sobrevivência.  

### 🛠 6. Tratamento de valores faltantes
- `Age`: valores ausentes foram desconsiderados.  
---

✅ Essa análise inicial permitiu identificar que **sexo, classe e idade** foram fatores cruciais na taxa de sobrevivência, o que já direciona hipóteses para etapas posteriores de modelagem preditiva.

