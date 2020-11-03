# Altera pacote de objetos de uma request
Programa que altera os pacotes de uma determinada request.  

Exemplo: o programa busca todos os objetos de uma request e exibe junto com a informação do pacote atual, ao selecionar um objeto é possível alterar o pacote dele.  

Programa útil para subir objetos ABAP para o GitHub. A maioria dos programas são criados em pacote padrão ZDEV, porém ao se utilizar o ABAPGit é necessário informar um pacote para importar objetos. Nesse caso é só informar a request do desenvolvimento, e alterar o pacote dos objetos desejados para que sejam importados via ABAPGit.

## Exemplo de uso

Informar uma request workbench.
<img src="tela selecao.png" align="center">

É exibida a tela com todos os objetos encontrados na request, bem como a informação do pacote atual do objeto
<img src="tela alv 9000.png" align="center">

Caso seja clicado o botão "Modifica Pacote" sem estar selecionada nenhuma linha é exibida a mensagem de erro:
<img src="mensagem erro.png" align="center">

Ao ser selecionada uma linha ou mais e ser clicado o botão "Modifica Pacote", é exibido o pop-up para informar o novo pacote desejado:
<img src="tela informar novo pacote.png" align="center">
