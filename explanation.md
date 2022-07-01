# Explicação

O plugin utiliza escopos restritos da API OAuth do Google devido ao modo como a dependência PHPMailer implementa sua interface OAuth, a qual não permite o uso do escopo GMAIL_SEND, somente o MAIL_GOOGLE_COM, referente a permissão total do Gmail.

O plugin somente utiliza os dados fornecidos para o envio de emails através da conta do Gmail do usuário.
