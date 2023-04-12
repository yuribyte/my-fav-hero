# Tarefa: Crie uma aplicação para mostrar seus heróis favoritos!

## Backend
*Tecnologias*:
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [CORS](https://www.npmjs.com/package/cors)

*Descrição*: Mostre uma lista dos seus heróis favoritos. Cada herói deve ter um ID, Nome e a sua fonte/origem.

### Requisitos
1. Crie um novo projeto Node.js e instale a biblioteca Express.
2. Implemente uma simples API com uma única rota que retorna um objeto JSON com um array que tenha os seus personagens favoritos.Cada personagem deve ser um objeto que tenha as seguintes propriedades:
   - `id`: Um identificador único, podendo ser um numero ou um guid/uuid
   - `name`: Nome do personagem
   - `source`: Origem do personagem
3. É importante ativar o CORS para que o frontend possa consumir os dados dessa API
4. É importante criar um arquivo chamado `heroes.json` que contenha a base de dados para os personagens

## Frontend
*Tecnologias*:
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Bootstrap](https://getbootstrap.com/)
- [Axios](https://axios-http.com/ptbr/docs/intro)

*Descrição*: Crie uma página principal que exiba no topo o nome da aplicação e no centro uma tabela com os personagens

### Requisitos
1. Crie uma aplicação React e adicione as bibliotecas Bootstrap e Axios.
2. Faça o design do layout da página principal com os seguintes componentes:
   - Header, contém o `title` da pagina
   - HeroTable, contém a tabela que receberá como parâmetro as `props` de cada herói sendo essas colunas `id`, `name` e `source`
   - O Component principal será responsável por fazer as requisições e passar os valores para o component filho `HeroTable`
3. Use o Axios para fazer as requisições HTTP para o backend Express

### Exemplo do projeto final:
![hero-test-img](https://user-images.githubusercontent.com/54062837/231313845-8fee086a-b9de-4db7-a5f6-b63eb2e7740b.jpg)
