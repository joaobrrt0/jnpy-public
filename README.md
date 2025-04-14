# jnpy-public

# Web Scraper com Selenium - Quotes to Scrape

Este projeto é um Web Scraper criado com **Python e Selenium** que coleta citações do site [Quotes to Scrape](http://quotes.toscrape.com/). Foram disponibilizadas duas versões do código:

- Versão para execução local com **Jupyter Notebook**
- ☁️ Versão pronta para **Google Colab**

---

## Tecnologias Utilizadas

- Python 3.11+
- Selenium
- Google Colab
- Jupyter Notebook
- Google Chrome e ChromeDriver

---

## Como Executar

### Opção 1: Localmente com Jupyter Notebook

1. Clone este repositório:
    ```bash
    git clone https://github.com/joaobrrt0/jpy.git
    cd jpy
    ```

2. Crie um ambiente virtual (opcional mas recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```

3. Instale os requisitos:
    ```bash
    pip install -r requirements.txt
    ```

4. Baixe o [ChromeDriver](https://sites.google.com/chromium.org/driver/) compatível com sua versão do Chrome e adicione ao PATH.

5. Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

6. Execute o notebook: `notebook/scraping_quotes_jupyter.ipynb`

---

### Opção 2: Google Colab (Recomendado)

> Não requer instalação de nada!

Clique no botão abaixo para abrir o projeto no Google Colab:

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bKAd9PvMQvimEVIty-CcNWpLM82HbB6g#scrollTo=b5648eee-250c-43c6-a422-9e36045167ac)

---

## Resultados

O scraper coleta:
- Citações
- Autores
- Tags associadas a cada citação

Os dados podem ser salvos como `.csv` ou utilizados diretamente no Python.

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## Contato

Caso tenha dúvidas ou sugestões:

- GitHub: [@joaobrrt0](https://github.com/joaobrrt0)
