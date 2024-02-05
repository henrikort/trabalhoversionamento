ContaBanco - Documentação:
---------------------------------------------------------------------------------------------------------------------
O código apresenta a classe ContaBanco, que modela uma conta 
bancária básica com funcionalidades como abertura, fechamento, depósito, saque, 
pagamento de mensalidade e exibição do estado atual.

Funcionalidades Principais:

Abrir Conta:
O método abrirConta(String tipo) permite a abertura de uma nova conta, 
definindo o tipo (CC para Conta Corrente, CP para Conta Poupança) e inicializando 
o saldo conforme o tipo escolhido.

Fechar Conta:
O método fecharConta() fecha a conta se o saldo for zero, exibindo uma mensagem se houver saldo pendente.

Depositar:
O método depositar(float valor) adiciona um valor ao saldo da conta, mas somente se a conta estiver aberta.

Sacar:
O método sacar(float valor) permite o saque de um valor da conta,
 desde que a conta esteja aberta e haja saldo suficiente.

Pagar Mensalidade:
O método pagarMensal() realiza o pagamento da mensalidade da conta,
 cujo valor é determinado pelo tipo de conta (CC ou CP).

Estado Atual:
O método estadoAtual() exibe informações detalhadas sobre o estado atual da conta,
 incluindo número, tipo, titular, saldo e status.