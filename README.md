## Aplicativo de Notas

Este é um aplicativo simples de notas desenvolvido em React. Ele permite que os usuários criem, visualizem e excluam notas facilmente. As principais funcionalidades incluem:

- **Criação de Notas:** Os usuários podem criar novas notas digitando seu conteúdo e salvando.
- **Visualização de Notas:** Todas as notas criadas são exibidas em cards na tela principal.
- **Exclusão de Notas:** Os usuários podem excluir notas indesejadas clicando no botão correspondente em cada card.
- **Busca de Notas:** Existe uma funcionalidade de busca que permite aos usuários filtrar notas com base no conteúdo.

### Estrutura do Projeto

O projeto é estruturado da seguinte forma:

- `src/`
  - `assets/`: Contém os recursos estáticos, como imagens.
  - `components/`: Contém os componentes React utilizados na aplicação.
  - `App.tsx`: Arquivo principal que renderiza a aplicação e gerencia o estado das notas.

### Funcionalidades Principais

- **useState:** Utilizado para gerenciar o estado dos componentes, incluindo as notas e a string de busca.
- **localStorage:** As notas são armazenadas localmente no navegador do usuário utilizando a API localStorage.
- **Filtragem de Notas:** As notas podem ser filtradas com base no conteúdo digitado na barra de busca.
- **Componentização:** O código está organizado em componentes reutilizáveis, como `NewCard` e `NoteCard`.

### Como Utilizar

Para rodar o aplicativo localmente:

1. [*Clone este repositório*](https://github.com/ViniciusMirtilo/NlW_Project_Note.git)
2. Instale as dependências com `npm install` ou `npm i`.
3. Execute o aplicativo com `npm run dev`
4. O aplicativo estará disponível em `http://localhost` no seu navegador.

Sinta-se à vontade para contribuir, reportar problemas ou sugerir melhorias! 😊
