# Técnicas para Especificação de Requisitos

A especificação de requisitos tem como objetivo registrar os requisitos de forma que possam ser lembrados, comunicados e utilizados ao longo do ciclo de vida do software. A escolha da técnica de especificação deve considerar:

- O público-alvo  
- O tipo de projeto  
- A maturidade da equipe  
- Os recursos disponíveis  

Em muitos casos, uma combinação de técnicas pode oferecer o melhor equilíbrio entre **clareza**, **precisão** e **manutenibilidade** dos requisitos.

---

## 1. Linguagem Natural Estruturada

Essa técnica utiliza uma forma controlada da linguagem natural para aumentar a precisão dos requisitos. Um exemplo comum é o formato *ator-ação-condição*, ou o uso de templates como **casos de uso** e **histórias de usuário**.

### Cenários de Aplicação
- Projetos em que os stakeholders não são técnicos e precisam entender os requisitos  
- Equipes que desejam maior clareza sem precisar usar notações formais  
- Documentação de sistemas com forte interação usuário-sistema  

### Vantagens
- Mais precisão e menos ambiguidade do que linguagem natural comum  
- Fácil compreensão por parte de usuários e stakeholders  
- Pode ser adaptada a diferentes públicos (ex: *use cases* para analistas, *user stories* para times ágeis)  

### Desvantagens
- Ainda pode conter ambiguidade se não houver um padrão bem definido  
- Requer esforço na criação de templates padronizados  
- Pode se tornar extensa se muitos detalhes forem incluídos em texto  

---

## 2. Especificação Baseada em Critérios de Aceitação

Essa técnica define requisitos com base em critérios de aceitação ou testes. Abordagens comuns incluem **ATDD (Acceptance Test-Driven Development)** e **BDD (Behavior-Driven Development)**. Ao focar em resultados verificáveis, facilita a validação dos requisitos e a automação de testes desde as etapas iniciais do desenvolvimento.

### Cenários de Aplicação
- Projetos ágeis com desenvolvimento iterativo  
- Ambientes em que a validação de requisitos via testes é essencial  
- Sistemas críticos que exigem validação precisa de comportamento  

### Vantagens
- Requisitos precisos e não ambíguos  
- Facilita a validação dos requisitos através de testes  
- Ajuda a alinhar as expectativas de desenvolvedores, testadores e clientes  

### Desvantagens
- Pode exigir maior esforço e envolvimento dos stakeholders para definição de cenários  
- Foco excessivo em testes pode deixar lacunas em requisitos não-funcionais  
- Requer conhecimento técnico e ferramentas para testes automatizados  

---

# Especificação de Requisitos do Projeto

## Requisito A: Lembretes Personalizados para Hábitos Saudáveis

> O sistema deve permitir que os funcionários configurem lembretes personalizados para hábitos saudáveis, como beber água, fazer pausas e ajustar a postura.

**Técnica Utilizada:** Linguagem Natural Estruturada (História de Usuário)

### História de Usuário
Como **funcionário da empresa**,  
Quero **configurar lembretes personalizados para hábitos saudáveis**,  
Para que **eu possa lembrar de beber água, fazer pausas e ajustar minha postura durante o expediente**.

### Critérios de Aceitação
- O sistema deve permitir que o usuário escolha o tipo de hábito (ex: beber água, fazer pausa, ajustar postura)  
- O sistema deve permitir a personalização do horário e frequência dos lembretes  
- O usuário deve receber notificações de lembrete conforme as configurações feitas  

---

## Requisito B: Participação em Desafios de Saúde

> O sistema permitirá que os funcionários participem de desafios de saúde, como caminhada ou meditação, e recebam feedback sobre seu progresso.

**Técnica Utilizada:** Especificação Baseada em Critérios de Aceitação (BDD)

### Cenário: Participação em desafios de saúde com feedback

**Dado que** o funcionário está logado na plataforma,  
**Quando** ele se inscreve em um desafio de saúde (ex: caminhada ou meditação),  
**Então** ele deve ser capaz de registrar seu progresso diariamente  
**E** receber feedback visual e textual com base no seu desempenho.

### Critérios de Aceitação
- O funcionário pode visualizar uma lista de desafios disponíveis  
- O funcionário pode registrar o progresso individual (ex: tempo de caminhada, sessões de meditação)  
- O sistema fornece feedback baseado nos dados inseridos (ex: medalhas, mensagens motivacionais)
