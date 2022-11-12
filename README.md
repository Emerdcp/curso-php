# PHP (Hypertext Preprocessor)

Uma linguagem server-side, roda do lado do servidor. É uma linguagem de progamação back-end, pois realiza comunicação com banco de dados.
Ela é processsado no servidor e o resultado do processamento é enviado ao cliente (quem requisitou). Exemplo:

Arquivo PHP: 2+2

Resposta para o cliente: 4

Todo arquivo PHP te´ra a extesão .php

## Aula 01
 - Introdução ao PHP
 - Infraestrutura necessária
 - Onde colocar nossos arquivos
 - Variáveis
 - Tipo de dados
 - Operadores aritméticos
 - Envio/Recebimento de informações entre arquivos
 
### Introdução ao PHP
 - Documentação oficial http://php.net.
 - Ele brilha na WEB, 79% da web ysa PHP (https://kinsta.com/php-market-share/).
 - PHP pode ser utilizado para projetos do IoT (internet das coisas), funciona para criar aplicação de linha de comando (modo texto), pode criar aplicativos desktop com PHP
 - PHP é uma linguagem interpretada.

 ### Infraestrutura necessária
  - Servidor é um computador que fornece serviços a clientes. Exemplo: Serviço de DHCP: O servidor fica responsável por distribuir números IP (internet Protocol) para clientes (host) na rede.
  - Nossa sites ficam em servidores Web, um servidor web é responsável por exibir um site quando for solicitado (requisição). Iremos utilizar o servidor web chamado APACHE (existem outros como IIS, NGINX) juntamente com um banco de dados chamdo MariaDB(mesma coisa do MySQL).
  - Vamos intalar o XAMPP, esse programa já instala o APACEH, o PHP e o MariaDB. Baixa o XAMPP em https://www.apachefriends.org/

![](xampp.PNG)

### Onde colocar nossos arquivos
 - Os arquivos PHP precisam ser executados à partir do servidor, como se você estivesse acessando pela internet.
 - Para o XAMPP, o local aonde devemos colocar os arquivos é `c:\xampp\htdocs`. Exemplo `c:\xampp\htdocs\site\index.php`.
 - Para executar os arquivos php, precisamos requisitá-los à partir do navegador digitando `http://localhost`. Exemplo: `http://localhost/site/index.php`.

 ### Variáveis
 - Variável é um espaço na memória que damos um nome para armazenar algum valor.
 - O PHP é case-sensitive, significa que ele diferencia maiúsculas de minúsculas, ou seja, Nome é diferente do nome.
 - O nome de uma variável deve ser segnificativo de acordo com o seu valor, Exemplo: para um variável que vai armazenar a idade de uma pessoa eu colocar o nome da variável de $idade.
 - No PHP toda variável inicia com $.
 Não utilzia caracters especiais, espaços ou acentos para nome de variáveis de forma simples. Exemplo: ao invés de endereço para o nome de uma variável utilize $endereco sem o 'ç'.
