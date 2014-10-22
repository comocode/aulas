
# Introdução ao Desenvolvimento Web
## Usando Um Ambiente Local

[Presentaçao: Ciclo De Vida de um Pedido](http://slides.com/comocode/lesson_1-ciclo_de_vida/)

[Presentaçao: Ambientes e Pedidos ](http://slides.com/comocode/lesson_1_introducao_a_web/)


## Neste video nos cubrimos

* Qual sao as partes de o ambiente LAMP
* As maneiras de installar um ambiente no teu systema local
* Oque sao maquinas virtual
* Oque e VirtualBox e Vagrant
* Como usar vagrant para criar um ambiente local

## Definições
* Sistema/Ambiente Local: O sistema de operação nativo que corre seu computador
* Ambiente/Caixa Virtual : Uma instância separada e isolada de outro computador que corre em cima do seu computador local

##Ferramentas
[Apache](http://www.apache.org) :: Servidor de internet mais popular em uso.

[MySQL](http://dev.mysql.com) :: Um banco de dados popular para executar SQL (Structured Query Language)

[PHP](http://php.net) :: Uma linguagem popular utilizada para executar applicativos em um servidor.

[MAMP](http://www.mamp.info/en/) :: Pacote para installar Apache + Mysql + PHP em seu systema mac local

[WAMP](http://www.wampserver.com/) :: Pacote para installar Apache + Mysql + PHP em seu PC (windows) local

[VirtualBox](http://virtualbox.org) :: Aplicaçao que cria e mantem maquinas virtual em seu systema local

[Vagrant](http://vagrantup.com) :: Ferramenta para criar maquinas virtual automaticamente

[Comocode Centos](http://www.github.com/comocode/centos) :: Pacote preparado para utilizar centos com lamp 


## Como criar um ambiente local

### Primerio, installar Virtualbox
* Visite [https://www.virtualbox.org/](https://www.virtualbox.org/)
* Click o link chamado "Download"
* Selecione seu pacote, windows our mac utiliza o link (x86/amd64), 
** Para Linux tem que seguir os paços para sua distribuição https://www.virtualbox.org/wiki/Linux_Downloads  
* Apos de fazer o Download, instalá-lo em seu sistema local
* Quando a instalação estiver concluída, confirme que você pode executar o comando VBoxManage -v
* Em um Mac, abra um instância de Terminal [command+spaço] que abre a pesquisa e escreva "Terminal" 
* Para Windows, [start] + (run ou click na area de pesquisa) e escreva "cmd" para criar um windows de Dos 
* Mac/Linux corra o commando "VBoxManage -v", 
* Para Windows, tem que navegar para a installação de Virtualbox "c:\Program Files\Oracle\Virtualbox\VBoxManage -v"

### Instalar Vagrant
* Visite [http://www.vagrantup.com/](http://www.vagrantup.com/)
* Click o botão "Download" 
* Abaixe o pacote para seu sistema 
* Apos baixado, execute o pacote e instale Vagrant em sua máquina local.
* Confirma que esta instalado executando o commando "vagrant -v" no seu terminal ou dos 









    
