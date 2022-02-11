<h1 align="center">Documentação de padrões para refatoração 🛠️</h1> 

<h3> Padrões de nomenclatura </h3>

<h4> Branchs & Commits </h4>

Usaremos a extensão [GitFlow](http://danielkummer.github.io/git-flow-cheatsheet/) para gerenciar as branches, além disso para nomear as branchs devemos seguir o seguinte padrão: `feature/tag_da_sprint_obejetivo_da_branch`

Ex: 
```
 feature/spt07_description_description
```

__Observações:__ O nome da branch deve ser em ingles e cada palavra deve ser separada por underline (_) seguindo o padrão snake_case. O préfixo `feature/` é adicionado automaticamente pela extensão GitFlow.

<h4> Variavéis </h4>

Váriaveis devem seguir o padrão de nomenclatura lower camel case.

Ex:
```js
 const pageContent =  "";
```

<h4> Classes </h4> 

As classes seguirão o padrão de nomenclatura PascalCase, começando com o nome da entidade seguido pela função da classe

Ex:

```js
  class UserController {
   // code
  }
```


