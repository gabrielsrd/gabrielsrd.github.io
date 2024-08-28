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

## Data: 09/08/2024

### Atualização

A issue foi respondida no Github e um dos colaboradores me deu sinal verde para continuar trabalhando na issue e me orientou como fazer. Devo subir um PR nos próximos dias.

## Data: 14/08/2024
### Atividades Realizadas
Realizei alterações no arquivo de geração de timers de Pomodoro (pomodoro.sh). A modificação permite que o timer de Pomodoro seja registrado sem a necessidade de especificar uma tag. Agora, se nenhuma tag for fornecida, o timer é registrado automaticamente com a tag padrão NO-TAG. Esta mudança foi feita para resolver o problema identificado anteriormente.

### Commit realizado:

"This commit modifies the pomodoro.sh script to allow the registration of a Pomodoro timer without requiring a specified tag. If no tag is provided, the timer is now automatically registered with the default tag NO-TAG.

### Próximos Passos
- Aguardar uma resposta de algum dos mantenedores do projeto
- Investigar o motivo dos testes estarem inconsistentes

## Data: 28/08/2024
### Atividades Realizadas

- Modifiquei o commit conforme um dos mantenedores me sugeriu
- Comecei a olhar o código do Patch-Hub