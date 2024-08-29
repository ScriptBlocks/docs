# Chapitre 29 : Introduction au Web Scraping

Le web scraping consiste à extraire des données des sites web. Les bibliothèques `requests` et `BeautifulSoup` de Python sont couramment utilisées à cet effet.

## Exemple

```python
import requests
from bs4 import BeautifulSoup

response = requests.get('http://example.com')
soup = BeautifulSoup(response.text, 'html.parser')

print(soup.title.text)  # Affiche le titre de la page
```