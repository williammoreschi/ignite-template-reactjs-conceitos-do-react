![image](https://user-images.githubusercontent.com/2512512/111013025-bd4c2700-837c-11eb-96bd-e35dd94de39d.png)
# Desafio 01 - Conceitos do React

Objetivo desse desafio é por em prática alguns conceitos sobre manipulação de estado do React visto no primeiro módulos.

## Especificação dos testes

- [x] **should be able to add a task**
A task deve ser criada e exibida em tela e devem conter os atributos seguindo o padrão da interface.
```js
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```
- [x] **should not be able to add a task with an empty title**
- Antes de criar uma task validar se campo de input foi preenchido e não permitir a criação caso o valor seja vazio.

- [x] **should be able to remove a task**
- Ao clicar no botão com ícone de uma lixeira, remover a task relacionado a esse botão.


- [x] **should be able to check a task**
- Ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de **isComplete** de **_false_** para **_true_** ou ao contrário, de **_true_** para **_false_** 

![to-do](https://user-images.githubusercontent.com/2512512/111013055-d6ed6e80-837c-11eb-9a92-20992651b117.gif)

O template desse projeto foi desenvolvido pela equipe da [Rocketseat](https://github.com/Rocketseat).


### Caso queira testar a aplicação em seu pc ou notebook.
```shell
git clone https://github.com/williammoreschi/ignite-template-reactjs-conceitos-do-react.git

cd ignite-template-reactjs-conceitos-do-react

# você pode usar o yarn ou npm

# instalar as dependências 
yarn install

# executar o projeto ele vai rodar na porta 8080
yarn dev 

# executar os testes
yarn test

#--------------

npm install

npm run dev

npm run test
```