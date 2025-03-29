## RF001: O sistema deve permitir que o usuário faça depósito de dinheiro

### Questionário de Requisitos – “Como”
#### Como saberemos que isso está completo?
Será considerado completo quando o saldo da conta do usuário for atualizado com o valor inserido ou, caso contrário, quando for exibida uma mensagem de erro informando que a operação não foi concluída.

### Questionário de Requisitos – “Onde”
#### Onde o usuário acessaria esse recurso?
O usuário acessaria esse recurso através de um botão na tela inicial, o qual o levará para a carteira do aplicativo.

### Questionário de Requisitos – “Quando”
#### Quando o recurso falhará?
O recurso falhará caso o pagamento seja recusado por falta de saldo, informações incorretas, instabilidade na plataforma financeira ou no próprio sistema. Além disso, a operação será impedida se o valor inserido não respeitar as restrições de mínimo e máximo estabelecidas.

### Questionário de Requisitos – “Quem”
#### Quem entregará as entradas para o recurso?
O usuário será responsável por entregar as entradas para o recurso, já que será ele quem vai inserir as informações do depósito. Além disso, as plataformas financeiras devem se conectar ao sistema e fornecer entradas para confirmação de dados inseridos no recurso.

### Questionário de Requisitos – “O Que”
#### Quais são as partes deste recurso?
Esse recurso contará com: a interfarce para inserção de dados, a integração com os provedores de pagamentos, a interface de notificação de sucesso ou falha da operação e a interface de registros de transações.

### Questionário de Requisitos – “Por Quê”
#### Esse recurso atende às necessidades de negócios e resolve o problema que estamos tentando resolver?
Sim, pois é fundamental para o objetivo da aplicação que o usuário realize o depósito na plataforma para fazer uso das suas funcionalidades, ou seja, atende às necessidades do negócio e resolve o problema.
