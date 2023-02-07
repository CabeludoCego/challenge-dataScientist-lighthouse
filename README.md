AUTOR: LUCAS LEMOS CARVALHO BATISTA
DESAFIO DE DATA SCIENTIST DA LIGHTHOUSE (INCIDIUM)

Como rodar o projeto:

Python utilizado: 3.8.10. 
> Baixar bibliotecas necessários com pip install requirements.txt

Arquivo a rodar: Entrega_INCIDIUM_challenge_3.ipynb
> Basta rodar o arquivo inteiro.

Arquivos necessários: os "desafio_manutenção".csv. 

-------------------------------------------------

Descrição mais completa:

- Rodar o python notebook

1. Importa bibliotecas necessárias
 
2. Treinamento

	-> 2.1. Carrega e prepara o banco de dados (treino + teste fake, remover colunas sem dados úteis, SMOTE)

	-> 2.2. Cria o modelo

	-> 2.3. Treinamento do modelo

3. "Validação" manual: Utiliza parte do banco de Treino para realizar um teste "fake", que serve para averiguar o quão bom é o modelo.
> O model já realiza uma validação no model.fit. Mas tive o interesse de realizar uma por fora também.

4. Teste: Utiliza o banco de teste para submeter as 3333 amostras e determinar as classes de acordo com os dados apresentados.

	-> 4.1. Carrega e prepara o banco

	-> 4.2. Classifica o banco

	-> 4.3. Converte a classificação de volta para as classes em String + cria o predicted.csv.
