# Envie email com Javascript

No site SmtpJs.com podemos usar uma lib bem simples que nos ajuda enviar e-mail pelo protocolo Smtp via javascrit.

##Exemplo
### HTML

```sh
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://smtpjs.com/v3/smtp.js"></script>
</head>
<body>
  <button id="send" value="send">Send</button>
  <script type="text/javascript" src="smtpjs.js"></script>
</body>
</html>


```

### JS

```sh
$(document).ready(function(){
  $('#send').click(function(){
    Email.send({
      SecureToken : "9d332450-e278-4fef-ac2a-63003f4f6b35 ",
      To : 'juan.cantero.jarilla@gmail.com',
      From : "juan.cantero.jarilla@gmail.com",
      Subject : "This is the subject",
      Body : "And this is the body"
  }).then(
    message => alert(message)
  );
  });

});


```

# VEJA TAMBÉM
## Grupo de Estudo no Telegram
- [Participe gratuitamente do grupo de estudo](https://t.me/blogilovecode)

## Cursos baratos!
- [Meus cursos](https://olha.la/udemy)

## Fique ligado, acesse!
- [Blog ILoveCode](https://ilovecode.com.br)

## Novidades, cupons de descontos e cursos gratuitos
https://olha.la/ilovecode-receber-cupons-novidades
