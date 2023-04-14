# app_help_desk
  
  
   Ao iniciar o projeto, para que funcione, colocamos o diretório do Apache dentro do painel de controle do XAMPP, através do qual acessamos o diretório htdocs e criamos uma pasta chamada app_help_desk. Para acessar, precisamos fazer uma requisição para localhost, que é onde o servidor Apache está aguardando requisições.

Observações:

O método action="" é responsável por referenciar para onde os dados inseridos no formulário irão após o cliente clicar no botão submit.
Para incluir os dados informados pelo usuário final é necessário declarar o método name="" nas tags HTML que o usuário irá preencher, pois esse método é quem recebe os dados informados.
Os métodos $_GET e $_POST definem o método de envio dos dados, esses dados precisam conter nomes, que definimos com o método name="" para que consigam ser recuperados através dos métodos $_GET ou $_POST.
A função header("location:") faz com que o usuário seja redirecionado para alguma outra página.
A função isset() verifica se um índice de um determinado array está setado, retornando true quando o índice está setado e false quando o índice não está setado dentro do array.
As sessões são uma forma simples de armazenar dados para usuários individuais usando um ID de sessão único.
Os includes podem incluir códigos de um arquivo para outro, como construtores.
É possível encerrar uma sessão de 2 modos, sendo por unset($_SESSION['x']) ou session_destroy().
Para criar um arquivo de escrita, você pode utilizar a função fopen('nome_do_arquivo.extensão','tipografia').
Para escrever o arquivo, você deve utilizar a função fwrite($variaval_que_recebe_o_arquivo, $texto).
Para fechar o arquivo, você deve utilizar a função fclose($variaval_que_recebe_o_arquivo).
PHP_EOL é uma constante utilizada para gerar uma quebra de linha nos arquivos de escrita.
A função feof() verifica se o combustível é o fim do arquivo (EOF).
A função fgets() retorna uma linha de um arquivo aberto
