# HU08 - Configuração de lembretes para hábitos saudáveis

## Fonte do requisito  
Sugestão 38, apresentado por Sophia Fernandes Magalhães Almeida
> O sistema deve permitir que os funcionários configurem lembretes personalizados para hábitos saudáveis, como beber água, fazer pausas e ajustar a postura.

## Prioridade
Baixa

## Especificação do requisito  
**Como** usuário do sistema  
**Eu quero** configurar lembretes personalizados para hábitos saudáveis, como beber água, fazer pausas e ajustar a postura  
**Para que** eu possa adotar práticas que promovam meu bem-estar durante o trabalho

## Critérios de aceitação  
### Cenário 1 - Criação de lembrete personalizado  
**Dado que** o funcionário acessa a funcionalidade de lembretes no sistema  
**Quando** ele selecionar o tipo de hábito (beber água, fazer pausa ou ajustar postura) e definir horários ou frequência  
**Então** o sistema deve salvar o lembrete e enviar notificações conforme configurado

### Cenário 2 - Edição de lembrete existente  
**Dado que** o funcionário possui um ou mais lembretes cadastrados  
**Quando** ele acessar um lembrete e alterar informações como horário, frequência ou tipo de hábito  
**Então** o sistema deve atualizar as informações e refletir as mudanças nas futuras notificações

### Cenário 3 - Desativação ou exclusão de lembrete  
**Dado que** o funcionário não deseja mais receber determinado lembrete  
**Quando** ele escolher desativar ou excluir o lembrete  
**Então** o sistema deve parar de enviar notificações relacionadas a esse lembrete e removê-lo (ou desativá-lo) da lista

### Cenário 4 - Notificação no horário configurado  
**Dado que** o funcionário possui um lembrete ativo e configurado  
**Quando** o horário ou intervalo definido for atingido  
**Então** o sistema deve enviar uma notificação clara indicando o hábito a ser realizado (ex.: “Hora de beber água”)

### Cenário 5 - Validação de conflito de horários  
**Dado que** o funcionário está configurando múltiplos lembretes  
**Quando** ele definir dois ou mais lembretes para o mesmo horário ou com sobreposição de tempo  
**Então** o sistema deve alertar sobre o conflito e permitir que ele ajuste os horários ou confirme a criação mesmo com a sobreposição

### Cenário 6 - Visualização dos lembretes ativos  
**Dado que** o funcionário deseja gerenciar seus lembretes  
**Quando** ele acessar a seção de lembretes no sistema  
**Então** o sistema deve exibir uma lista com todos os lembretes ativos, incluindo informações como tipo de hábito, horário e frequência
