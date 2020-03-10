# LuvArts
Repositório de desenvolvimento da plataforma LuvArt's

## Ferramentas necessárias

* Node.js: https://nodejs.org/en/
* PHP: https://www.apachefriends.org/pt_br/index.html
* Composer: https://getcomposer.org/
* Laravel: https://laravel.com/docs/6.x/installation
* IDE recomendada: https://code.visualstudio.com/

## Instalação do Projeto

* Baixar o projeto
* Iniciar Apache e Mysql no xampp
* Acessar a url localhost/phpmyadmin/
* Criar um banco de dados com o nome "laravel"

rodar o seguinte comando dentro da pasta src:

```sh
php install.php
```

## Modo de uso

* Ligar Apache e Mysql no xampp
* ir dentro da pasta src e rodar o comando "php artisan serve"
* Abrir a url que aparecer no terminal

## Desenvolvimento

Regras e dicas:
* Todo o template não implantado deve ser amarzenado em uma pasta ao lado de src
* As paginas do projeto implantadas ficam em src/resources/views
* O js fica em src/resources/js
* O local de trabalho com css deve ser escolhido pelo Front-End podendo ser em src/resources/sass ou src/public