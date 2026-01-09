# Modelo Preditivo para o Fechamento IBOVESPA

Este projeto consiste no desenvolvimento de um modelo preditivo para o índice IBOVESPA, a principal referência do mercado acionário brasileiro. O objetivo é prever o valor de fechamento oficial do índice, utilizando técnicas de análise de séries temporais e garantindo uma acurácia superior a 70% para suporte à tomada de decisão financeira.

### Pré-requisitos

Certifique-se de ter o Python 3.11 instalado em seu sistema.

Para sistemas baseados em Linux (Ubuntu/Debian), instale o suporte ao ambiente virtual:

```bash
sudo apt update && sudo apt install python3.11-venv
```

### Instalação

Siga os passos abaixo para configurar o ambiente e instalar as dependências:

```bash
#clonar o repositório
git clone https://github.com/jorgeplatero/previsao-ibovespa.git
cd postech-data-analytics-techchallenge-fase-2

#criar o ambiente virtual
python -m venv venv

#ativar o ambiente virtual
# No Linux/Mac:
source venv/bin/activate
# No Windows:
venv\Scripts\activate

#instalar as dependências
pip install -r requirements.txt
```

### Como Executar o Modelo

Com o ambiente virtual ativado, você pode executar o script principal ou abrir o notebook de análise para visualizar o storytelling e os resultados:

```bash
# Para executar o script principal
python main.py

# Ou para abrir o Jupyter Notebook
jupyter lab
```

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **ML** | **Statsforecast** | `1.6.0` | Biblioteca para desenvolvimento de modelos de ML |
| **Análise de Dados** | **Pandas** | `2.2.1` | Biblioteca para manipulação de dados |
| **Visualização** | **Plotly** |`5.20.0` | Biblioteca para criação de gráficos dinâmicos e interativos |
| **Linguagem** | **Python** | `>=3.11` | Linguagem para desenvolvimento de scripts |
| **Gerenciamento** | **Venv** | `-` | Gerenciador de ambientes virtuais para isolamento de dependências 

### Fontes de Dados

Os dados históricos utilizados foram extraídos do site Investing.

Link para a base de dados: https://br.investing.com/indices/bovespa-historical-data

### Colaboradores

[Mateus Albuquerque](https://github.com/mateus-albuquerque)

[Adrielly Silva](https://github.com/adriellytsilva)
