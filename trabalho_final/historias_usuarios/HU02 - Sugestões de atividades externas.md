# HU2 - Sugestões de atividades externas
## Fonte do requisito
Sugestão 8, apresentada por Felipe Moreira Silva.

> O sistema deve ofertar uma grade de serviços externos aos colaboradores; como lazer; atividades físicas e auxílios; fora do trabalho. Estes podem ser mudados periodicamente; a fim de atrair atenção.

## Prioridade
Média

## Especificação do requisito
**Como** gestor de recursos humanos,  
**Eu quero** criar e gerenciar uma lista de sugestões de atividades e serviços externos à organização, em que os usuários possam optar por omitir sugestões e avaliar positiva ou negativamente uma sugestão;  
**Para que** os colaboradores da organização tenham indicações de atividades que promovam sua saúde e bem-estar, estando saudáveis e dispostos quando vierem para o trabalho, e o departamento de RH saiba quais os tipos de sugestões os usuários mais gostam e procuram, para continuar sugerindo.

## Critérios de aceitação
### Cenário 1 - Cadastrar sugestão de atividade
**Dado que** sou o colaborador do setor de RH  
**Quando** eu cadastrar uma nova sugestão de atividade,   
**Então** essas atividades devem ser mostradas aos usuários.

### Cenário 2 - Optar por não visualizar uma sugestão de atividade
**Dado que** sou um colaborador da organização e recebo recomendações de atividades externas,  
**Quando** eu optar por não ver mais essa sugestão de atividade,   
**Então** o sistema não deverá mostrá-la para mim novamente.

### Cenário 3 - Visualizar todas as sugestões de atividades externas
**Dado que** sou um colaborador da organização e recebo recomendações de atividades externas,  
**Quando** eu optar por visualizar todas sugestões de atividades externas,    
**Então** o sistema deverá me mostrar todas as sugestões cadastradas pelo RH, segregando aquelas que eu optei por não visualizar mais.

### Cenário 4 - Remover sugestão de atividade
**Dado que** sou colaborador do RH com permissões para gerenciar sugestões de atividades externas,     
**Quando** eu optar por excluir uma sugestão de atividade  
**Então** a sugestão de atividade excluída não deverá ser mais mostrada aos usuários do sistema.

### Cenário 5 - Avaliar uma sugestão de atividade
**Dado que** sou colaborador da organização e capaz de visualizar as sugestões de atividades externas   
**Quando** eu avaliar uma atividade, positiva ou negativamente   
**Então** a minha avaliação deve ser mostrada pelo sistema aos demais usuários.

### Cenário 6 - Aleatorizar as sugestões de atividade
**Dado que** sou colaborador da organização e capaz de visualizar as sugestões de atividades externas    
**Quando** o sistema me mostrar um widget com as atividades externas sugeridas   
**Então** as atividades mostradas deverão ser sorteadas, para haver alguma diversidade nas sugestões mostradas de forma rápida.  