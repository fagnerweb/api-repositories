# Projeto Api de Repositorios  | [Rocketseat](https://www.rocketseat.com.br/)

Um desafio do curso **Ignite da Rocketseat**, onde foi fornecido um código iniciado de uma api com erros e o desafio era corrigir os erros com base nos erros gerados 
pelos testes. Ou seja, uma api que já possui os testes necessários para fazer toda a validação dos requisitos e que o aluno não deveria mexer nos testes.

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios 
cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

A estrutura de um repositório ao ser criado é a seguinte: 

```
{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}
```

Descrição de cada propriedade:

- **id** deve ser um uuid válido;
- **title** é o título do repositório (por exemplo "unform");
- **url** é a URL que aponta para o repositório (por exemplo "[https://github.com/unform/unform](https://github.com/unform/unform)");
- **techs** é um array onde cada elemento deve ser uma string com o nome de uma tecnologia relacionada ao repositório 
(por exemplo: ["react", "react-native", "form"]);
- **likes** é a quantidade de likes que o repositório recebeu (e que vai ser incrementada de 1 em 1 a cada chamada na rota de likes).

### Screenshot do template fornecido.

![code-3](https://user-images.githubusercontent.com/42723263/205490382-48419fa3-ac93-4138-bb64-5007349a4aa2.png)


## Para executar o projeto na sua máquina

Basta baixar o projeto, ter instalado o node na versão mais recente e o npm.

Em seguida execute o comando abaixo para instalar as dependências 

> yarn install

E para executar 

> yarn dev

Para executar os testes

> yarn test


## Fale comigo

Para entrar em contato

> fagnermarketing2014@gmail.com

