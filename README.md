# Sistema Finanças Pessoais

Para rodar o sistema , tem que ter um software chamado composer.
Com o composer instalado tem que abrir o terminal CMD  dentro da pasta do projeto.
e rodar o comando:
composer install

Ai ele já instala todas as dependencias do laravel.

É necessario tem um software de banco de dados no caso usei mysql com o xammp.
criar um Db com o nome personalfinances.


Depois de tudo ajustado tem que rodar alguns comandos para gerar as tabelas do banco de dados:

php artisan migrate

E depois disso mais um comando para semear o banco de dados com os valores fakes gerados pelo laravel (para fins de demonstração ele gera automaticamente alguns dados com esse comando):

php artisan serve db:seed

para rodar o projeto tem que dar um comando chamado:

php artisan serve.

