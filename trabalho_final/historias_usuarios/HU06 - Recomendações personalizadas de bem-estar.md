# HU06 - Recomendações personalizadas de bem-estar
## Fonte do requisito
Sugestão 27, apresentado por Lucas Gabriel Nunes Alves 

> O sistema deve ser capaz de fornecer recomendações personalizadas para o bem-estar do usuário, com base no perfil de saúde e hábitos de trabalho.

## Prioridade
Média

## Especificação do requisito
**Como** usuário do sistema  
**Quero** receber recomendações personalizadas de bem-estar - como pausas, exercícios e alimenação - baseadas no meu perfil de saúde e hábitos de trabalho  
**Para** que eu possa melhorar minha qualidade de vida de forma direcionada às minhas necessidades específicas, otimizando meu bem-estar físico e mental no ambiente de trabalho.

## Critérios de aceitação

### Cenário 1 - Configuração do perfil de saúde
**Dado que** estou acessando o sistema pela primeira vez  
**Quando** eu for configurar meu perfil  
**Então** devo poder inserir informações sobre minha saúde, condições físicas e hábitos de trabalho

### Cenário 2 - Geração de recomendações personalizadas
**Dado que** tenho um perfil de saúde configurado  
**Quando** acesso a seção de recomendações  
**Então** o sistema deve apresentar sugestões específicas baseadas no meu perfil

### Cenário 3 - Atualização das recomendações
**Dado que** alterei informações do meu perfil ou hábitos de trabalho  
**Quando** salvo as alterações  
**Então** as recomendações devem ser atualizadas automaticamente para refletir as mudanças

### Cenário 4 - Categorização das recomendações
**Dado que** visualizo minhas recomendações  
**Quando** navego pela lista  
**Então** devo ver as sugestões organizadas por categorias (exercícios, alimentação, pausas, etc.)

### Cenário 5 - Recomendações baseadas no tempo de trabalho
**Dado que** estou trabalhando há mais tempo que o recomendado  
**Quando** o sistema detecta esse padrão  
**Então** deve sugerir pausas ou atividades específicas para meu perfil

### Cenário 6 - Feedback sobre recomendações
**Dado que** recebi uma recomendação  
**Quando** a utilizo  
**Então** devo poder avaliar sua eficácia para que o sistema aprenda e melhore futuras sugestões

