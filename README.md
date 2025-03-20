# 📊 Projetos de Preparação de Dados - Ciência de Dados (CCD)

Bem-vindo(a) ao repositório de Projetos de Preparação de Dados! 🚀 Este espaço reúne códigos e práticas fundamentais para o tratamento, transformação e preparação de dados, pilares essenciais da Ciência de Dados. Durante o desenvolvimento destes projetos, são aplicadas técnicas cruciais como limpeza de dados, normalização, codificação e o tratamento de valores ausentes e duplicados.

---

## 🎯 Objetivo

O objetivo deste repositório é fornecer exemplos práticos e replicáveis para estudantes e profissionais que desejam aprender ou reforçar suas habilidades na preparação de dados.

---

## 🛠️ Tecnologias Utilizadas

As principais ferramentas e bibliotecas utilizadas neste repositório incluem:

- **pandas**: Manipulação e análise de dados.
- **numpy**: Operações numéricas e transformações matemáticas.
- **scipy.stats**: Aplicação de estatísticas avançadas.
- **sklearn.preprocessing**: Normalização, padronização e codificação de dados.

---

## 🚀 Como Reproduzir o Projeto

### 🔹 Clone o repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 🔹 Crie um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate  # Para Windows
```

### 🔹 Instale as dependências
```bash
pip install -r requirements.txt
```

### 🔹 Execute os notebooks ou scripts conforme necessário.

---

## 📂 Estrutura dos Projetos

Este repositório está organizado em módulos independentes, cada um cobrindo uma etapa específica da preparação de dados.

### 1️⃣ Inspeção e Tratamento Inicial dos Dados
**🔍 Objetivo:** Carregar e analisar os dados, verificando estrutura, tipos e valores ausentes.

**🛠️ Ferramentas:** `pandas`

**🔹 Etapas:**
- Leitura de arquivos CSV
- Visualização de amostras iniciais e finais
- Verificação de tipos de dados e valores ausentes

---

### 2️⃣ Codificação de Variáveis Categóricas
**🔍 Objetivo:** Converter variáveis categóricas em formatos numéricos adequados à modelagem.

**🛠️ Ferramentas:** `pandas`, `sklearn.preprocessing.LabelEncoder`

**🔹 Etapas:**
- **One-Hot Encoding** para **"estado civil"**
- **Codificação Ordinal** para **"nível educacional"**
- **Label Encoding** para **"estado"**

---

### 3️⃣ Transformações Matemáticas
**🔍 Objetivo:** Aplicar transformações para melhorar a distribuição dos dados numéricos.

**🛠️ Ferramentas:** `numpy`, `scipy.stats`

**🔹 Etapas:**
- **Transformação Logarítmica**
- **Transformação Box-Cox**

---

### 4️⃣ Conversão de Tipos e Tratamento de Dados Faltantes
**🔍 Objetivo:** Ajustar tipos de dados e tratar valores nulos e duplicados.

**🛠️ Ferramentas:** `pandas`

**🔹 Etapas:**
- **Conversão de formatos de data**
- **Identificação e remoção de valores nulos**
- **Eliminação de duplicatas**
- **Salvamento dos dados processados em CSV**

---

### 5️⃣ Normalização e Padronização
**🔍 Objetivo:** Ajustar escalas numéricas para otimizar o desempenho de modelos.

**🛠️ Ferramentas:** `sklearn.preprocessing.MinMaxScaler`, `sklearn.preprocessing.StandardScaler`, `sklearn.preprocessing.RobustScaler`

**🔹 Etapas:**
- **Normalização Min-Max**
- **Padronização** *(média = 0, desvio padrão = 1)*
- **Padronização robusta** *(baseada no IQR)*

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar **pull requests**.

---

## 📜 Licença

Este projeto está licenciado sob a **GNU General Public License v3.0**.

---

## 📬 Contato

Se tiver dúvidas ou sugestões, entre em contato por e-mail: **Artymente@outlook.com.br**

---

🚀 **Explore os projetos e aprimore suas habilidades em Ciência de Dados!**

