

## 웹크롤링

웹에서 정보 가져오기

```python
import requests
from bs4 import BeautifulSoup

kospi_url = 'https://finance.naver.com/sise/'
res = requests.get(kospi_url).text
soup = BeautifulSoup(res, 'html.parser')
text = soup.select_one('#KOSPI_now').text

print(text)
```



