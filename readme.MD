# Conceitos React

#### components/TaskList.tsx
Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde botaremos em prática várias partes da manipulação do estado.

Deverão ser criadas as funcionalidades para as três funções presentes nesse arquivo, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.