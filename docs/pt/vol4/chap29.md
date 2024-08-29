# Capítulo 29: Introdução ao Web Scraping

Web scraping envolve a extração de dados de sites. As bibliotecas `requests` e `BeautifulSoup` do Python são comumente usadas para isso.

## Exemplo

```python
import requests
from bs4 import BeautifulSoup

response = requests.get('http://example.com')
soup = BeautifulSoup(response.text, 'html.parser')

print(soup.title.text)  # Exibe o título da página
```