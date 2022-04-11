---
layout: PostLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Variável Interna e variável de Estado
date: '2022-04-11'
excerpt: Variável Interna e variável de Estado
featuredImage:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/post-4.jpeg'
  altText: Post thumbnail image
  caption: ''
bottomSections: []
---
Exemplo de variavel de estado



```
//license

pragma solidity ...

contract HelloWorld {
string public message = "Hello World!"

function greetings () public view returns (string memory){
return message;
}
}
```



Exemplo de Variavel interna

```
contract HelloWorld {


function greetings () public pure returns (string memory){
string memory message = "Hello World!"


return message;

}}
```



Para nossa variavel de estado fazer mais sentido precisamos refartorar da seguinte forma:

```
//license

pragma solidity ...

contract HelloWorld {
string public message = "Hello World!"

function greetings () public view returns (string memory){return message;}

function greetings () public view returns (string memory){return message;}



}


```

