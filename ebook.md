1. instalar o xampp

	#verificar a instalação - > php -v 

2. instalar o composer
	
	#verificar a instalação - > composer --version

3. no vscode

	composer create-project --prefer-dist laravel/laravel sistema

4. teste
	php artisan serve

5.Routes

sistema/routes/web.php 

***adicionando rota/página***

sitema/resouces/views

criar arquivo: contact.blade.php

sistema/routes/web.php

Route::get('/contact', function () {
    return view('contact');
});

***adicionando um link para voltar para home ou qualquer rota:*** 

<a href="/">home</a> 







	