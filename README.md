# Vehicles Dashboard — Análise Exploratória e Aplicativo Web

## Descrição do Projeto
Projeto de análise e visualização de dados aplicado a um conjunto de dados de anúncios de vendas de carros. O objetivo principal foi realizar uma análise exploratória dos dados e desenvolver um dashboard interativo como aplicativo web, implantado em nuvem e acessível ao público.

**Acesse o aplicativo:** [Vehicles Dashboard — Render](https://car-analysis-cqed.onrender.com)

---

## Metodologia

1. **Configuração do ambiente**
   - Criação de ambiente virtual Python com os pacotes necessários e versionamento do projeto via Git/GitHub.

2. **Análise Exploratória de Dados (EDA)**
   - Carregamento e exploração do dataset em Jupyter Notebook, com criação de visualizações interativas (histogramas e gráficos de dispersão) usando `plotly-express`.

3. **Desenvolvimento do aplicativo web**
   - Construção de dashboard interativo com **Streamlit**, integrando gráficos dinâmicos acionados por botões e caixas de seleção.

4. **Deploy em nuvem**
   - Configuração e implantação do aplicativo no **Render**, tornando o dashboard acessível publicamente via URL.

---

## Funcionalidades do Aplicativo

- Histograma interativo da distribuição da quilometragem dos veículos
- Gráfico de dispersão entre quilometragem e preço
- Controles via botões e checkboxes para geração dinâmica dos gráficos

---

## Tecnologias e Ferramentas

- **Linguagem:** Python
- **Bibliotecas:** pandas, plotly-express, streamlit
- **Ambiente:** VS Code, ambiente virtual Python
- **Versionamento:** Git / GitHub
- **Deploy:** Render (serviço de nuvem)
- **Notebook:** Jupyter Notebook (EDA.ipynb)

---

## Estrutura do Repositório

- `notebooks/EDA.ipynb` — análise exploratória dos dados
- `streamlit/config.toml` — configuração para deploy no Render
- `.gitignore` — arquivos e diretórios ignorados pelo Git
- `README.md` — este arquivo
- `app.py` — aplicativo web Streamlit
- `requirements.txt` — dependências do projeto
- `vehicles.csv` — dataset de anúncios de venda de carros


---

## Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/wspdata/Vehicles-Dashboard

# Crie e ative o ambiente virtual
python -m venv vehicles_env
source vehicles_env/bin/activate  # Linux/Mac
vehicles_env\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute o aplicativo
streamlit run app.py
```

---

## Contato

Willian De Souza Pereira — ws13292@gmail.com

LinkedIn: https://linkedin.com/in/willian-de-souza-pereira-b69109202

---

## Licença

Este repositório está disponível para estudo e demonstração. Sinta-se à vontade para clonar, adaptar e abrir *issues* com dúvidas ou sugestões.
