

## Introdução

Nesse tópico será explicado como utilizar a ferramenta de geração de templates. Ferramenta destinada para situação onde existe um template ja em uso, e deseja-se converter esse template para poder ser utilizado na extensão. 
  A conversão de um template em uso para um template preparado para extensão, é que o template preparado contém textos pre definidos que serão substituidos no momento da utilização do template. 


###  Gerando templates

  ** 1. Acessar a ferramenta "Convert to template" ** </br>
  Para começar, acesse as ferramentas de desenvolvimento: Clique com o botão direito na pasta que deseja converter em template e selecione a opção `extensionDevelop`.  Em seguida, abrirá uma janela contendo as opções de ferramentas disponiveis; nessa janela que abriu, selecione a opção `convertToTemplate`
  </br>

** 2. Definir valores que devem ser substituidos ** </br>
  A próxima etapa é informar quais textos do template devem ser substituidos pelo texto de marcação. Posteriormente, no momento de uso da extensão, os textos de marcação serão substituidos no momento da geração do template.  
  Após realizar o passo anterior e selecionar a opcão `convertToTemplate`, será aberto um campo de texto onde devem ser informados os textos maiusculo e minusculo a serem substituidos. Os textos devem ser separados por '/'.  </br> </br>
   Vamos pegar como exemplo um template com as seguintes classes: 
   </br> 
    LoginView(); 
    LoginController(); 
  
  No caso do exemplo, deveriamos inserir o valor "Login/login".  Obs: Em palavras compostas, todas as iniciais devem ser maiusculas/minusculas. 

   

