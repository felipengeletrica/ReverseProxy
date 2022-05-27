# Projeto PROXY reverso

Utliliza o Traefik para servidor Apache, Grafana e monitoramento utilizando o dashboard próprio do Traefik.

Este projeto utiliza Docker facilitando a implantação (deploy) dos serviços.

---

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

---

## Testando os serviços

Utilize o navegador web e digite a seguinte url:

> http://apachekarla.localhost

![Testando o Apache](doc/apachekarla.PNG)

http://apache1karla.localhost

![Testando o Apache](doc/apache1karla.PNG)

> http://grafanakarla.localhost

![Testando o Grafana](doc/grafanakarla.PNG)

> http://docuwikikarla.localhost

![Testando o DocuWiki](doc/DocuWikikarla.PNG)

> http://dashkarla.localhost

![Testando o Traefik](doc/dashkarla.png)
