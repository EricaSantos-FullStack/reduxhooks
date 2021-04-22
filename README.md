# Primeiros passos: Integração entre Redux + React Hooks 💜
Neste projeto, estudo mais funcionalidades e jeitos de simplificar a vida dessa programadora aqui na hora de usar o React.js. Por exemplo, essa nova funcionalidade do React somada com o Redux simplificou muito o acesso aos dados do state e também as actions do Redux.

### ✎ Organização do projeto:
- [x] Escolher o tema dos estudos do dia
- [x] Criar Projeto no React.
- [x] Baixar as extenções Redux.
- [x] Excluir os excessos. 
- [x] Realizar os testes de funcionalidades e correção de bugs
- [x] Deploy no GitHub pages

### ✎ Primeiro passo: 
* Incluir a seguinte linha de código:


### ✎ Segundo passo:
* Excluir as pastas que não são importantes neste projeto.
* Incluir as pastas: </br>

Pasta       | Conteúdo
---------   | ------
Components  | Pasta base
CourseList  | É nesta pasta que fazemos a magia acontecer com o React-redux
Store       | É nessa pasta que incluimos os dados
</br>

A ordem das pastas ficará desta forma:

### ✎ Terceiro passo:
Além de escrever os códigos da aplicação, neste passo mostrarei apenas os 3 imports mais importantes que usei: 
* No App.js:
```JavaScript
import { Provider } from 'react-redux';
```
* No index.js do Store:
```JavaScript
import { createStore } from 'redux';
```
* No Index.js do CourseList:
```JavaScript
import { useSelector, useDispatch} from 'react-redux';
```
### ✎ Resultado:
* Coloquei 3 tipos de curso na lista de Dados, ao clicar em "Adicionar curso" ele incluirá "GraphQL" com a ajuda do *dispatch*. 

### 💍 Secret Gem: 
* Joquinho do Gino. Quem disse que estudos e diversão não podem andar juntos?

#### Veja a aplicação completa:
Deploy: https://ericasantos-fullstack.github.io/reduxhooks/

##### ❥ Agradecimentos especiais: 
Gostaria de agradecer pela aula incrível do <strong>Diego Fernandes</strong> do Rocketseat.</br>
Tutorial: https://www.youtube.com/watch?v=7L7MhxjI4PE

Many thanks to the cutest website where I could get T-Rex Dino's game from: </br>
Website: https://chromedino.com/
