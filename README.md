# Recuperação de senha

**Requisitos Funcionais**

- O usuário pode recuperar sua senha informando o seu e-mail;
- O usuário deve receber um e-mail com as instruçẽs de recuperação de senha;
- O usuário pode resetar sua senha.

**Requisitos Não Funcionais**

- Utilizar Mailtrap para testar envios em ambiente de dev;
- Utilizar Amazon SES para envios em produção;
- O envio de e-mails deve acontecer em segundo plano (background job);

**Regras de Negócios**

- O link enviado por email para resetar a senha, deve expirar em 2h;
- O usuário precisar confirmar a nova senha para validar;

# Atualização do perfil

# Painel do prestador

# Agendamento de serviços
