# HU03 - Marcação de consultas virtuais com especialistas
## Fonte do requisito  
Sugestão 11, apresentado por GABRIEL MILHOMEM CUNHA

> O aplicativo deve permitir a marcação de consultas virtuais com especialistas em saúde e bem-estar.

## Prioridade
Média

## Especificação do requisito  
**Como** Usuário do aplicativo  
**Quero** marcar consultas virtuais com especialistas em saúde e bem-estar  
**Para que** eu possa receber atendimento de forma prática e acessível

## Critérios de aceitação  
### Cenário 1 - Marcar uma consulta virtual com especialista disponível  
**Dado que** o usuário está autenticado no sistema e visualiza uma lista de especialistas disponíveis  
**Quando** ele selecionar um especialista e um horário disponível  
**Então** o sistema deve confirmar a marcação da consulta virtual e exibir os detalhes da agenda

### Cenário 2 - Consulta virtual com especialista indisponível  
**Dado que** o usuário tenta agendar com um especialista sem horários disponíveis  
**Quando** ele tentar selecionar um horário  
**Então** o sistema deve informar que não há horários disponíveis e sugerir outros profissionais ou datas

### Cenário 3 - Notificação de consulta agendada  
**Dado que** o usuário agendou uma consulta virtual com sucesso  
**Quando** a data da consulta estiver se aproximando (por exemplo, 24 horas antes)  
**Então** o sistema deve enviar uma notificação lembrando o usuário sobre a consulta
