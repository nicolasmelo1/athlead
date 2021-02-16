# Athlead
A sua atlética na palma da sua mão

## Motivação
De acordo com [essa reportagem](https://www.terra.com.br/noticias/dino/profissionalizacao-de-atleticas-universitarias-e-a-aposta-de-startup-mineira,3971d33354e60b6239011ae35d08aae4gw80nu9b.html#:~:text=Atualmente%20existem%20cerca%20de%204.000,da%20universidade%20ou%20qualquer%20institui%C3%A7%C3%A3o.) de 2018 o número de atléticas universitárias no Brasil é de 4000 atléticas ao todo. Ainda que esse número seja bastante alto sinto que existe um problema comum entre todas elas: existe uma certa dificuldade das mesmas em se modernizar para com os seus estudantes. Muitas se utilizam da venda de produtos e eventos para manter o caixa positivo e muitas vezes essa venda acaba sendo feita de maneira presencial nos estandes das universidades. 

Com essa informação, creio que seria uma boa solução criar um criador de apps para atléticas. Com ele vamos oferecer tudo o que uma atlética precisa e/ou venha a precisar utilizando-se de tecnologias modernas e fáceis de aprender. Não só oferecer toda a base para que os alunos possam criar seus próprios aplicativos (sejam web, desktop ou mobile), queremos também contribuir para a disseminação de conteúdo e material de estudo para alunos de faculdade que desejam aprender os mais variados conceitos de programação, ciência de dados, e demais frentes.

Portanto, esse criador de aplicativos deve:

1 - ser fácil de manter

2 - ser fácil de extender com novas funcionalidades

3 - atender a maioria das necessidades das atléticas universitárias do país

## Ideação e possivel arquitetura do projeto
O projeto será um monorepo lerna contendo: O backend feito em [express.js](https://expressjs.com/pt-br/), uma versão front-end web com [next.js](https://nextjs.org/), uma versão mobile em [react native](https://reactnative.dev/) e se tudo rolar tranquilamente, uma versão desktop feita com [electron.js](https://www.electronjs.org/)

## Tarefas a serem feitas
Essas tarefas não serão realizadas necessariamente em ordem

- [X] Escrever uma documentação simples sobre o projeto
- [ ] Escrever uma documentação mais aprofundada sobre o projeto, suas intenções e estrtutura
- [ ] Configurar prettier
- [ ] Configurar o ambiente lerna
    - [X] Instalar o lerna
    - [ ] Criar pasta `packages`
    - [ ] Linkar dependências
- [ ] Configurar o ambiente de backend **Express.js**
- [ ] Configurar o ambiente de front-end com **Next.js**
- [ ] Configurar o ambiente de mobile com **React Native**
- [ ] Configurar ambiente de código compartilhado entre o React Native e o Next.js
- [ ] Definir dominios do sistema utilizando-se dos conceitos de [Domain Driven Design](https://en.wikipedia.org/wiki/Domain-driven_design)
- [ ] Definir estrutura dos dados de autenticação
