---
layout: PostLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Tipos Primitivos
date: '2022-04-11'
excerpt: Tipos Primitivos
featuredImage:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/post-4.jpeg'
  altText: Post thumbnail image
  caption: ''
bottomSections: []
---
#

### Booleano.

![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FV7rf4wz3AWoxafcNuvRR%2Fimage.png?alt=media\&token=aef2f9a5-c6ae-41b2-addf-cf5fcc4262b1)\*bool \*é um tipo de dado primitivo que representa dois valores: verdadeiro ou falso. Em inglês: *true* and *false*.

Vamos fazer um paralelo com java script, nesse primeiro exemplo vamos escrever um codigo JS e outro em solidity.

Booleano em JS:

```
var x;
x = Boolean(false);
if (x) {
}
```

Booleano em Solidity;

```
boll public boo = true;
```

### Endereço (address).

![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2Fz3IMQP47iDp51reuY2BS%2Fimage.png?alt=media\&token=7ae2627b-f102-4cb5-b9f3-0906c414ce8c)o tipo \*address \*armazena endereços de carteiras e outros contratos.

### Números inteiros positivos.

### Texto simples (string).

### Texto com tamanho específico (bytes)

### Listas específicas (arrays)

### Chave e valor (mapping).

### Estrutura de dados (struct).

### Variáveis categóricas (Enums)

![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FLsvSuIleImdPYb2Fv42i%2Fimage.png?alt=media\&token=9a9f531f-98c7-4262-a322-12fbd2bed4cd)Para armazenar números inteiros positivos usamos o tipo \*uint \*e para números de tamanho definido podemos usar por exemplo *uint256* para números de 256 bytes.![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FlQBi7MixfgVX9bIxdOzl%2Fimage.png?alt=media\&token=cda69e7e-bb7a-4fbc-8134-c52b62a742d1)\*string \*é a forma mais comum de armazenar textos mas também podemos usar o formato *bytes32 para tamanhos definidos e otimização de gas.*![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FYYVjrVKzaQTqDK1bqWDP%2Fimage.png?alt=media\&token=9d5d7329-7921-4d05-8685-a646a333b788)É muito importante saber como arrays funcionam pois são muito usados. Há uma semelhança enorme entre *listas* e \*arrays \*e a maior diferença entre eles é que \*arrays são listas de um unico tipo de dado. \*Só podemos ter uma lista de números ou uma lista de textos ou uma lista de endereços... não se pode misturar os tipos de dados.![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2Fua2JVsJz2hH2OoEoyUyO%2Fimage.png?alt=media\&token=8bffb2cc-fad6-4f88-9674-83365c922cf5)Seguindo a lógica de antes primeiro define-se o tipo da variável e depois o seu nome. Para definir um array usa-se o seu tipo de dado mais "\[]".Pode-se dizer que \*mapping \*é como os dicionários em outras linguagens. Utiliza-se um tipo de "lista" de chaves e cada chave guarda um valor.![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FFevCCGCH2UmHMQHdK6tn%2Fimage.png?alt=media\&token=b734b58b-c2d5-479e-954f-6f42801553bf)Nesse caso temos uma "lista" chamada saldos que possui \*endereços \*como \*chave \*e dentro de cada endereço está guardado um valor.É o tipo de dado mais parecido com *Objetos* em outras linguagens. É muito usado para definir uma estrutura padrão de variáveis a serem usadas em contextos específicos. ![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FaJzhMJpgq1iWp0pJuORf%2Fimage.png?alt=media\&token=c1f86aa4-4076-4a42-94e4-beb6d8c3adb1)

Por exemplo, se você construir um programa que precisa do nome de um usuario, seu id e uma lista de produtos ou NFTs que ele comprou, e precisar disso em vários contextos do seu programa a forma mais compreensível e legível de manipular isso é usando uma estrutura definida de variáveis.Enums são muito uteis para categorização de dados, você pode criar uma categoria "Cor" e guardar várias cores dentro dessa categoria e quando precisar de uma determinada cor pode "pedir" um valor que está guardando dentro dessa categoria.

![](https://3038272287-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FXT0NrtKBWFOa2UENeSLs%2Fuploads%2FkfWLUKGLRfcF6a2P20Nv%2Fimage.png?alt=media\&token=81fca74d-852d-48a9-9527-7b462ed814e6)
