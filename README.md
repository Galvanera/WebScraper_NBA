Web Scraper de Estatísticas da NBA
Este repositório contém um script Python que utiliza Selenium para fazer scraping de estatísticas de jogadores da NBA no site da ESPN. O script acessa a página, extrai os dados desejados e os exibe no console.

Funcionalidades
Acesso Automático à Página: Utiliza Selenium para abrir a página de estatísticas de jogadores da NBA no site da ESPN.
Extração de Dados: Coleta as estatísticas dos jogadores listados na página.
Exibição dos Dados: Imprime as estatísticas dos jogadores no console.
Configuração Flexível: Pode ser executado em modo headless (sem interface gráfica) para maior eficiência.
Como Usar
Instale as bibliotecas necessárias:
pip install selenium openpyxl beautifulsoup4 pandas numpy

Baixe o WebDriver do Chrome:
Faça o download do ChromeDriver compatível com a versão do seu navegador Chrome.
Adicione o caminho do ChromeDriver ao seu PATH do sistema ou coloque o executável na mesma pasta do script.
Clone este repositório:
git clone https://github.com/seu-usuario/webscraper_nba.git
cd web-scraper-nba

Execute o script:
python scraper_nba.py
