# Leitor (PDF)

O seguinte Modelo tem com objetivo realizar leitura de arquivos com extensão ".pdf"

Para os arquivos pdf de origem utiliza-se a biblioteca pdfplumber; já os arquivos scaneados em formato pdf são lido mediante a biblioteca pytsseract(OCR).

Esse modelo é um pequeno exemplo de um modelo real que desenvolvi para um projeto, o qual realiza a leitura do pdf e entrega um arquivo xml. Logos as nota fiscaisde serviço são lidas e transformadas em xml e entregues para leitura do ERP.

Após a coseguir realizar a leitura do arquivo podemos realizar manipulação dos dados que serão entregues no tipo "str". Sendo assim, podemos utilizar a biblioteca re(Expressões Regulares). Utilizarei com exemplo duas notas fiscais fictícias, as quais estão em pdf. A primeira é um pdf scaneado e a segunda é um arquivo de origem.


