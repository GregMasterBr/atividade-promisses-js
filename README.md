# Sistema de Pedidos de Restaurante com Interface HTML  
Vou criar uma interface HTML completa para simular o sistema de pedidos do restaurante, com botões para acionar a função prepararPedido() e exibir os resultados na tela.

## Funcionalidades Implementadas:
### Interface:
- Botões para cada item do menu com seus tempos de preparo
- Botão para preparar todos os pedidos de uma vez
- Botão para limpar os resultados

### Sistema de Pedidos:
- Função prepararPedido() que retorna uma Promise
- 20% de chance de falha (simulando falta de ingredientes)
- Tempo de preparo variável para cada item

### Feedback Visual:
- Mensagens coloridas (verde para sucesso, vermelho para erro, azul para informações)
- Scroll automático para acompanhar as mensagens mais recentes

### Funcionalidades Avançadas:
- Preparo individual de cada pedido
- Preparo em paralelo de todos os pedidos usando Promise.all()
- Tratamento de erros individual e coletivo

## Como Usar:
- Clique em qualquer item do menu para prepará-lo individualmente
- Clique em "Preparar Todos os Pedidos" para testar o Promise.all()
- Observe as mensagens de sucesso/erro aparecendo na área de resultados
- Use "Limpar Resultados" para começar de novo


## Instruções do Professor
![Texto alternativo](https://github.com/GregMasterBr/atividade-promisses-js/blob/main/atividade-js-promises.png)
