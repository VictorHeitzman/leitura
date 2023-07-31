Na área de dados você encontra diversos modelos de arquivos contendo informações para ser tradada e entrega de forma legível.

A linguagem Python pode te ajudar com isso 💡

Hoje mostro como fazer a leitura de um arquivo .txt e criar um DataFrame a partir dele.

Os dados foram extraídos de um arquivo PDF, então as informações vieram apenas com os espaçamentos e sem cabeçalhos.

usando a biblioteca Pandas com a função 'pd.read_fwf()'
Ela pede três parâmetros obrigatórios ('dados', 'colspecs', 'names')

dados: É a fonte de dados a ser lida

colspecs: Seria o intervalo da posição do caractere inicial até a posição final de cada informação para criar uma coluna.

names: É uma lista contendo o nome de cada coluna

crie um Df a partir desses parâmetros passados e salva em .csv

Tutorial 📽

GitHub: https://lnkd.in/dABebxNP