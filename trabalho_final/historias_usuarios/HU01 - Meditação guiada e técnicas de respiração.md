# HU01 - Meditação guiada e técnicas de respiração  
## Fonte do requisito  
Sugestão 1, apresentado por Abraao Santiago Moreira

> O sistema deve fornecer opções de áudio/guias para meditação, e técnicas de respiração.

## Prioridade  
Baixa

## Especificação do requisito  
**Como** usuário do sistema  
**Quero** cessar opções de áudio e guias interativos com instruções para meditação e técnicas de respiração 
**Para** que eu possa encontrar momentos de pausa e relaxamento ao longo do dia, promovendo o equilíbrio emocional, a concentração e o bem-estar físico e mental durante minhas atividades diárias.

## Critérios de aceitação  

### Cenário 1 - Acesso a opções de meditação guiada  
**Dado que** estou na tela inicial do sistema  
**Quando** eu acessar a seção de meditação  
**Então** devo visualizar uma lista de áudios/guias disponíveis para meditação  

### Cenário 2 - Execução de técnicas de respiração  
**Dado que** estou na seção de técnicas de respiração  
**Quando** eu selecionar uma técnica disponível  
**Então** o sistema deve exibir instruções e/ou áudio explicativo para execução da técnica  

### Cenário 3 - Reproduzir conteúdo de meditação ou respiração  
**Dado que** selecionei um áudio ou guia  
**Quando** eu clicar em “Iniciar”  
**Então** o sistema deve reproduzir o conteúdo correspondente com controles de pausa e parada

### Cenário 4 - Exercícios de respiração personalizáveis
**Dado que** selecionei uma técnica de respiração 
**Quando** inicio o exercício  
**Então** devo ver um contador visual que me orienta o ritmo da respiração e posso personalizar o tempo se necessário

### Cenário 5 - Informações sobre o conteúdo
**Dado que** estou navegando pelos guias disponíveis  
**Quando** visualizo cada item  
**Então** devo ver uma breve descrição do objetivo e benefícios de cada meditação ou técnica

### Cenário 6 - Funcionamento offline
**Dado que** baixei um conteúdo para uso offline  
**Quando** estou sem conexão com a internet  
**Então** devo conseguir acessar e reproduzir o conteúdo normalmente
