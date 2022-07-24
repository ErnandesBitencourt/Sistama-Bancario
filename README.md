# Sistema-Bancario
um pequeno exercicio, criando uma conta bancaria usando o typescript


# SISTEMA BANCÁRIO

## Estrutura de Dados

### Contas:

* `nome`
* `CPF` (único)
* `data` de nascimento (idade > 18)
* `saldo` (começa zerado)
* `extrato` (array de transações)      
   * `valor`
   * `data` 
   * `descrição`

## Funcionalidades

### Criar Conta

* Informar `nome`, `CPF` e `data` de nascimento

### Pegar Saldo

* Passando `nome` e `CPF`. 

### Adicionar saldo

* Passando `nome`, `CPF` e `valor` 

### Pagar Conta

* Passando `valor`, `descrição` e `data` de pagamento. 
* Caso ele não informe a `data`, considerar pagamento no mesmo dia. 
* Não pode haver agendamento para `data` passada
* Não pode haver pagamento sem que haja `saldo` suficiente.

### Transferência Interna

* Informar `nome`, `CPF`, `nome` do destinatário, `CPF` do destinatário e `valor`. 
* Não podem ser agendadas 
* Devem respeitar o `saldo` do usuário remetente.

## Requisitos Mínimos

* Criar conta, 
* Pegar contas e 
* Adicionar validação de idade. 
