## Welcome to Awesome.AspNetCore.VueJS.Template

Awesome.AspNetCore.VueJs.Template is a demo/template project for you to use vuejs and webpack in your dotnetcore web/mvc projects. In this project , you need  know just these knowledges before:

- webpack
- vuejs
- dotnet-core

Clone from ```git@github.com:duotai/Awesome.AspNetCore.VueJs.git```  . If it's useful for you , please star it. Thank you .

### Step 1

Clone the project into your directory:

```markdown
git Clone git@github.com:duotai/Awesome.AspNetCore.VueJs.git
```

### Step 2

Open the project directory , and run ```npm install``` and ```dotnet restore```

```
cd Awesome.AspNetCore.VueJs
npm install
dotnet restore
```

### Step 3

Use ```Webpack ``` to watch the vue files changed, and then you can run the project with ```dotnet```:

```
webpack -w
dotnet run
```

Any things you changed in the *.vue files, you just refresh the browser . You need not run build for the front-end files.

### Publish

Use ``` webpack -publish ``` to publish the front-end files.

Use ```dotnet publish ``` to publish the back-end files.

```
webpack -publish
dotnet publish
```



### Support or Contact

Having trouble with Project ?  

- add issues .
- Join the  qq group :436035237  ask questions  @苏州-似血残阳