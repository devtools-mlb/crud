# Cadastro de usuários

Você poderá escolher a linguagem que se sente mais confortável para fazer.
Crie uma API que deverá listar, cadastrar, editar e deletar usuários. Com os seguintes requisitos:

1 - Os usuários devem ser gravados em um banco de dados a sua escolha (dê preferencia ao Open Source: MySQL, PostgreSQL, MongoDB, etc).<br>
2 - O usuário deve conter os campos: nome, e-mail, idade, telefone e empresa.<br>
3 - Cada usuário pode ter mais de um e-mail.<br>
4 - A empresa só poderá ser alterada 1 única vez.

O JSON de entrada será:

```json
{ 
   "nome":"João",
   "email":[ 
      "joao@teste.com.br",
      "joao1@teste.com.br"
   ],
   "idade":"20",
   "telefone":"11111111111",
   "empresa":"Teste"
}
```

Você deve enviar todas as instruções para iniciar a API e o banco de dados.
