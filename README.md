# Projeto-Final-Java-2023
Sistema de Gerenciamento Bancário


Você foi contratado para desenvolver um sistema de gerenciamento bancário em Java. O sistema deve permitir o cadastro de contas correntes e contas poupança, além de possibilitar operações como depósito, saque, transferência e consulta de saldo. Além disso, é necessário aplicar os conceitos de herança, polimorfismo e interfaces para melhorar a organização e flexibilidade do sistema.


Requisitos do sistema:


Conta:


Uma conta possui os seguintes atributos: número da conta, titular da conta e saldo.

Implemente uma classe abstrata "Conta" com os atributos, construtor e métodos de acesso (getters e setters).

A classe "Conta" também deve ter um método abstrato "calcularSaldo()" que calcula o saldo da conta com base em regras específicas (por exemplo, considerando o saldo e eventuais taxas).

Crie duas subclasses de "Conta": "ContaCorrente" e "ContaPoupanca".

A classe "ContaCorrente" deve ter um atributo adicional "limiteChequeEspecial" e implementar o método "calcularSaldo()" de acordo com regras específicas para contas correntes.

A classe "ContaPoupanca" deve ter um atributo adicional "taxaRendimento" e implementar o método "calcularSaldo()" de acordo com regras específicas para contas poupança.

Implemente também o método "toString()" nas classes "Conta", "ContaCorrente" e "ContaPoupanca" para retornar uma representação em string das contas.


Cliente:


Um cliente possui os seguintes atributos: nome, idade e lista de contas.

Implemente uma classe "Cliente" com os atributos, construtor e métodos de acesso (getters e setters).

A classe "Cliente" deve implementar a interface "OperacoesConta" que define os métodos "depositar()", "sacar()" e "consultarSaldo()".

Na implementação dos métodos da interface "OperacoesConta", realize as operações nas contas do cliente.

Implemente também o método "listarContas()" na classe "Cliente" para imprimir as contas do cliente.


Banco:


O banco é responsável pelo gerenciamento das contas e clientes.

Implemente uma classe "Banco" que possua listas para armazenar as contas e clientes.

A classe "Banco" deve ter métodos para cadastrar contas e clientes, além de métodos para realizar as operações de depósito, saque, transferência e consulta de saldo.

Utilize polimorfismo nos métodos de operações para permitir o uso de diferentes tipos de contas.

A classe "Banco" também deve ter métodos para buscar uma conta por número e listar todos os clientes.


Main:


Crie uma classe "Main" com o método principal (main) para executar o programa.

No método principal, crie um objeto da classe "Banco" e implemente um menu interativo para o usuário interagir com o sistema.

O menu deve permitir as seguintes opções: cadastrar conta, cadastrar cliente, depositar, sacar, transferir, consultar saldo, listar contas, listar clientes e sair do programa.


Observações:


Utilize os conceitos de encapsulamento, herança, polimorfismo e interfaces.

Utilize a classe "Scanner" para receber entradas do usuário e interagir com o sistema.

Implemente as validações necessárias para garantir a integridade dos dados do sistema.

Desenvolva o código completo que implemente as classes "Conta", "ContaCorrente", "ContaPoupanca", "Cliente", "OperacoesConta", "Banco" e "Main" de acordo com as especificações acima.
