
# **Feature: Teste de  login no site  da Dafiti usando a Sintaxe BDD**

**Como** Cliente acessa o site www.dafiti.com.br &nbsp;

**Dado que** o cliente digita o  de email ou CPF ou CNPJ e a senha &nbsp;

**Para** fazer login no site e efetuar compras &nbsp;


## Cenário 1

**Dado que** o cliente precisa fazer login no site e efetuar compras &nbsp;

**Quando** cliente digitar o email &nbsp;

**E** digitar a senha &nbsp;

**Então** ele clica em **entrar** para conseguir logar fazer as compras &nbsp;


## Cenário 2

**Dado que** o cliente precisa fazer login no site e efetuar compras &nbsp;

**Quando** cliente digitar o CPF &nbsp;

**E** o cliente digitar a senha &nbsp;

**Então** o cliente consegue logar e fazer compras &nbsp;


## Cenário 3

**Dado que** o cliente precisa esta cadastrado no site &nbsp;

**Quando** cliente digitar o CNPJ &nbsp;

**E** o cliente digitar a senha &nbsp;

**Então** o cliente consegue logar e fazer compras &nbsp;


## Cenário 4 
**Dado que** o cliente não consegue logar no site &nbsp;

**Quando** insere um email incorreto &nbsp;

**E** retorna mensagem de email ou senha incorreta &nbsp;

**Então** Cliente não consegue logar no site &nbsp;

## Cenário 5

**Dado** que o cliente não consegue logar no site &nbsp;

**Quando** insere CPF incorreto &nbsp;

**E** retorna mensagem de email ou senha incorreta &nbsp;

**Então** Cliente não consegue logar no site &nbsp;


## Cenário 6

**Dado** que o cliente não consegue logar no site &nbsp;

**Quando** insere CNPJ incorreto &nbsp;

**E** retorna mensagem de email ou senha incorreta &nbsp;

**Então** Cliente não consegue logar no site &nbsp;

## Cenário 7

**Dado** que o cliente não consegue logar no site &nbsp;

**Quando** insere a senha incorreta &nbsp;

**E** retorna mensagem de email ou senha incorreta &nbsp;

**E**  cliente clica em esqueceu a senha &nbsp;

**E** preenche o campo com  email, CPF ou CNPJ para recuperar a senha &nbsp;

**E** o cliente clica em ok &nbsp;

**E** uma mensagem será enviada para o email cadastrado para recuperação de senha &nbsp;

**E**  acessa o link enviado no email cadastrado, cria uma nova senha e clica em salvar minha senha.

**Então**  Cliente consegue acessar o site com a nova senha.



