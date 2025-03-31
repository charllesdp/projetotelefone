Este script Python realiza web scraping no site "django-anuncios.solyd.com.br" para extrair números de telefone de anúncios de automóveis. Ele utiliza as bibliotecas requests, BeautifulSoup e re para buscar, analisar o HTML e encontrar padrões de números de telefone. O script também utiliza threads para acelerar o processo de extração.

Funcionalidades:

Extração de Links: Busca todos os links de anúncios de automóveis na página inicial.
Extração de Telefones: Analisa o conteúdo de cada anúncio para encontrar números de telefone usando expressões regulares.
Multithreading: Utiliza múltiplas threads para processar os anúncios simultaneamente, melhorando o desempenho.
Salvamento de Telefones: Salva os números de telefone encontrados em um arquivo CSV chamado "telefones.csv".
Requisitos:

Python 3.x
Bibliotecas: requests, BeautifulSoup4
Como executar:

Certifique-se de ter o Python e as bibliotecas necessárias instaladas.
Salve o código em um arquivo Python (por exemplo, scraper_telefones.py).
Execute o script a partir da linha de comando: python scraper_telefones.py
Observações:

O script pressupõe que os números de telefone estão presentes na descrição dos anúncios e seguem um padrão específico.
O uso de web scraping deve ser feito com responsabilidade, respeitando os termos de serviço do site e evitando sobrecarregar o servidor.
O uso de threads pode variar de acordo com a maquina que for utilizada.
