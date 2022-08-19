# JoinPDFpages
 Join different PDF pages in one file

Criei esse executável, para poder juntar as páginas em um único arquivo em PDF.

Foram utilizadas as bibliotecas:
<br>-FILEDIALOG(TKINTER) - para selecionar a pasta com os arquivos em PDF no computador
<br>-PDFFILEREADER(PYPDF2) - para ler o arquivo em PDF
<br>-MESSAGE BOX (TKINTER) - Para informar ao usuário que o arquivo PDF unificado foi gerado
<br>-PATHLIB (para criar uma pasta, no local onde os arquivos em PDF se encontram, para o arquivo unificado ser salvo)

...todo esse projeto foi realizado no JUPYTER NOTEBOOK (pela facilidade em executar os códigos por partes).
<br>Foi necessário salvar o arquivo na extensão .py, para que a biblioteca usada posterior (PYINSTALLER) pudesse ler esse arquivo
<br>Criei um AMBIENTE VIRTUAL, para poder instalar as bibliotecas necessárias(citadas acima), para que o arquivo final não ficasse pesado (devido bibliotecas desnecessárias, instaladas no meu computador)
<br>Para a criação do arquivo executável, foi utilizada a biblioteca PYINSTALLER.


***Obs. O arquivo PDF unificado será salvo na pasta onde os arquivos estão localizados. A ordenação das páginas será de acordo com a numeração dos arquivos sequencialmente
