## Automação do processo de pesquisa, cálculo e edição de planilhas XLSX de logística
Script criado para automatizar o processo de pesquisa de dados, cálculo e edição das planilhas XLSX de logística. </br>
Como funciona:</br>
O time recebe 2 planilhas de transportadoras diferentes, recebe também um CSV com as informações atualizadas de rastreio das encomendas e possuem 1 planilha com informações de apoio de qual ação tomar de acordo com a quantidade de dias em atraso. </br>
O Script vai ler esses 4 arquivos, fazer o merge dos dados do CSV de Rastreio com os dados de ambas as planilhas das transportadoras pelo ID da encomenda. </br>
Vai calcular o aging desde a data que a encomenda está na transportadora até o dia atual. </br>
Depois de acordo com o aging vai procurar na planilha de apoio (como se fosse um procv do excel) qual ação deve tomar junto a transportadora.
### 📋 Pré-requisitos
Python mais recente, baixar em: https://www.python.org/downloads/ </br>
Bibliotecas: 
- requests
- pandas
- datetime
- CSV
### 🔧 Instalação
Para instalar as bibliotecas, use o código abaixo: </br>
`pip install requests` </br>
`pip install pandas` </br>
`pip install datetime`</br>
`pip install csv`</br>

### 🛠️ Construído com
Utilizei o Visual Studio para desenvolver e rodar o código. 

### 📱 Qualquer dúvida, sugestão ou elogio (rs..) Entre em contato comigo
e-mail: santostainads@gmail.com </br>

⌨️ com ❤️ por <a href="https://github.com/taidsantos">Tai Santos </a>  😊
