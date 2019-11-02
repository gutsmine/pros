# prof

<img src="pros.png" style="zoom:50%;" />


### This is a new javascript framework.

-----
## v

#### Please clone this repository

    git@github.com:gutsmine/pros

#### Or run the following command in npm

```
npm install pros
```

#### Embed it in your project.

    <script src="pros.js"></script>
### Or

    fetch('./pros.js').then(r=>r.text()).then(t=>eval(t))

----

## syntax

### html

    window.document

  #### It will be the same shape as

    var document = html.input.value;

### getid(Variable name, Id to get)

#### Gets an element from id.

    var Variable name = document.getElementById(Id to get);
  #### It will be the same shape as

#### You can use getclass and getname in the same way.

## getidval(Variable name, Id to get)

##### Gets element text from id.

```
var Variable name = document.getElementById(Id to get).value;
```



   ## cli(Element variable, The function to execute, argument)

#### Allows click processing of an element.

    Element variable.onclick(function(argument){The function to execute}
   #### It will be the same shape as 

   ##### In addition, we plan to make it possible to specify multiple arguments using variables.

   ## che(Element variable, The function to execute, argument)

#### Allows processing when an element changes.

    Element variable.addEventlistener("chenge",(event)=>{
    Function name(argument)
    })
   #### It will be the same shape as

   ## kup(Element variable, Function name, argument)

#### Allows processing when a keyboard is pressed within an element.

    Element variable.addEventlistener("keyup",(event)=>{
    if(event.isComposing){
    Function name(argument)
    }
    })  
   #### It will be the same shape as

   ## inhtm(Element variable, text)

#### Change the text of the element.

    Element variable.innerHTML=text;
   #### It will be the same shape as

## newobj(Variable name, The text to add)

#### Create a new object variable.

```
var Variable name = {The text to add};
```

#### It will be the same shape as

## addobj(Variable name, The text to add)

#### Append to object variable.

```
Variable name.push(The text to add);
```

#### It will be the same shape as

#### There are also newlist and addlist.

## mergevar(追加する変数名, 変数1, 変数2)

#### 変数を統合します。

```
var Variable name to add = Variable 1 +  Variable 2;
```

#### It will be the same shape as

-----
   ### Due to the current development process, problems may occur.

 This repository is licensed under MIT LICENSE (this license). You must comply with this license to use this file. A copy of this license can be obtained from:

https://github.com/gutsmine/pros/blob/master/LICENSE



![](gutsminemade-by.png)