## API Reference
### List Books
#### List all books
List all awesome books
```http
  GET http://127.0.0.1:8000/api/list-book/
``` 

### Response 200: 

```Json
{
   "livro":[
      {
         "id":1,
         "created_at":"2022-06-09T19:28:26.000000Z",
         "updated_at":"2022-06-09T19:28:26.000000Z",
         "nome":"Asdas dasd",
         "autor":"Das",
         "ano":1961,
         "status":0,
         "sinopse":"aosfgjiashfjoghsdfhiofo\u00b4ghisdgoihjsdgkhl"
      },
      {
         "id":2,
         "created_at":"2022-06-09T19:29:55.000000Z",
         "updated_at":"2022-06-09T19:29:55.000000Z",
         "nome":"Asdas dasd",
         "autor":"Das",
         "ano":1986,
         "status":1,
         "sinopse":"aosfgjiashfjoghsdfhiofo\u00b4ghisdgoihjsdgkhl"
      },
      {
         "id":3,
         "created_at":"2022-06-09T19:40:04.000000Z",
         "updated_at":"2022-06-09T19:40:04.000000Z",
         "nome":"O poder da china",
         "autor":"Ricardo Geromel",
         "ano":2019,
         "status":1,
         "sinopse":"Com este livro, você aprender\u00e1: As ferramentas b\u00e1sicas para decodificar a China; Qual \u00e9 a rela\u00e7\u00e3o China vs. mundo e como as empresas chinesas se internacionalizam; Por que e como a China tem crescido t\u00e3o rapidamente; Como fazer neg\u00f3cios com o mercado chin\u00eas; Os detalhes dos principais protagonistas da nova economia digital da China; O que \u00e9 a Nova Rota da Seda, em que o governo chin\u00eas promete investir US$ 1 trilh\u00e3o no exterior; Quem s\u00e3o Shenzhen, Hangzhou e diversos outros unic\u00f3rnios chineses; Por que \u00e9 um consenso que a China ultrapassar\u00e1 a economia dos EUA."
      },
      {
         "id":4,
         "created_at":"2022-06-09T19:41:46.000000Z",
         "updated_at":"2022-06-09T19:41:46.000000Z",
         "nome":"O rafael \u00e9 gay????",
         "autor":"Eu",
         "ano":1917,
         "status":0,
         "sinopse":"Qual Rafael voc\u00ea se pergunta? O rafael certo \u00e9 o que est\u00e1 lendo isso agora e ele \u00e9 gay."
      },
      {
         "id":5,
         "created_at":"2022-06-09T19:43:29.000000Z",
         "updated_at":"2022-06-09T19:43:29.000000Z",
         "nome":"Berserk",
         "autor":"Kentaro Miura",
         "ano":1979,
         "status":1,
         "sinopse":"A Melhor obra do mundo inteiro apenas compre imediatamente agora pode clicar no botao de comprar to esperando..."
      },
      {
         "id":6,
         "created_at":"2022-06-09T19:44:33.000000Z",
         "updated_at":"2022-06-09T19:44:33.000000Z",
         "nome":"Front-End \u00e9 cringe",
         "autor":"Todo mundo da terra",
         "ano":2009,
         "status":0,
         "sinopse":"Front end \u00e9 a pior maneira de programar. ningu\u00e9m gosta dele, e ele n\u00e3o gosta de ningu\u00e9m, se voc\u00ea gosta, eu recomendo pular da janela do quinto andar."
      },
      {
         "id":7,
         "created_at":"2022-06-09T19:49:17.000000Z",
         "updated_at":"2022-06-09T19:49:17.000000Z",
         "nome":"O dia a dia de um cidad\u00e3o da china",
         "autor":"Alguem chin\u00eas",
         "ano":2001,
         "status":1,
         "sinopse":null
      },
      {
         "id":8,
         "created_at":"2022-06-09T19:50:10.000000Z",
         "updated_at":"2022-06-09T19:50:10.000000Z",
         "nome":"Shrek",
         "autor":"William Steig",
         "ano":1998,
         "status":1,
         "sinopse":"Era uma vez um p\u00e2ntano distante, onde vivia um ogro chamado Shrek. De repente, seu sossego \u00e9 interrompido pela invas\u00e3o de personagens de contos de fadas que foram banidos de seu reino pelo maldoso Lorde Farquaad. Determinado a salvar o lar das pobres criaturas, e tamb\u00e9m o dele, Shrek faz um acordo com Farquaad e parte para resgatar a princesa Fiona. Resgatar a princesa pode n\u00e3o ser nada comparado com seu segredo profundo e sombrio."
      },
      {
         "id":9,
         "created_at":"2022-06-10T01:41:08.000000Z",
         "updated_at":"2022-06-10T01:41:08.000000Z",
         "nome":"B\u00edblia",
         "autor":"Deus",
         "ano":1917,
         "status":0,
         "sinopse":"Voc\u00ea sabe..."
      },
      {
         "id":10,
         "created_at":"2022-06-10T01:42:35.000000Z",
         "updated_at":"2022-06-10T01:42:35.000000Z",
         "nome":"UIIIIII",
         "autor":"Vai da namoro",
         "ano":1901,
         "status":1,
         "sinopse":"Ele gooooooosta, YEEEEEEEEHAAAAW, Dan\u00e7a gatinho dan\u00e7a, rapais, que isso menino calma."
      }
   ]
}

```
### Delete book
#### Delete a book
Delete a awesome book
```http
  DELETE http://127.0.0.1:8000/api/delete-book/{id}
``` 

### Response 200:

```Json
  {
    "message" :"success"
  }
```
