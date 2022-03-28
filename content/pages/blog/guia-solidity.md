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

\*\*pública: \*\*parte da interface do contrato e pode ser acessada de outros contratos.

\*\*interna: \*\*acessada somente dentro do contrato atual.

\*\*privada: \*\*visível apenas para o contrato em que está definida.

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

```
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
```

}

Este exemplo apresenta os seguintes itens:

Uma variável com um tipo 

\*\*address \*\*que armazena o endereço Ethereum de 20 bytes do usuário vendedor. Você aprenderá mais sobre essas variáveis mais adiante neste módulo.

Um modificador chamado `onlySeller` que descreve que apenas um vendedor pode listar um item.

Um símbolo especial `_;` para indicar em que local o corpo da função é inserido.

Uma definição de função que usa o modificador `onlySeller`. Modificadores de função adicionais que podem ser usados na definição de função: \*\*pure \*\*para descrever funções que não permitem modificações nem acesso ao estado.

\*\*view \*\*para descrever funções que não permitem modificações de estado.

**payable** para descrever as funções que podem receber Ether.

## Eventos

Eventos descrevem as ações que são executadas no contrato. Semelhante às funções, os eventos têm parâmetros que precisam ser especificados quando o evento é chamado.

Para chamar um evento, você deve usar a palavra-chave **emit** com o nome do evento e os parâmetros dele.

pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
event PurchasedItem(address buyer, uint price);

```
function buy() public {
    // ...
    emit PurchasedItem(msg.sender, msg.value);
}
```

}

Quando você chama um evento, ele é capturado como uma transação no log de transações, que é uma estrutura de dados especial no blockchain. Esses logs são associados ao endereço do contrato, são incorporados ao blockchain e permanecem lá para sempre. O log e seus dados de evento não estão acessíveis de dentro de contratos e não podem ser modificados.

# Explorar tipos de valor

A seguir oss tipos de valor principal no Solidity. Os tipos de valor são passados por valor e copiados quando usados. Os tipos de valor primário que você usará ao escrever contratos incluem **inteiro**, **booliano**, **literal de cadeia de caracteres**, **endereço** e **enumeração**.

## Inteiros

Os inteiros são usados em cada arquivo de origem do Solidity. Eles representam números inteiros e podem ser com ou sem sinal. Intervalo de inteiros no tamanho do armazenamento de 8 bits a 256 bits.

*   Assinado: inclui números negativos e positivos. Pode ser representado como **int**.

*   Sem sinal: incluem apenas números positivos. Pode ser representado como **uint**.

Se um número de bits não for especificado, o valor padrão será de 256 bits.

As seguintes operações podem ser aplicadas a inteiros:

*   Comparações: `<=`, `<`, `==`, `!=`, `>=`, `>`

*   Operadores de bits: `& (and)`, `| (or)`, `^ (bitwise exclusive)`, `~ (bitwise negation)`

*   Operadores aritméticos: `+ (addition)`,`- (subtraction)`, `* (multiplication)`, `/ (division)`, `% (modulo)`, `** (exponential)`

Aqui estão alguns exemplos de definições de inteiro:

```
int32 price = 25; // signed 32 bit integer
uint256 balance = 1000; // unsigned 256 bit integer

balance - price; // 975
2 * price; // 50
price % 2; // 1

```

## Booleano

Os booleanos são definidos usando a palavra-chave **bool**. Eles sempre têm um valor de `true` ou `false`.

Veja como eles podem ser definidos:

```
bool forSale; //true if an item is for sale
bool purchased; //true if an item has been purchased

```

Os boolianos são comumente usados em instruções de comparação. Por exemplo:

```
if(balance > 0 & balance > price) {
    return true;
}

if(price > balance) {
    return false;
}

```

Os booleanos também podem ser usados em parâmetros de função e tipos de retorno.

```
function buy(int price) returns (bool success) {
    // ...
}

```

## Literais de cadeia de caracteres

Literais de cadeia de caracteres também são usados na maioria dos arquivos de contrato. Eles são caracteres ou palavras entre aspas duplas ou simples.

```
    String shipped = "shipped"; // shipped
    String delivered = 'delivered'; // delivered
    String newItem = "newItem"; // newItem

```

Além disso, os seguintes caracteres de escape podem ser usados com literais de cadeia de caracteres:

*   `\<newline>` ignora uma nova linha

*   `\n` nova linha

*   `\r` retorno de carro

*   `\t` tabulação

## Endereço

Um endereço é um tipo com um valor de 20 bytes que representa uma conta de usuário do Ethereum. Esse tipo pode ser um **address** regular ou um **address payable**.

A diferença entre os dois é que um tipo **address payable** é um endereço para o qual você pode enviar Ether e que contém os membros adicionais e `send`.

```
address payable public seller; // account for the seller
address payable public buyer; // account for the user

function transfer(address buyer, uint price) {
    buyer.transfer(price); // the transfer member transfers the price of the item
}

```

## Enumerações

No Solidity, você pode usar enumerações para criar um tipo definido pelo usuário. Ele é chamado de definido pelo usuário porque a pessoa que cria o contrato decide quais valores incluir. As enumerações podem ser usadas para apresentar muitas opções selecionáveis, uma das quais é obrigatória.

Uma **enumeração** pode ser usada, por exemplo, para apresentar status diferentes para um item. Você pode considerar enumerações como a representação de respostas de várias opções em que todos os valores são predefinidos e você precisa selecionar um. Enumerações podem ser declaradas em definições de contrato ou de biblioteca.

```
enum Status { 
    Pending,
    Shipped,
    Delivered 
}

Status public status;

constructor() public {
    status = Status.Pending;
}

```

# Explorar documentos de referência

Ao escrever contratos, você também deve compreender os tipos de referência.

Ao contrário dos tipos de valor, que sempre passam uma cópia independente do valor, os tipos de referência fornecem um **local de dados** para o valor. Os três tipos de referência são: **structs**, **matrizes** e **mapeamentos**.

## Local dos dados

Ao usar um tipo de referência, você deve fornecer explicitamente o local de armazenamento de dados para ele. As seguintes opções podem ser usadas para especificar o local dos dados em que o tipo é armazenado:

*   `memory`:

    *   O local em que os argumentos de função são armazenados.

    *   Tem um tempo de vida limitado ao tempo de vida de uma chamada de função externa.

*   `storage`:

    *   O local em que as variáveis de estado são armazenadas.

    *   Tem um tempo de vida limitado ao tempo de vida do contrato.

*   `calldata`:

    *   O local em que os argumentos de função são armazenados.

    *   Este local é necessário para parâmetros de funções externas, mas também pode ser usado para outras variáveis.

    *   Tem um tempo de vida limitado ao tempo de vida de uma chamada de função externa.

Tipos de referência sempre criam uma cópia independente dos dados.

Aqui está um exemplo de como usar um tipo de referência:

```
contract C {

  uint[] x;
  
  // the data location of values is memory
  function buy(uint[] memory values) public {
      x = value; // copies array to storage
      uint[] storage y = x; //data location of y is storage
      g(x); // calls g, handing over reference to x
      h(x); // calls h, and creates a temporary copy in memory
  }

  function g(uint[] storage) internal pure {}
  function h(uint[] memory) public pure {}
}

```

## Matrizes

As matrizes são uma forma de armazenar dados semelhantes em uma estrutura de dados definida. As matrizes podem ter um tamanho fixo ou dinâmico. Seus índices começam em 0.

Para criar uma matriz de `k` de tamanho fixo e tipo de elemento `T`, você escreveria `T[k]`. Para uma matriz de dimensionamento dinâmico, você escreveria `T[]` .

Elementos de matriz podem ser de qualquer tipo. Por exemplo, podem conter **uint**, **memória** ou **bytes**. As matrizes também podem incluir **mapeamentos** ou **structs**.

Os exemplos a seguir mostram a criação da matriz:

```
uint[] itemIds; // Declare a dynamically sized array called itemIds
uint[3] prices = [1, 2, 3]; // initialize a fixed size array called prices, with prices 1, 2, and 3
uint[] prices = [1, 2, 3]; // same as above

```

### Membros de matriz

Os seguintes membros podem manipular e obter informações sobre matrizes:

*   **length**: obter o comprimento de uma matriz.

*   **push()**: acrescentar um elemento no final da matriz.

*   **pop**: remover um elemento do final de uma matriz.

Estes são alguns exemplos:

```
// Create a dynamic byte array
bytes32[] itemNames;
itemNames.push(bytes32("computer")); // adds "computer" to the array
itemNames.length; // 1

```

## Estruturas

Structs são tipos personalizados que um usuário pode definir para representar objetos do mundo real. Normalmente, structs são usados como um esquema ou para representar registros.

Exemplo de uma declaração de estrutura:

```
struct Items_Schema {
    uint256 _id;
    uint256 _price;
    string _name;
    string _description;
}

```

## Tipos de mapeamento

Os mapeamentos são pares chave-valor encapsulados ou empacotados juntos. Os mapeamentos estão mais próximos de dicionários ou objetos em JavaScript. Normalmente, você usa mapeamentos para modelar objetos do mundo real e realizar pesquisas de dados mais rápidas. Os valores podem incluir tipos complexos como structs, o que torna o tipo de mapeamento flexível e legível por humanos.

O exemplo de código a seguir usa o struct `Items_Schema` e salva uma lista de itens representados pelo `Items_Schema` como um dicionário. Dessa forma, o mapeamento imita um banco de dados.

```
contract Items {
    uint256 item_id = 0;

    mapping(uint256 => Items_Schema) public items;

    struct Items_Schema {
      uint256 _id:
      uint256 _price:
      string _name;
    }

    function listItem(uint 256 memory _price, string memory _name) public {
      item_id += 1;
      item[vehicle_id] = Items_Schema(item_id, _price, _name);
    }
}

```

` Observação`

`A assinatura de mapeamento uint256 => Items_Schema indica que as chaves são um tipo inteiro sem sinal e os valores são de tipo struct Items_Schema.`


# Solidity para criar um contrato inteligente para um marketplace online simples. 

Este contrato permitirá aos usuários listar um item para venda e comprar um item disponível. Há duas funções envolvidas: um vendedor e um comprador.

## Exemplo de marketplace simples

```
pragma solidity >0.7.0 <0.8.0;

contract Marketplace {
    address public seller;
    address public buyer;
    mapping (address => uint) public balances;

    event ListItem(address seller, uint price);
    event PurchasedItem(address seller, address buyer, uint price);

    enum StateType {
          ItemAvailable,
          ItemPurchased
    }

    StateType public State;

    constructor() public {
        seller = msg.sender;
        State = StateType.ItemAvailable;
    }

    function buy(address seller, address buyer, uint price) public payable {
        require(price <= balances[buyer], "Insufficient balance");
        State = StateType.ItemPurchased;
        balances[buyer] -= price;
        balances[seller] += price;

        emit PurchasedItem(seller, buyer, msg.value);
    }
}    

```

Vamos nos aprofundar nos principais componentes deste contrato inteligente:

*   Elas são:

    *   Três variáveis de estado: `buyer`, `seller` e `balances`

    *   Dois eventos: `ListItem` e `PurchasedItem`

    *   Uma enumeração com dois valores: `ItemAvailable` e `ItemPurchased`

*   O construtor designa o usuário do vendedor como `msg.sender` e define o estado inicial como `ItemAvailable`. Esse construtor é chamado quando o contrato é criado.

*   A função `buy` usa três parâmetros: `seller`, `buyer` e `price`. Ela exige que o comprador tenha dinheiro suficiente para a compra. Em seguida, transfere o dinheiro do comprador para o vendedor e, por fim, uma mensagem é emitida.

## Próximas etapas

Acesse [Remix IDE](https://remix.ethereum.org/) para explorar mais exemplos de contratos inteligentes no Solidity. O [remix ](https://solidity.coflow.com.br/blog/remix/)é um IDE no navegador que permite que você comece imediatamente sem precisar criar uma conta nem logar. Você pode gravar, testar, compilar e implantar contratos imediatamente.

Copie e cole este contrato inteligente no [Remix ](https://solidity.coflow.com.br/blog/remix/)em um novo arquivo chamado `Marketplace.sol`. Em seguida, compile e implante o contrato. Embora o contrato tenha uma função para comprar um item disponível, você observará que não é possível fornecer uma moeda do comprador para fazer a compra. Como desafio extra, use o que você aprendeu para escrever uma função para dar um saldo ao comprador, fornecendo um endereço de conta e um valor. Se quiser ver um exemplo de como fazer isso, assista ao [Dr. G adicionar uma função para inicializar um saldo para os participantes](https://aka.ms/LearnWithDrG/Blockchain/Challenge1).



