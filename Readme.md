# IMDB Popular Movies Scraper
Este script em Python extrai informações sobre os 100 filmes mais populares do site IMDB e as escreve em um arquivo CSV chamado ‘movies.csv’.

<br>

## Requisitos
- Python 3
- Bibliotecas: requests, beautifulsoup4, concurrent.futures

Você pode instalar as bibliotecas necessárias usando o seguinte comando:
```
pip install requests beautifulsoup4
```

<br>

## Uso
Para executar o script, navegue até o diretório onde ele está localizado e execute o seguinte comando:
```
python multiThreading.py
```
O script fará solicitações HTTP para o site IMDB para obter as informações dos filmes e extrairá os detalhes relevantes usando a biblioteca BeautifulSoup. Ele usará multithreading para acelerar o processo de extração.

Quando o script for concluído, ele criará um arquivo CSV chamado ‘movies.csv’ no mesmo diretório, contendo informações sobre os 100 filmes mais populares do site IMDB. Cada linha do arquivo CSV conterá informações sobre um filme, incluindo título, data de lançamento, classificação e sinopse.