### Scraper training
Welkom bij de Scraper training! We gaan vandaag leren:
1. Wat is webscraping?
2. Hoe je een scraper bouwt door middel van Selenium of BeautifulSoup

Voordat we beginnen is het belangrijk om een nieuwe environment aan te maken. Open hiervoor het programma Anaconda Prompt op je computer. 
```bash
conda create -n scraper-training python=3.12
```

Vervolgens activeer je de nieuw gemaakte environment.
```bash
conda activate scraper-training
```

Tot slot installeer je alle packages in de requirements file met pip.
```bash
pip install -r requirements.txt
```

Open nu een jupyter notebook. Als het goed is moeten alle benodigde packages nu zonder fouten kunnen worden geïmporteerd.
```bash
jupyter notebook
```