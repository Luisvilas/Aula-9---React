## Exercício React

* Baixar o arquivo de imagens
* Colocar esse arquivo na pasta public/assets
* Criar pasta components na pasta scr, e criar na pasta components um arquivo MenuComponent.js

Já no visual Code:
* Inserir todo o código nesse arquivo

1. As importações:
   * usestates- gerencia componentes dentro de outros componentes
   * media- exibe listas de imagens e textos juntos
     
2. Define a constante Menu para chamar os pratos:
   * dentro dessa constante ele chama outra constante chamada pratos ou dishes,
     essa que utiliza o import usestate, para utilizar listas de imagens e textos.
   * Dentro dessa mesma constante ele cria a lista de Menu em "dishes.map"
  
3. Na próxima linha de código ele renderiza a linha de código para a página.
  
4. E por último exporta o componente Menu.

-Esse código chama as imagens que estão na pasta public, e coloca na pagina.

-O código imita um cardápio de restaurante com descrições e imagens.

* Apagar tudo do arquivo App.css

No terminal da pasta confusion:
* git init para criar um repositorio
* git add .
* git commit -m "nome do arquivo"
* git remote add origin <url do git hub>
* git push -u origin master
Para subir os arquivos para o github
