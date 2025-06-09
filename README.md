# Web Scraping de Dados de Livros para Análise e Visualização

Este projeto tem como objetivo principal demonstrar o processo de web scraping para coletar dados de um catálogo online de livros, seguido pela análise exploratória e visualização dessas informações. O trabalho abrange desde a coleta automatizada dos dados até a organização em um formato estruturado, permitindo insights sobre tendências de preços e disponibilidade de estoque no mercado editorial.

Sobre o Conjunto de Dados

O conjunto de dados utilizado neste estudo é construído a partir de raspagem de dados (web scraping) do site books.toscrape.com. Este site é uma plataforma fictícia, desenvolvida especificamente para fins didáticos e prática de web scraping. Ele oferece um catálogo diversificado de livros, incluindo informações como título, link para detalhes, preço e status de estoque. Por ser um ambiente de aprendizado controlado, é ideal para aplicar técnicas de coleta e processamento de dados de forma ética e segura.

Etapas do Projeto

O desenvolvimento deste projeto seguiu as seguintes etapas principais:

Coleta dos Dados: Utilização das bibliotecas Python requests para fazer as requisições HTTP e BeautifulSoup para parsear o conteúdo HTML das páginas, extraindo as informações relevantes dos livros.
Exploração dos Dados: Realização de análises estatísticas descritivas (ex: df.describe() para preços) para entender a distribuição e as características dos dados. Foram criadas visualizações como histogramas para a distribuição de preços e gráficos de barras para a contagem de livros em estoque.
Armazenamento dos Dados: Os dados limpos e organizados foram exportados para formatos de arquivo comuns, como Excel (.xlsx) e CSV (.csv), facilitando o acesso e o compartilhamento para análises futuras.

Tecnologias Utilizadas

Python 3: Linguagem de programação principal.
requests: Para fazer requisições HTTP e obter o conteúdo das páginas web.
BeautifulSoup: Para parsear o HTML e extrair os dados.
pandas: Para manipulação, limpeza e análise dos dados em formato de DataFrame.
matplotlib: Para a criação de gráficos e visualizações.
seaborn: Para gráficos estatísticos mais atraentes e complexos.

Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, detetar bugs ou quiser adicionar novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.
