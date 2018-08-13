<h1>Informações Complementares:</h1>
 <ul>
  <li>Banco de Dados: MYSQL 5.6.17;</li>
  <li>PHP: Version 5.5.12;</li>
  <li>Servidor: APACHE 2.4.9;</li>
  <li>Framework: LARAVEL 5.6;</li>
  <li>Ambiente de Desenvolvimento: WAMP SERVER 2.5.</li>
</ul>

<h2>Para configurar a aplicação siga os seguintes passos:</h2>

<h3>Passo 1: DOWNLOAD DO ARQUIVO</h3>
	<ul>
    <li>
      Realize o download do arquivo compactado acima e extraia-o no ambiente de desenvolvimento ou servidor web, clique uma vez sobre ele ou digite o seguinte comando no prompt do git:
      <ul>
        <li>
          git clone https://github.com/vinicius-nascimento98/Projeto-laravel.git';
        </li>
      </ul>
    </li>
  </ul>

<h3>Passo 2: CONFIGURAR VM-HOST:</h3>
	<ul>
    <li>
      Realize a configuração do VM-Host com o nome de 'projeto-laravel' e o diretório de destino da pasta 'projeto', conforme realizado no Passo 1 [projeto/public/index.php];
    </li>
  </ul>

<h3>Passo 3: CONFIGURAR BANCO DE DADOS:</h3>
	<ul>
    <li>Abra o arquivo '.env' do diretório projeto/ e mude as seguintes configurações de acordo com o usuario e login do banco de dados:</li>
		  <ul>
        <li>DB_CONNECTION=mysql;</li>
		    <li>DB_HOST=127.0.0.1;</li>
        <li>DB_PORT=3306;</li>
		    <li>DB_DATABASE=projeto;</li>
        <li>DB_USERNAME=root;</li>
        <li>DB_PASSWORD=root;</li>
      </ul>
	  <li>Abra o PHPMYADMIN ou qualquer outro gerenciador de banco de dados, e crie o banco de dados informado na configuração acima [DB_DATABASE=projeto];</li>
    <li>Com o banco de dados configurado é necessário realizar a importação das migrates que serão utilizadas na aplicação, para isso digite o seguinte comando no prompt:</li>
	    <ul>
        <li>php artisan migrate</li>
      </ul>
  </ul>
  
<p><b>Pronto o banco de dados ja esta configurado e a aplicação esta pronta para o uso.</b></p>
