Criar uma arquivo csv com o layout abaixo
Mes/Ano;Quantidade;Estado;Previsao
01/2023;1;SP;0
02/2023;20;SP;0
03/2023;3;SP;0
04/2023;50;SP;0
05/2023;10;SP;0
06/2023;10;SP;0
07/2023;25;SP;0
08/2023;25;SP;0
09/2023;147;SP;0
10/2023;5;SP;0
11/2023;10;SP;0
12/2023;1000;SP;0
01/2024;100;SP;0
02/2024;2;SP;0
01/2023;1;RJ;0
02/2023;20;RJ;0
03/2023;3;RJ;0
04/2023;50;RJ;0
05/2023;10;RJ;0
06/2023;10;RJ;0
07/2023;25;RJ;0
08/2023;25;RJ;0
09/2023;147;RJ;0
10/2023;5;RJ;0
11/2023;10;RJ;0
12/2023;1000;RJ;0
01/2024;100;RJ;0
02/2024;2;RJ;0
01/2024;100;MG;0
02/2024;2;MG;0


Acessar o site https://ml.azure.com
Acessar o seu Espaço de Trabalho (Senão tiver, crie)
Acessar na opção do menu esquerdo "ML automazido"
Clicar na opção "Novo trabalho de ML automazitado"
Informar nos campos:
  "Nome do trabalho" = previsaoAluguel
  "Nome do experimento" = Criar Novo
  "Novo nome do Experimento" = previsaoAluguel
  "Descrição" = Previsao dos alugueis
Clique em Avançar

Informe em "Selecionar tipo de tarefa" = Previsão de série temporal
Em "Selecionar os dados", clique em "+ criar"
Informe em "Nome" = previsaoAluguel
Informe em "Descrição" = Previsao dos alugueis
Informe em "Tipo" = Tabular
Clique em avançar

Clique em "De arquivos locais"
Em "Tipo de armazenamento de dados" informe "Azure Storage Blob
Clique em avançar

Informe o caminho do arquivo em "Carregar arquivo ou pasta"
Clique em avançar

"Formato de Arquivo" = Delimitado
"Delimitador" = Ponto e Vírgula
"Codificação" = Windows-1252
"Cabeçalhos de coluna" = Somente o primeiro arquivo tem cabeçalho
"Ignorar linhas" = Nenhuma
Clique em avançar

Deixe o default
Clique em avançar

Clique em criar

Selecione a fonte de dados criada.
Clique em avançar

"Coluna de destino" = Previsão
"Coluna de tempo" = Mes/Ano

Demais campos deixe default
Clique em avançar

Demais campos deixe default
Clique em avançar

