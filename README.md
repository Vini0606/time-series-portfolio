# Time Series Portfolio

Um projeto de análise e previsão de séries temporais com foco em fundamentos, decomposição e modelagem preditiva.

## 📋 Descrição

Este projeto implementa técnicas de análise de séries temporais, desde conceitos fundamentais até modelos avançados de previsão. É ideal para aprender e experimentar com dados temporais em Python.

## 🎯 Objetivos

- Explorar fundamentos de séries temporais
- Aplicar técnicas de decomposição de séries
- Desenvolver modelos de previsão
- Análise e visualização de dados temporais

## 📁 Estrutura do Projeto

```
time-series-portfolio/
├── notebooks/
│   ├── 01_fundamentos.ipynb      # Introdução a séries temporais
│   ├── 02_decomposicao.ipynb     # Decomposição e análise de componentes
│   └── 03_previsao.ipynb         # Modelos de previsão
├── data/
│   ├── raw/                      # Dados brutos originais
│   └── processed/                # Dados processados e tratados
├── scripts/
│   └── utils.py                  # Funções utilitárias
├── reports/                      # Relatórios e resultados
├── main.py                       # Ponto de entrada principal
├── pyproject.toml                # Configuração do projeto
└── README.md                     # Este arquivo
```

## 🛠️ Dependências

- **pandas**: Manipulação e análise de dados
- **numpy**: Operações numéricas
- **statsmodels**: Modelos estatísticos para séries temporais
- **matplotlib**: Visualização de dados
- **seaborn**: Visualizações estatísticas avançadas
- **openpyxl**: Manipulação de arquivos Excel
- **ipykernel**: Suporte para Jupyter notebooks

## 🚀 Instalação

### Pré-requisitos
- Python >= 3.11
- pip ou uv (recomendado)

### Configuração com uv

```bash
# Clonar o repositório
git clone <url-do-repositorio>
cd time-series-portfolio

# Criar e ativar ambiente virtual
uv venv
source .venv/bin/activate  # Linux/Mac
# ou
.venv\Scripts\activate     # Windows

# Instalar dependências
uv sync
```

### Configuração com pip

```bash
# Criar e ativar ambiente virtual
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows

# Instalar dependências
pip install -e .
```

## 📚 Como Usar

### Executar o script principal

```bash
python main.py
```

### Explorar os notebooks

1. **01_fundamentos.ipynb**: Comece aqui para entender os conceitos básicos
2. **02_decomposicao.ipynb**: Aprenda sobre decomposição de séries
3. **03_previsao.ipynb**: Desenvolva modelos de previsão

### Adicionar dados

Coloque seus arquivos CSV ou Excel em `data/raw/` e processe-os com os scripts disponíveis.

## 💾 Estrutura de Dados

### Raw Data (`data/raw/`)
Armazena os dados originais, sem modificações.

### Processed Data (`data/processed/`)
Contém dados após limpeza, transformação e tratamento.

## 📊 Exemplos

Os notebooks contêm exemplos completos de:
- Carregamento e exploração de séries temporais
- Visualização de trends, sazonalidade e ruído
- Aplicação de modelos ARIMA, exponencial smoothing e outros
- Validação e interpretação de previsões

## 🤝 Contribuições

Este é um projeto de portfólio. Sinta-se livre para:
- Adicionar novos notebooks
- Implementar novas técnicas
- Melhorar a documentação
- Compartilhar aprendizados

## 📝 Licença

Este projeto está disponível para uso educacional e de aprendizado.

## 📧 Contato

Para dúvidas ou sugestões, abra uma issue no repositório.

---

**Última atualização**: Abril de 2026
