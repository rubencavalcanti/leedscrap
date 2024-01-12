#Projeto de Web Scraping do Google Shopping

##Descrição

Este projeto consiste em um script Python para realizar Web Scraping de resultados de pesquisa no Google Shopping com base em um termo específico. O script busca links de produtos e extrai domínios associados a esses links, oferecendo uma visão geral dos sites que oferecem produtos relacionados ao termo de pesquisa.

##Funcionalidades

- Realiza consultas ao Google Shopping com um termo de pesquisa especificado.
- Coleta links de produtos da página de resultados de pesquisa.
- Extrai domínios associados a esses links.
- Filtra e armazena os domínios encontrados em um arquivo CSV.
- Permite personalizar palavras-chave para filtrar domínios específicos.
  
##Como Usar

- Clone o repositório para o seu ambiente local.
- Instale as dependências necessárias listadas no arquivo requirements.txt.
- Execute o script Python main.py.
- Consulte os domínios extraídos no arquivo CSV links.csv gerado.

##Requisitos

- Python 3.x

- Bibliotecas Python: requests, beautifulsoup4, time, random, csv

##Configurações

- Defina o termo de pesquisa desejado no arquivo main.py na variável termo_pesquisa.

- Personalize as palavras-chave de filtragem no mesmo arquivo na lista palavras_chave.

##Observações

- Este script faz uso de scraping para obter dados do Google Shopping. Respeite os Termos de Serviço e a Política de Uso do Google.

- Modifique e utilize este script com responsabilidade e ética, considerando as políticas de privacidade e direitos autorais.

##Contribuição

- Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, reportar problemas ou abrir pull requests.

##Autor

Guilherme Montanher - https://github.com/gmontanher

Rúben Cavalcanti - https://github.com/rubencavalcanti

Moises Goulart - https://github.com/Moisesopg
