# chatNodeJs
Chat simples em NodeJS

#Instruções para executar em Servidor Amazon AWS

Com o npm forever Modulo pode-se executar o seguinte comando para manter o serviço sempre ativo:
  - forever start /var/www/html/chatNodeJs/app.js
Para listar os serviços ativos e ver o seu ID de Processo Linux:
  - forever list
Caso precise parar o processo use o comando Kill + ID do processo consultado acima:
  $ kill 13519

Para testes em desenvolvimento:
  - node app.js
  Isso faz a execução do codigo somente durante o momento que o terminal Linux estiver aberto.
