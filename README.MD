O programa funciona através das escolhas de 3 opções: Coletar AUTEFs, Coletar PMF e Coletar GF.

Caso escolha a coleta de AUTEFs, pode escolher entre coletar as ações junto com os produtos ou apenas as ações.
Caso escolha a coleta de PMF ele irá coletar as ações, uma vez que os produtos não estão disponíveis

Já a coleta de GF é um pouco diferente, pode-se escolher a coleta de ações, Xlsx ou apenas os produtos,
durante a coleta de ações também é possivel coletar os produtos, mas não é recomendavel pois os produtos
funcionam de uma forma que atrasa muito a coleta dos dados, por isso deve-se separa-los.

Para filtrar os dados por ano, quando solicitado, coloque o ano inicial seguido por um "-" e depois o ano final, exemplo 2021-2022

O programa salva o progesso de qual pagina parou nos arquivos "last_page.obj" para todas as coletas não referentes ao Xlsx
e no arquivo "last_page_xlsx.obj" para o Xlsx. Para recomeçar a coleta pode apagar este arquivo e recomeçará.

Na linha 12 do programa existe uma constante chamada P_COUNT, esse valor determina quantas paralelizações ocorrem ao mesmo tempo
O valor de 8 parece ser um bom valor para a coleta de ações e xlsx, mas para os produtos 16 funciona bem, se o programa estiver muito lento
ou falhando muito, pode mudar o valor para mais ou menos
