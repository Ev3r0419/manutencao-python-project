# manutencao-python-project

#O projeto se chama "Help Desk - Notebook Manager"

#Criado para gerenciar equipamentos (notebooks) que necessitam de manutenção e realizar a mediação com as assistências técnicas sobre os notebooks que já estão em fase de conserto. 
O objetivo é simplificar a maneira de armazenamento e consulta dos dados sem a necessidade visual e complexa de uma planilha, evitando erros que podem ser cometidos, sejam eles de escrita ou até mesmo por falta de algum dado considerado importante.

#Foi criado em Python e utiliza diversas bibliotecas sendo uma delas a "gspread", uma API que faz a comunicação do Python com o Google Sheets, onde atualmente funciona como um banco de dados.

#Na aplicação encontramos algumas funções, sendo elas:
- Adicionar manutenção; (Adiciona os dados solicitados na aba de "Máquinas em manutenção" na planilha do Google.)
- Adicionar conserto;  (Adiciona os dados solicitados na aba de "Máquinas com necessidade de conserto" na planilha do Google.)
- Excluir Patrimônio; (Faz a exclusão das máquinas do banco de dados a partir do patrimônio inserido.)
- Filtrar manutenções; (Realiza o filtro dos notebooks em manutenção por Técnico atribuído, patrimônio da máquina e assistência técnica.)
- Filtrar consertos; (Realiza o filtro dos notebooks em manutenção por Técnico atribuído e patrimônio da máquina.)
- Sair. (Encerra o programa.)

