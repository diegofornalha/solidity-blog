---
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Guia Completo de Solidity Grátis
date: '2022-03-28'
excerpt: >-
  O Solidity é uma linguagem orientada a objeto para escrever contratos
  inteligentes.


  Contratos inteligentes são programas armazenados dentro de um blockchain. Eles
  especificam as regras e o comportamento de como os ativos digitais são
  transferidos. Você usa o Solidity para programar contratos inteligentes para a
  plataforma de blockchain Ethereum. Os contratos inteligentes contêm lógica
  programável e estado. As transações resultam em funções executadas em
  contratos inteligentes. Assim, os contratos inteligentes permitem que você
  crie um fluxo de trabalho empresarial.


  Visão geral

  O Solidity é a linguagem de programação mais popular para o blockchain
  Ethereum.


  O Solidity é uma linguagem de alto nível baseada em outras linguagens de
  programação, incluindo C++, Python e JavaScript. Caso você conheça qualquer
  uma dessas linguagens, o código do Solidity vai parecer familiar.


  O Solidity tem tipo estático, o que significa que a verificação de tipo ocorre
  em tempo de compilação, não em tempo de execução, como em linguagens com tipo
  dinâmico. Com uma linguagem de tipo estático, você precisa especificar o tipo
  de cada variável. Por exemplo, Python e JavaScript são linguagens de tipo
  dinâmico, enquanto C++ tem tipo estático.


  O Solidity dá suporte à herança, o que significa que as funções, variáveis e
  outras propriedades presentes em um contrato podem ser usadas em outra. A
  linguagem também dá suporte a tipos complexos definidos pelo usuário, como
  structs e enums, que permitem agrupar tipos de dados relacionados.


  O Solidity é uma linguagem de programação de software livre com uma comunidade
  crescente de colaboradores. Para saber mais sobre o projeto do Solidity e como
  contribuir, confira o repositório do GitHub.


  O que é o Ethereum?

  Antes de continuarmos, você também deve familiarizar-se com o Ethereum.


  O Ethereum é uma das plataformas blockchain mais populares, logo atrás do
  Bitcoin. É uma tecnologia criada pela comunidade e tem a própria criptomoeda
  chamada de ETH (Ether ) que você pode comprar e vender.


  O que torna o Ethereum exclusivo é que ele é o "blockchain programável do
  mundo". Usando o Ethereum, você pode codificar definições de contrato, também
  conhecidas como contratos inteligentes. Os contratos inteligentes são usados
  para descrever como os participantes do blockchain transferem ativos digitais.
  O Solidity é a principal linguagem de programação usada para desenvolvimento
  na plataforma Ethereum, que foi criada e mantida por desenvolvedores do
  Ethereum.


  Máquina virtual do Ethereum

  Os contratos do Solidity são executados na EVM, a máquina virtual do Ethereum.
  É um ambiente de área restrita completamente isolado. Ele não acessa nada mais
  na rede além dos contratos que executa. Você não precisa saber muito mais
  sobre EVM por enquanto, mas lembre-se de que os contratos inteligentes do
  Solidity serão implantados e executados em um ambiente virtual.
featuredImage:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/post-4.jpeg'
  altText: Post thumbnail image
  caption: ''
bottomSections: []
layout: PostLayout
---
O Solidity é uma linguagem orientada a objeto para escrever contratos inteligentes.

Contratos inteligentes são programas armazenados dentro de um blockchain. Eles especificam as regras e o comportamento de como os ativos digitais são transferidos. Você usa o Solidity para programar contratos inteligentes para a plataforma de blockchain Ethereum. Os contratos inteligentes contêm lógica programável e estado. As transações resultam em funções executadas em contratos inteligentes. Assim, os contratos inteligentes permitem que você crie um fluxo de trabalho empresarial.

O Solidity é a linguagem de programação mais popular para o blockchain Ethereum.

O Solidity é uma linguagem de alto nível baseada em outras linguagens de programação, incluindo C++, Python e JavaScript. Caso você conheça qualquer uma dessas linguagens, o código do Solidity vai parecer familiar.

O Solidity tem tipo estático, o que significa que a verificação de tipo ocorre em tempo de compilação, não em tempo de execução, como em linguagens com tipo dinâmico. Com uma linguagem de tipo estático, você precisa especificar o tipo de cada variável. Por exemplo, Python e JavaScript são linguagens de tipo dinâmico, enquanto C++ tem tipo estático.

O Solidity dá suporte à herança, o que significa que as funções, variáveis e outras propriedades presentes em um contrato podem ser usadas em outra. A linguagem também dá suporte a tipos complexos definidos pelo usuário, como structs e enums, que permitem agrupar tipos de dados relacionados.

O Solidity é uma linguagem de programação de software livre com uma comunidade crescente de colaboradores. Para saber mais sobre o projeto do Solidity e como contribuir, confira o repositório do GitHub.

O que é o Ethereum?
Antes de continuarmos, você também deve familiarizar-se com o Ethereum.

O Ethereum é uma das plataformas blockchain mais populares, logo atrás do Bitcoin. É uma tecnologia criada pela comunidade e tem a própria criptomoeda chamada de ETH (Ether ) que você pode comprar e vender.

O que torna o Ethereum exclusivo é que ele é o "blockchain programável do mundo". Usando o Ethereum, você pode codificar definições de contrato, também conhecidas como contratos inteligentes. Os contratos inteligentes são usados para descrever como os participantes do blockchain transferem ativos digitais. O Solidity é a principal linguagem de programação usada para desenvolvimento na plataforma Ethereum, que foi criada e mantida por desenvolvedores do Ethereum.

# Máquina virtual do Ethereum


Os contratos do Solidity são executados na EVM, a máquina virtual do Ethereum. É um ambiente de área restrita completamente isolado. Ele não acessa nada mais na rede além dos contratos que executa. Você não precisa saber muito mais sobre EVM por enquanto, mas lembre-se de que os contratos inteligentes do Solidity serão implantados e executados em um ambiente virtual.

Compreenda os conceitos básicos da linguagem

Todos os contratos do Solidity normalmente incluem:

Diretivas pragma

Variáveis de estado

Funções

Eventos

Embora você precise saber mais para programar contratos inteligentes em nível de produção, essas informações deverão colocar você no caminho certo.

Se você compreende esses conceitos, pode começar a escrever contratos inteligentes para uma variedade de usos de casos imediatamente.

Diretivas pragma

**Pragma** é a palavra-chave que você usa para solicitar que o compilador verifique se sua versão do Solidity corresponde à necessária. Uma correspondência significa que o arquivo de origem pode ser executado com êxito. Se não houver correspondência, o compilador apresentará um erro.

Sempre inclua a versão mais recente do Solidity em sua definição de contrato. Para encontrar a versão atual do Solidity, acesse o [site do Solidity](https://solidity.readthedocs.io/). Use a versão mais recente no arquivo de origem.

Uma diretiva pragma de versão tem esta aparência:

`pragma solidity ^0.7.0;`

Essa linha significa que o arquivo de origem será compilado com um compilador superior à versão `0.7.0`, até `0.7.9`. Da versão `0.8.0` em diante, provavelmente haverá alterações significativas que causarão a falha na compilação do arquivo de origem.

Variáveis de estado

As variáveis de estado são fundamentais para qualquer arquivo de origem do Solidity. Os valores da variável de estado são armazenados permanentemente no armazenamento de contratos.

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    uint price; // State variable  


` Observação`

`Os arquivos de origem do contrato sempre começam com a definição contract ContractName.`

Neste exemplo, a variável de estado tem o nome `price` com o tipo `price`. O tipo de inteiro uint indica que essa variável é um inteiro sem sinal com 256 bits. Isso significa que ele pode armazenar números positivos no intervalo de 0 a 2256 -1.

Para todas as definições de variáveis, você deve especificar o tipo e o nome da variável.

Além disso, você pode especificar a visibilidade de uma variável de estado como:

**pública: **parte da interface do contrato e pode ser acessada de outros contratos.

**interna: **acessada somente dentro do contrato atual.

**privada: **visível apenas para o contrato em que está definida.

## Funções

Em um contrato, as unidades de código executáveis são conhecidas como funções. As funções descrevem uma única ação para obter uma tarefa. Elas são reutilizáveis e também podem ser chamadas de outros arquivos de origem, como bibliotecas. As funções do Solidity se comportam de modo semelhante às funções em outras linguagens de programação.

Aqui está um exemplo básico de definição de uma função:

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    function buy() public {
        // ...
    }
}


Esse código mostra uma função com o nome `buy` que tem uma visibilidade pública, o que significa que pode ser acessado por outros contratos. O Functions pode usar um dos seguintes especificadores de visibilidade: **pública**, **privada**, **interna** e **externa**.

Uma função pode ser chamada interna ou externamente de outro contrato. As funções podem aceitar parâmetros e retornar variáveis para passar parâmetros e valores entre eles.

Aqui está um exemplo de uma função que aceita um parâmetro – um inteiro chamado `price` – e retorna um inteiro:

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    function buy(uint price) public returns (uint) {
        // ...
    }
}


Modificadores de função

Os modificadores de função podem ser usados para alterar o comportamento das funções. Eles funcionam verificando uma condição antes que ela seja executada. Por exemplo, uma função pode verificar se apenas um usuário designado como um vendedor pode listar um item para venda.

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    address public seller;

    modifier onlySeller() {
        require(
            msg.sender == seller,
            "Only seller can put an item up for sale."
        );
        \_;
    }

    function listItem() public view onlySeller {
        // ...
    }
}


Este exemplo apresenta os seguintes itens:

Uma variável com um tipo 

**address **que armazena o endereço Ethereum de 20 bytes do usuário vendedor. Você aprenderá mais sobre essas variáveis mais adiante neste módulo.

Um modificador chamado `onlySeller` que descreve que apenas um vendedor pode listar um item.

Um símbolo especial `_;` para indicar em que local o corpo da função é inserido.

Uma definição de função que usa o modificador `onlySeller`. Modificadores de função adicionais que podem ser usados na definição de função: **pure **para descrever funções que não permitem modificações nem acesso ao estado.

**view **para descrever funções que não permitem modificações de estado.

**payable** para descrever as funções que podem receber Ether.

## Eventos

Eventos descrevem as ações que são executadas no contrato. Semelhante às funções, os eventos têm parâmetros que precisam ser especificados quando o evento é chamado.

Para chamar um evento, você deve usar a palavra-chave **emit** com o nome do evento e os parâmetros dele.

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    event PurchasedItem(address buyer, uint price);

    function buy() public {
        // ...
        emit PurchasedItem(msg.sender, msg.value);
    }
}


Quando você chama um evento, ele é capturado como uma transação no log de transações, que é uma estrutura de dados especial no blockchain. Esses logs são associados ao endereço do contrato, são incorporados ao blockchain e permanecem lá para sempre. O log e seus dados de evento não estão acessíveis de dentro de contratos e não podem ser modificados.

