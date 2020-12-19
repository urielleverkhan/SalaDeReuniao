# Projeto de criação de Sala de reuniões feito para o Bootcamp da Everis do site da Digital Innovation one.
## Temos aqui 2 pastas, uma contendo o FrontEnd e outra contendo o BackEnd
Esta aplicação toda foi construída toda sob o framework Angular no front, e no Blackend usamos o java versão 8 junto com o controlador de dependencias Mavem.

Para funcionar a aplicação primeiro você deve no terminal e dentro da pasta onde foi colocado todo o projeto, na pasta BackEnd você deve criar o pacote.jar usando a seguinte linha de comando:
**mvn clean package spring-boot:repackage**

Em seguida suba o projeto usando a seguinte linha de comando:
**java -jar target/saladereuniao-0.0.1-SNAPSHOT.jar**

Em seguida, precisamos subir o servidor Angular, para isto dentro da pasta FrontEnd execute o seguinte comando:
**ng serve**

Agora você pode ver a aplicação rodando pelo seguinte endereço em seu browser de preferencia usando o seguinte endereço:
**http://localhost:4200/rooms**

