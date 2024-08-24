# Lista de Tarefas

Este é um aplicativo de lista de tarefas desenvolvido em Flutter, que permite aos usuários adicionar, remover e marcar tarefas como concluídas. As tarefas são armazenadas localmente no dispositivo usando um arquivo JSON, garantindo que os dados permaneçam disponíveis mesmo após fechar o aplicativo.

## Funcionalidades

- **Adicionar Tarefas**: Permite que o usuário adicione novas tarefas à lista.
- **Marcar Tarefas como Concluídas**: As tarefas podem ser marcadas como concluídas utilizando uma checkbox.
- **Remover Tarefas**: As tarefas podem ser removidas deslizando para a esquerda.
- **Desfazer Remoção**: Opção de desfazer a remoção de uma tarefa por meio de uma snackbar.
- **Atualização e Ordenação**: As tarefas são automaticamente reordenadas, exibindo as não concluídas antes das concluídas.

## Tecnologias Utilizadas

- **Flutter**: Framework para construção da interface do usuário.
- **path_provider**: Pacote usado para obter o diretório de documentos onde os dados são armazenados.
- **JSON**: Formato utilizado para armazenar e ler os dados das tarefas.

## Como Funciona

- **Adicionando Tarefas**: Use o campo de texto e o botão "ADD" para adicionar novas tarefas à lista.
- **Concluindo Tarefas**: Marque as tarefas como concluídas clicando na checkbox.
- **Removendo Tarefas**: Para remover uma tarefa, deslize-a para a direita. Um botão de desfazer estará disponível por um curto período após a remoção.
- **Persistência de Dados**: As tarefas são salvas localmente no dispositivo, permitindo que o usuário retome de onde parou.
