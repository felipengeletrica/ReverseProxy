# Projeto PROXY reverso 

 Utliliza o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.
    
Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços. 
 ***

 ## Implantação dos serviços
 Abrir o terminal e execute os seguintes comandos:

Construindo e excutando os serviços (pressione ctrl+c para cencelar):

 > $ docker-compose up --build

 Utilize -d para dar um "detach" rodar o serviço na máquina

> $ docker-compose up --build -d

Parando serviços: 
> $ docker-compose stop

Removendo serviços: 
> $ docker-compose rm
***

 ## Testando os serviços

Utilize o navegador web e digite a seguinte url:

> http://mayara4.localhost

 ![Testando o Apache](doc/apache.png) 

 > http://mayara6.localhost

 ![Testando o Grafana](doc/grafana.png) 

  > http://mayara5.localhost

 ![Testando o DocuWiki](doc/DocuWiki.png) 

  > http://mayara1.localhost

 ![Testando o Traefik](doc/dashboard.png) 
