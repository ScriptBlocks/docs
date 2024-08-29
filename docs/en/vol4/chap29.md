# Chapter 29: Introduction to Web Scraping

Web scraping involves extracting data from websites. Python's `requests` and `BeautifulSoup` libraries are commonly used for this.

## Example

```python
import requests
from bs4 import BeautifulSoup

response = requests.get('http://example.com')
soup = BeautifulSoup(response.text, 'html.parser')

print(soup.title.text)  # Outputs the title of the page
```