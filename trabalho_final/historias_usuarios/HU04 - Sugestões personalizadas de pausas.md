# HU04 - Sugestões personalizadas de pausas no trabalho

## Fonte do requisito
Sugestão 12, apresentado por Giovanna Lyssa Rodrigues Borges Teles

> O sistema deve oferecer sugestões personalizadas de pausas para alongamento ou relaxamento, com base no tempo de uso do computador e nas atividades realizadas.

## Especificação do requisito
**Como** usuário do sistema  
**Eu quero** receber sugestões personalizadas de pausas para alongamento ou relaxamento baseadas no meu tempo de uso do compuatdor e atividades realizadas no trabalho  
**Para que** eu possa prevenir lesões por esforço repetitivo e manter minha produtividade sem comprometer minha saúde física e mental a partir de longos períodos de trabalho

## Prioridade
Baixa

## Critérios de aceitação

### Cenário 1 - Monitoramento do tempo de uso
**Dado que** estou usando o computador continuamente por mais de 1 hora  
**Quando** o sistema detecta este período de uso   
**Então** devo receber uma sugestão de pausa personalizada para alongamento ou relaxamento

### Cenário 2 - Sugestões baseadas nas atividades realizadas  
**Dado que** realizei atividades intensas ou repetitivas no computador  
**Quando** o sistema identificar esse padrão de uso 
**Então** devo receber sugestão de um tipo de pausa específica para me ajudar a me recompor do meu comportamento repetitivo

### Cenário 3 - Personalização baseada no histórico
**Dado que** já utilizei sugestões de pausa anteriormente  
**Quando** o sistema possui um histórico dessas pausas realizadas anteriormente e analisa meu comportamento e preferências  
**Então** deve oferecer sugestões mais adequadas ao meu perfil (duração, tipo de exercício)

### Cenário 4 - Configuração de frequência
**Dado que** quero personalizar a frequência das sugestões  
**Quando** acesso as configurações do sistema  
**Então** devo poder definir intervalos de tempo entre uma sugestão e outra (30min, 1h, 2h)

### Cenário 5 - Sugestões contextuais
**Dado que** está próximo ao fim do expediente ou meio-dia  
**Quando** o sistema detecta estes horários  
**Então** deve sugerir pausas mais longas ou específicas para estes momentos

### Cenário 6 - Controle das notificações
**Dado que** estou em uma atividade que não pode ser interrompida  
**Quando** recebo uma sugestão de pausa  
**Então** devo poder adiar realizar a sugestão por 15-30 minutos ou desabilitar temporariamente as notificações
