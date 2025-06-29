# Rastreabilidade e Análise de Consistência – HU05

## Matriz de Rastreabilidade

| Requisito / User Story        | Relacionado a                          | Descrição / Observações                                                                 |
|------------------------------|----------------------------------------|-----------------------------------------------------------------------------------------|
| HU05 - Feedback e Reporte Anônimo | RF05                        | Requisito principal que define a funcionalidade de envio anônimo e seguro de feedback  |
| HU05                         | RF06                            | Feedbacks recebidos podem influenciar recomendações personalizadas para o bem-estar     |
| HU05                         | RF09                            | Relatos anônimos podem embasar reuniões de bem-estar com profissionais especializados   |

---

## Análise de Consistência

- [x] O envio de feedback é realmente anônimo e sem vínculo com dados pessoais?
- [x] O conteúdo é criptografado e armazenado de forma segura?
- [x] O sistema possui canais distintos para feedback e reporte de problemas?
- [ ] Existe uma política de retenção de dados para esse tipo de informação?
- [ ] O administrador tem acesso apenas ao necessário (mensagem, data/hora)?
- [ ] O sistema impede tentativas de identificação do autor do feedback?

### Recomendações:

- Reforçar a implementação de anonimização real dos dados e revisar possíveis rastros de IP ou sessão.
- Incluir alerta visual garantindo ao usuário que o envio será anônimo.
- Implementar logs de acesso administrativos para garantir rastreabilidade e auditoria da visualização dos feedbacks.
- Garantir que os relatórios administrativos não exibam nenhuma informação de identificação, nem metadados.
- Criar um canal claro de diferenciação entre sugestões e denúncias, ambos anônimos e seguros.
