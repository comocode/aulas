
#  PHP Basico
## Introdução


### Criando um ambiente LAMP

[Usando Ambiente Local](http://www.comocode.com/assista/usando_ambiente_local)


### Commandos de PHP

Todos commando de PHP seguem o modelo de
    php "commando"

* php -v :: versão de PHP instalada no seu sistema
* php -i :: informação sobre a usa instalação de PHP
* php -a :: Shell interativo para linguagem PHP

### Variavels

Para declarar um variavel so seu applicativo o modelo e

cifrão nome do variavel (que so começar com letras e so pode incluir [a-zA-Z0-9_]) signal de igual e o valor do variavel

exemplo

    $meuVariavel="oi Mundo";

### Função
função sao pacotes de comandos ou instruçao que sao executada em uma operação

exemplo
```php
        |------ declaração de função
        |      | -- nome da função
        |      |    | -- parênteses para argumentos
       \/     \/    \/
    function oiMundo(){ < -- chave aberta
        echo "oi mundo"; <-- comando
    } <-- chave para fechar
 ```
para chamar sua função e so usar como comando

    oiMundo(); 

### Se Lembre !
todos os commandos em PHP terminão com ";" para dizer para PHP que o commando termina aqui. 
exemplo
    
    echo "oi mundo"; 
    $meuVariavel = "oi Mundo"; 

