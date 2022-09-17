# Git Branches

## Criei um site e apliquei os conhecimentos sobre Branches (ramificações dentro do Git/Github)

### Passo 1

1. Criei um novo repositório/projeto `main` dentro do Github Desktop,

   ↪️ Os componentes do projeto foram:

   * .gitattributes;
   * License _usei MIT_;
   * Readme.md.
2. Abri meu projeto no Visual Studio Code

   ↪️ Criei a pasta de HTML `index.html`.

   * Com o comando `!`

```
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> // Auterei o título
</head>
<body>
   
</body>
</html>
```

* Em seguida comentei no Github Desktop e dei um `Commit`
* Logo após comitar, o Github Desktop pediu para eu dá um `Push origem` ou seja: (carregar as alterações para o meu repositório remoto = Github

3. Criei um `new branch` no menu do Github Desktop

   ↪️ O nome dado para a `new branch` ➡️ `conteúdo`.

   * Adicionei os componentes de : `</link>, </body>, </main>, </h1>, </article>, </h2> e </p>`

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título do Site</title>
</head>
<body>
   <main>
    <head>
        <h1>Cursos Grátis</h1>
    </head>
    <article>
        <h2>Curso de HTML5 com CSS3</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. // texto padrão
             Id consectetur facere adipisci rem magni voluptatibus. 
             Explicabo, deleniti quaerat dolore sunt quos fuga natus 
             non ea rem ab consequatur facilis sequi.</p>
    </article>
    <article>
        <h2>Curso de JavaScript</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Sunt ut cum amet hic nemo.
             Autem error harum dolor, recusandae optio rem, libero 
             asperiores praesentium qui eos velit exercitationem! Tenetur, commodi.</p>
    </article>
   </main> 
</body>
</html>
```

* Em seguida comentei no Github Desktop e dei um `Commit`
* Logo após comitar, o Github Deskitop pediu para eu dá um `Push origem` ou seja: (carregar as alterações para o meu repositório remoto = Github

4. Criei uma segunda `new branch` no menu do Github Desktop

   ↪️ O nome dado para a `new branch` ➡️ `design`.

   * Adicionei o comando ` <link rel="stylesheet" href="estilos/style.css">` no VSCode
   * ↪️ Como eu não havia criado uma pasta com atributos Gráficos de CSS, o VSCode pediu para eu criar essa pasta
   * A pasta foi criada
   * * Com o comando `*{}` Adicionei os atributos gráficos do meu projeto

```
*{
font-family: Arial, Helvetica, sans-serif;
font-size: 16px;
}

body {
    background-color: rgb(161, 72, 40);

}

main {
    background-color: rgb(112, 45, 19);
    width: 500px;
    margin: auto;
    padding: 10px;
    box-shadow: 3px 3px 5px rgb(0, 0, 0.473);
}
```

* Em seguida comentei no Github Desktop e dei um `Commit`
* Logo após comitar, o Github Deskitop pediu para eu dá um `Push origem` ou seja: (carregar as alterações para o meu repositório remoto = Github

### Passo 2

1. Fazer a união das três `branches` criadas

   ![image](https://user-images.githubusercontent.com/109313933/184496027-ffdb0542-323b-4860-89ec-c530a04d9954.png)

   ↪️ No Github Desktop eu cliquei em:
   `Branch` ➡️ `Merge into current branch ou (Ctrl+Shift+M)`
   ↪️ Cliquei na `branch conteúdo` ➡️ clico em `Creata merge commit`

   * Mesmo procedimento pra as demais
   * Ao final a `branch` vai conter todas as auterações feitas nas `branches` __conteúdo e design__ e irão aparecer integradas ao repositório desta forma:

   ![image](https://user-images.githubusercontent.com/109313933/184496347-275fdb9f-1e8a-40a6-9fab-59d236be3fe6.png)
   
  ↪️[Link do projeto finalizado](https://keilianerocha.github.io/Branches/)

> Em construção ...

