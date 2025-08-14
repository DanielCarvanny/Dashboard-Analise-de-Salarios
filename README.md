# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um **Dashboard Interativo** desenvolvido  em **Python** como parte da **Imersão de Dados com Python da Alura**, utilizando **Plotly** e **Streamlit**, para explorar e visualizar informações sobre salários na área de dados.  
O objetivo é fornecer uma ferramenta prática e intuitiva para análise exploratória, auxiliando na identificação de padrões, tendências e insights.

---

## 🚀 Tecnologias Utilizadas

- **Python** – Linguagem principal do projeto
- **Pandas** – Manipulação e tratamento de dados
- **Plotly** – Criação de gráficos interativos
- **Streamlit** – Desenvolvimento do dashboard web
- **NumPy** – Operações matemáticas e estruturais (se aplicável)
- **Jupyter Notebook / Google Colab** – Exploração inicial dos dados (opcional)

---

## 📂 Estrutura do Projeto
```
Dashboard-Analise-de-Salarios/
│
├── dados-imersao-final.csv # Base de dados utilizada
├── app.py # Arquivo principal do dashboard Streamlit
├── requirements.txt # Lista de dependências do projeto
└── README.md # Documentação do projeto
```

---

## 📈 Funcionalidades

- Visualização interativa de salários por cargo, nível e localização
- Filtros dinâmicos para explorar subsets de dados
- Análise de distribuição salarial
- Comparação entre diferentes áreas e níveis de experiência
- Geração de gráficos interativos (barras, dispersão, boxplots, etc.)

---

## 💾 Como Executar o Projeto Localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/DanielCarvanny/Dashboard-Analise-de-Salarios.git
```

### 2️⃣ Criar e ativar um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### 3️⃣ Instalar as dependências
```bash
pip install -r requirements.txt
```
### 4️⃣ Executar o dashboard
```bash
streamlit run app.py
```
Após rodar o comando, abra o link gerado no terminal (geralmente http://localhost:8501) no navegador.

---
✍️ Autor: Daniel Carvanny
