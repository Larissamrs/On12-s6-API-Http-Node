# Introdução à API: HTTP e NodeJS 

**Semana 6 – Teoria + Prática**

------
### Breve apresentação

Eu me chamo Larissa, sou aluna do Reprograma na turma On12 de 2021.1 e é um prazer compartilhar um pouco do conhecimento adquirido. Ao longo dessa trajetória venho aprendendo que desenvolver a lógica de programação exige prática e é algo que suma importância para saber os caminhos a seguir e interpretar os dados necessários para resolução daquele determinado problema. Com isso, venho praticando e aliando com o cronograma do curso, sendo assim, a cada dia venho ganhando mais confiança em relação a programação.

<br>

### Exercícios propostos

**1. Qual a relação entre os métodos HTTP e o CRUD?**

**HTTP** - É um protocolo que permite a obtenção de recursos, como documentos HTML. É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, no qual significada que as requisições são iniciadas pelo destinatário, geralmente um navegador Web. Analisando o que o HTTP faz que o REST permita possibilidades para o CRUD.

**CRUD** - é um acrônimo para palavras em inglês: Creat (Criar), Read (Ler), Update (Atualizar) e Delete (deletar) que são operações básicas que podemos fazer com os dados.

Com os serviços web RESTful, existe uma semelhança entre os métodos HTTP e operações CRUD. Embora não existam regras estabelecidas, as seguintes diretrizes são aplicáveis na maioria dos casos: 

- **GET** é usado para recuperar dados ou executar uma consulta em um recurso. Os dados retornados do webservice é uma representação do recurso solicitado. 

- **POST** é usado para criar um novo recurso. O serviço web pode responder com os dados ou estados que indicam o sucesso ou fracasso.

- **PUT** é usado para atualizar dados ou recursos existentes. Também pode ser utilizado para criação de recursos como será visto adiante.

- **DELETE** é usado para remover dados ou recursos.

  

**2. Comente, com exemplos, a diferença entre o PUT e o PATCH?**

Os métodos **HTTP PUT** e **PATCH** são usados para indicar um requisição de alteração de dados.

Ao usar o **PUT**, fica legível que a alteração de dado será completa.

Exemplo: (/usuario/1234):

Resultado: {'id': 1234, 'name': 'Larissa', 'idade': 26, 'documento': '321.123.21-X'}

O **PATCH** é usado para atualização parcial.

Exemplo: (/usuario/1234) :

Resultado: {'name': 'Larissa'

**3. Assim como na aula, apresente os dados dos JSONs no console.**

- No colors-rgb.js apresente o nome da cor e o código RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
- No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidades, sem arrays aparentes no console
- No filmes.js apresente titulo, plot, gêneros e língua. Gênero e língua devem ser apresentados em arrays no console.

**4. Defina o conceito de idempotência e como uma API pode ser idempotente.**

O método é considerado idempotente se o resultado de uma requisição realizada com sucesso é independente do número de vezes que é executada.

Quando falamos em idempotência em API’s REST, podemos concluir que os seguintes os verbos:

- **GET**, **PUT**, **DELETE**, **HEAD** e **OPTIONS** são idempotentes**.**
- **POST** não é idempotente. A função do **POST** é criar um recurso, então a cada requisição que se realizar, um recurso será criado e assim alterando o estado da aplicação e não mantendo o atual.

**5. Cite alguns diferentes padrões de projetos de software.**

**Design Patterns** (Padrões de Projeto) são soluções para problemas comuns que encontramos no desenvolvimento ou manutenção de um software orientado a objetos (não são tão bem aplicáveis em outros paradigmas). Em resumo, são soluções generalistas para problemas que surgem de forma recorrente ao longo do desenvolvimento de softwares. Ou seja: são soluções elegantes, prontas, pensadas, testadas e aprovadas para situações comuns e que surgem no cotidiano.

Citando alguns dos diferentes padrões de projetos de software, são eles:

- **Layers (camadas);**

- **Cliente-server (cliente servidor);**

- **Model-view-controller (MVC);**

- **Microservices (microserviços);**

- **Pipers-and-filters (PF);**

- **Peer-to-peer (P2P);**

- **Service-Oriented Architecture (SOA);**

- **Publish-Subscribe (Pub/Sub).**

  

------



<h3>Fontes</h3>

UMA visão geral do HTTP. MDN Web Docs mozilla, 2021. Disponível em: <https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Overview> . Acessado em: 18 de junho de 2021.

CRUD: o que é este conceito no Desenvolvimento de Sistemas. Angelo Publio, 2021. Disponível em: <https://angelopublio.com.br/blog/crud>. Acessado em: 18 de junho de 2021.

DE PAIVA FERREIRA, Esequiel; MATIUSSO JR, Mario. **Aplicações RESTful**. 2018.

DIFERENÇA entre PUT e PATCH. Alura, 2021. Disponível em: <https://cursos.alura.com.br/forum/topico-diferenca-entre-put-e-patch-44669>. Acessado em: 18 de junho de 2021.

O que é idempotência e porque devemos utilizar. Medium, 2021. Disponível em: <https://medium.com/@lucasschwenke/idempot%C3%AAncia-uma-boa-pr%C3%A1tica-a-se-utilizar-em-servi%C3%A7os-rest-633c38f4d7c0#:~:text=Quando%20falamos%20em%20idempot%C3%AAncia%20em,HEAD%20e%20OPTIONS%20s%C3%A3o%20idempotentes.>. Acessado em: 18 de junho de 2021.

PADRÕES de projeto: o que são e o que resolvem. Treinaweb, 2021. Disponível em: <https://www.treinaweb.com.br/blog/padroes-de-projeto-o-que-sao-e-o-que-resolvem>. Acessado em: 18 de junho de 2021.

CONHEÇA os diferentes tipos de Design Patterns e seus benefícios. Bitbaru, 2021. Disponível em: <https://www.bitbaru.com/site/conhea-os-diferentes-tipos-de-design-patterns-e-seus-benefcios/>, Acessado em: 18 de junho de 2021.

QUAIS são os tipos de arquitetura de software e como escolher o melhor para seu projeto, Posdigital, 2021. Disponível em:<https://posdigital.pucpr.br/blog/tipos-de-arquitetura-de-software>. Acessado em: 18 de junho de 2021.



------

<br>

## Larissa Maria
- [linkedin](https://www.linkedin.com/in/lmrs99/)
- [github](https://github.com/Larissamrs)

  
