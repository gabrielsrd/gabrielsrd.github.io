---
layout: default
---

# Diário de Desenvolvimento - Contribuição para o Projeto KW

## Data: 07/08/2024

### Atividades Realizadas

Hoje, foi iniciado o trabalho no projeto KW (Kernel Workflow).
O ambiente do KW foi configurado na máquina pessoal. 
Como primeiro PR, procurei funcionalidades simples, e encontrei a função de pomodoro do KW.
Foi identificado um problema ao tentar usar a opção de Pomodoro sem especificar uma tag.

### Problema Identificado

Ao utilizar o comando `kw pomodoro` para definir um timer sem uma tag, o timer não é criado e nenhuma mensagem de erro é exibida. No entanto, quando o comando é executado com uma tag, ele funciona conforme esperado.


### Issue Criada no Repositório

Foi criada uma issue no repositório do projeto para relatar este problema e iniciar a investigação e correção da situação. A issue completa pode ser visualizada [aqui](https://github.com/kworkflow/kworkflow/issues/1156).

### Próximos Passos

- Investigar se o timer está sendo criado sem uma tag.
- Corrigir o problema para que o timer seja exibido corretamente ou implementar uma mensagem de erro apropriada.
- Testar as correções e atualizar a issue no repositório.

