## Calculadora básica desenvolvida em HTML, CSS e JavaScript.

</br><div align="center">
    <img src="https://github.com/josueschiavini/Calculadora-JavaScript/blob/master/calc.gif"/>
</div>

## </br></br></br>Estrutura
### - HTML
#### * Cabeçalho(head) com metatags
##### Adendo:
###### <meta name="viewport" content="initial-scale=1, maximum-scale=1">
###### "viewport" Informa ao navegador que a largura da tela deve ser considerada a "largura total" da página, não importando a largura do dispositivo, tanto desktop como celular ou tablet.
###### "initial-scale=1" Define o nível de zoom inicial da página quando ela é carregada.
###### "maximum-scale=1" Para evitar que usuários deem zoom na página.

#### </br></br>* Body
##### divs para o fundo da página, e para o corpo da calculadora.
##### p - parágrafo para o resultado.
##### table - tabela com linhas e colunas para os números e operadores.
##### classes para atribuir formatação a vários elementos de uma vez.
##### identificador para atribuir formatação a elementos únicos.

### </br></br></br>CSS externo para estilização.
##### Adendo:
###### :hover
###### Para adicionar característica ao elemento botão quando posiciona o mouse sobre ele.

### </br></br></br>JavaScript externo para funções
##### Adendo:
###### onclick="clean()" - Serve para limpar todo o parágrafo "resultado" quando clicado no "C".
###### onclick="back()" - Serve para apagar o caracter anterior.
###### onclick="insert('')" - Serve para inserir o valor definido nos parênteses.
###### onclick="calcular()" - Serve para efetuar o cálculo.
###### function - Para criar as funções dos onclick.
###### document.getElementById - Retorna a referência do elemento através do seu ID.
###### innerHTML - Para alterar o conteúdo de um elemento no DOM inserindo texto e HTML.
###### substring - Retorna a parte da string entre os índices inicial e final, ou até o final da string.
###### length - Contém o comprimento da string, nesse caso para apagar o caracter anterior.
###### eval - Computa um código JavaScript representado como uma string


## </br></br></br>Ferramenta utilizada
#### - <a href="https://code.visualstudio.com/">Vscode 1.67.2</a>

## </br></br></br>Sistema Operacional
#### - Windows 10 x64 versão 21H1

#### </br></br></br>Conteúdo visto em vídeo de Gustavo Neitzke.
#### Link: https://youtu.be/42TShjXR0m0
#### Criado arquivos CSS e JS externos, como melhor prática.
