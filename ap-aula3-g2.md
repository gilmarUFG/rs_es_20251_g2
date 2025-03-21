## RF001: O sistema deve permitir que o usuário faça depósito de dinheiro

### 1) Descrição detalhada do requisito:

O sistema de apostas de jogos de futebol deve permitir que os usuários realizem depósitos de dinheiro em suas contas de forma segura e eficiente. 

HU01 
**Como** um usuário registrado,
**Quero** ser capaz de depositar dinheiro na minha conta de apostas,
**Para** que eu possa participar das apostas em jogos de futebol.

Critérios de Aceitação:

- O usuário deve ser capaz de escolher entre diversos métodos de pagamento, como cartão de débito, pix, transferência bancária e carteiras digitais.
- O valor mínimo e máximo de depósito deve ser claramente informado ao usuário antes de concluir o processo.
- Após concluir a transação com sucesso, o saldo da conta do usuário deve ser atualizado imediatamente.
- O sistema deve exibir uma mensagem de sucesso quando o depósito for bem-sucedido e uma mensagem de erro clara em caso de falha.


### 2) Identificação das fontes dos requisitos:

1) Representante dos usuários finais do aplicativo.
2) Legislação local sobre jogos de azar e transações financeiras

### 3) Fluxo de execução:

Fluxo de execução bem sucedido:

1) O usuário acessa a página de depósitos no sistema.
2) O sistema solicita o valor do depósito.
3) O usuário insere o valor e confirma.
4) O sistema exibe as opções de métodos de pagamento (cartão de débito, pix, transferência bancária, carteiras digitais).
5) O usuário escolhe o método de pagamento desejado.
6) O sistema exibe uma tela de confirmação com os detalhes do depósito (método de pagamento, valor).
7) O sistema solicita as informações necessárias para processar o pagamento (exemplo: dados do cartão, chave PIX, login de carteira digital).
8) O usuário confirma as informações e finaliza a transação.
9) O sistema processa a transação e o valor é creditado na conta do usuário.
10) O sistema exibe uma mensagem de sucesso e atualiza o saldo da conta do usuário.
11) O histórico de depósitos é atualizado, registrando o depósito.

### 4) Perfis de usuários com permissão de execução:

Perfil: Usuário Comum
Permissão:
Usuários registrados que desejam realizar depósitos em suas contas de apostas. Eles devem ter permissão para acessar a página de depósitos e realizar transações financeiras, desde que tenham um saldo positivo na conta ou um limite de crédito estabelecido.

Restrições:
Não têm permissões administrativas ou de controle sobre a plataforma.

