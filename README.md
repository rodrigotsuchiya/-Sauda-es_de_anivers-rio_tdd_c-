<h1>Saudações de aniversário</h1> 
desafio do coding dojo <https://codingdojo.org/kata/birthday-greetings/>

Como você é uma pessoa muito simpática, gostaria de enviar um bilhete de aniversário para todos os amigos que tem. Mas você tem muitos amigos e é um pouco preguiçoso, pode demorar um pouco para escrever todas as notas à mão.

A boa notícia é que os computadores podem fazer isso automaticamente para você.

E você deseja enviar a eles um e-mail de feliz aniversário na data de nascimento:

 Subject: Happy birthday!

 Happy birthday, dear <first_name>!

Como seria esse software? Tente implementá-lo para que você possa alterar facilmente:

    a maneira como você recupera os dados dos amigos (por exemplo, tente mudar para um banco de dados SQLite)
    a forma como você envia a nota: (por exemplo, imagine que você deseja enviar SMS em vez de e-mails)

Que tipo de testes você escreveria? Você usaria Mocks?
Características adicionais

    Amigos nascidos no dia 29 de fevereiro deverão ter seu aniversário comemorado no dia 28 de fevereiro

    Envie um lembrete de aniversário quando for o aniversário de outra pessoa:

        Subject: Birthday Reminder

        Dear <first_name>,

        Today is <someone_else_first_name> <someone_else_last_name>'s birthday.
        Don't forget to send him a message !

    Envie um único lembrete de aniversário

        Subject: Birthday Reminder

        Dear <first_name>,

        Today is <full_name_1>, <full_name_2> and <full_name_3>'s birthday.
        Don't forget to send them a message !


