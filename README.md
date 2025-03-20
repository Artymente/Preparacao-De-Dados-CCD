# 📊 Projetos de Preparação de Dados – Ciência de Dados

Bem-vindo(a) ao repositório de Projetos de Preparação de Dados! 🚀


## 🎯 Objetivo

Este repositório tem como propósito oferecer exemplos práticos e reutilizáveis para estudantes e profissionais que desejam consolidar suas habilidades em preparação de dados.

## 🛠️ Tecnologias Utilizadas

As principais ferramentas e bibliotecas utilizadas incluem:

- 📌 **pandas** – Manipulação e análise de dados
- 📌 **numpy** – Operações matemáticas e vetoriais
- 📌 **scipy.stats** – Aplicação de estatísticas avançadas
- 📌 **scikit-learn (sklearn.preprocessing)** – Normalização, padronização e codificação de dados

## 🚀 Como Reproduzir o Projeto

### 🔹 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 🔹 2. Crie um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

### 🔹 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 🔹 4. Execute os notebooks ou scripts conforme necessário

## 📂 Estrutura dos Projetos

O repositório está organizado em módulos independentes, abordando diferentes etapas da preparação de dados.

### 1️⃣ Inspeção e Tratamento Inicial dos Dados

📌 **Objetivo:** Carregar e analisar os dados, verificando estrutura, tipos e valores ausentes.
🛠 **Ferramentas:** pandas

🔹 **Principais etapas:**
- ✔ Leitura de arquivos CSV
- ✔ Visualização de amostras iniciais e finais
- ✔ Verificação de tipos de dados e valores ausentes

### 2️⃣ Codificação de Variáveis Categóricas

📌 **Objetivo:** Converter variáveis categóricas em formatos numéricos adequados à modelagem.
🛠 **Ferramentas:** pandas, sklearn.preprocessing

🔹 **Principais técnicas:**
- ✔ One-Hot Encoding – Para variáveis como "estado civil"
- ✔ Codificação Ordinal – Para variáveis como "nível educacional"
- ✔ Label Encoding – Para variáveis como "estado"

### 3️⃣ Transformações Matemáticas

📌 **Objetivo:** Melhorar a distribuição dos dados numéricos.
🛠 **Ferramentas:** numpy, scipy.stats

🔹 **Técnicas aplicadas:**
- ✔ Transformação Logarítmica
- ✔ Transformação Box-Cox

### 4️⃣ Conversão de Tipos e Tratamento de Dados Faltantes

📌 **Objetivo:** Ajustar tipos de dados e lidar com valores ausentes e duplicados.
🛠 **Ferramentas:** pandas

🔹 **Principais etapas:**
- ✔ Conversão de formatos de data
- ✔ Identificação e remoção de valores nulos
- ✔ Eliminação de duplicatas
- ✔ Salvamento dos dados processados em CSV

### 5️⃣ Normalização e Padronização

📌 **Objetivo:** Ajustar escalas numéricas para otimizar o desempenho de modelos de machine learning.
🛠 **Ferramentas:** sklearn.preprocessing

🔹 **Técnicas aplicadas:**
- ✔ Normalização Min-Max
- ✔ Padronização (média = 0, desvio padrão = 1)
- ✔ Padronização robusta (baseada no IQR – Intervalo Interquartil)

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para:

- Abrir uma issue
- Enviar um pull request

## 📜 Licença

Este projeto está licenciado sob a **GNU General Public License v3.0**.
---

## 📬 Contato

Se tiver dúvidas ou sugestões, entre em contato por e-mail: **Artymente@outlook.com.br**

---

🚀 **Explore os projetos e aprimore suas habilidades em Ciência de Dados!**

