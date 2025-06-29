# HU05 - Feedback e Reporte Anônimo
## Fonte do requisito  
Sugestão 5, apresentado por José Alves de Oliveira Neto

> O aplicativo deve incluir uma funcionalidade para que os colaboradores possam dar feedbacks e reportar problemas de maneira anônima e segura. 

## Prioridade  
Alta

## Especificação do requisito  
**Como** usuário do aplicativo  
**Quero** enviar feedbacks e reportar problemas de maneira anônima e segura  
**Para** que eu possa expressar preocupações e sugestões sem medo de retaliações

## Critérios de aceitação  

### Cenário 1 - Acesso à funcionalidade de feedback anônimo
**Dado que** o colaborador está autenticado no aplicativo  
**Quando** ele acessa a área de bem-estar  
**Então** ele deve visualizar a opção “Enviar feedback anônimo”  

### Cenário 2 - Envio de feedback sem identificação
**Dado que** o colaborador está na tela de envio de feedback anônimo  
**Quando** ele preenche o formulário com sua mensagem e envia  
**Então** o sistema deve registrar o feedback sem associar nenhuma informação de identificação do usuário  

### Cenário 3 - Confirmação de envio
**Dado que** o colaborador enviou um feedback ou problema  
**Quando** o sistema processa a submissão  
**Então** uma mensagem de confirmação deve ser exibida informando que o feedback foi enviado com sucesso  

### Cenário 4 - Segurança de dados
**Dado que** o colaborador envia um feedback anônimo  
**Quando** o sistema armazena a informação  
**Então** os dados devem ser criptografados e não vinculados a nenhum identificador pessoal  

### Cenário 5 - Canal exclusivo para reportar problemas
**Dado que** o colaborador deseja reportar um problema específico relacionado ao ambiente de trabalho  
**Quando** ele seleciona a opção “Reportar problema”  
**Então** deve ser exibido um formulário voltado para relatos de problemas, também anônimo e seguro  

### Cenário 6 - Acompanhamento geral por administradores
**Dado que** o administrador acessa o painel de gestão de feedbacks  
**Quando** ele visualiza os relatórios recebidos  
**Então** ele deve ver apenas o conteúdo do feedback e a data/hora do envio, sem nenhuma informação pessoal do remetente
