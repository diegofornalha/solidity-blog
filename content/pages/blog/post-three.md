---
title: 'Truffle '
layout: PostLayout
date: '2021-07-01'
excerpt: >-
  O Truffle foi criado pela Consensys, é um ambiente de desenvolvimento,
  estrutura de teste e pipeline de ativos para blockchains usando a Ethereum
  Virtual Machine (EVM). Com o Truffle, você obtém muitas características
  importantes que podem ajudá-lo a desenvolver Dapps, como um console interativo
  para comunicação direta de contrato, gerenciamento de rede para implantação em
  qualquer rede pública e privada, compilação de contrato, vinculação e
  gerenciamento binário.


  Outra parte do ecossistema Truffle é o Ganache, um blockchain Ethereum local
  para testar contratos de solidez, você pode usar o Ganache de duas maneiras
  diferentes, você pode usar o Ganache CLI (a versão mais completa) ou pode usar
  a Ganache UI (a versão mais amigável especialmente para iniciantes) cabe a
  você testar e ver qual versão você prefere.
featuredImage:
  type: ImageBlock
  url: /images/3d.gif
  altText: Post Image
bottomSections:
  - elementId: ''
    variant: variant-c
    colors: colors-a
    title: Read next
    recentCount: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: RecentPostsSection
metaTitle: 'Truffle '
addTitleSuffix: true
author: content/data/team/desmond-eagle.json
---
![](https://theblockchainguy.dev/static/truffle-64c064bbfcca8e0234856716ed189dca.png)

O Truffle foi criado pela Consensys, é um ambiente de desenvolvimento, estrutura de teste e pipeline de ativos para blockchains usando a Ethereum Virtual Machine (EVM). Com o Truffle, você obtém muitas características importantes que podem ajudá-lo a desenvolver Dapps, como um console interativo para comunicação direta de contrato, gerenciamento de rede para implantação em qualquer rede pública e privada, compilação de contrato, vinculação e gerenciamento binário.

Outra parte do ecossistema Truffle é o Ganache, um blockchain Ethereum local para testar contratos de solidez, você pode usar o Ganache de duas maneiras diferentes, você pode usar o Ganache CLI (a versão mais completa) ou pode usar a Ganache UI (a versão mais amigável especialmente para iniciantes) cabe a você testar e ver qual versão você prefere.

## Documentação

[A documentação](https://www.trufflesuite.com/docs/truffle/overview) do Truffle é clara e você pode começar a aprender o básico de como criar um projeto, migrar com Truffle develop ou Ganache, conectar o Truffle à metamask e começar a interagir com os contratos.

O Truffle possui uma seção de guias para guiá-lo em tarefas comuns de desenvolvimento do Truffle, esses guias não são um guia passo a passo de um único projeto e não são tão atualizados. O lado bom é que o Truffle não é uma ferramenta nova para o desenvolvimento de blockchain, existem mais artigos e tutoriais por aí, então você pode encontrar muitos recursos devido à longevidade e ao ecossistema de desenvolvimento construído em torno dele.

## Comunidade

A comunidade do Truffle não fica atrás de outras comunidades de desenvolvedores você pode encontrar todos os canais da [comunidade](https://www.trufflesuite.com/community) na seção comunidade do site principal do Truffle, recomendo fazer perguntas no [servidor Discord](https://discord.com/invite/bZwrf3x4Vs) do Consensys existe um canal só sobre o Truffle. Portanto, você pode fazer todas as perguntas que tiver e terá uma resposta o mais rápido possível.

## Você pode encontrar respostas quando está preso fora dos principais canais da comunidade, em lugares como [StackOverflow](https://stackoverflow.com/search?q=truffle) ou [Stackexchange](https://stackexchange.com/search?q=truffle) a comunidade é grande, então encontrar respostas nesses lugares e outros tipos de blogs ou fóruns é algo comum.&#xA;&#xA;Bibliotecas e plug-ins

O ecossistema da Truffle é em torno de [caixas](https://www.trufflesuite.com/boxes) . As caixas de trufas são clichês úteis que aceleram o desenvolvimento do seu projeto para que você possa se concentrar nas partes importantes. As caixas possuem uma combinação de contratos de solidez, bibliotecas e front-end prontos para uso, você pode encontrar caixas oficiais, feitas pela comunidade ou você pode [fazer as suas próprias](https://www.trufflesuite.com/docs/truffle/advanced/creating-a-truffle-box) também.

Cada Box gira essencialmente em torno de um `truffle-box.json`arquivo de configuração. Este arquivo determina quais comandos devem ser executados no ponto de unboxing para que esteja pronto para ser usado. Se você está começando do zero, há uma caixa de [blueprint](https://www.trufflesuite.com/boxes/blueprint) com o arquivo de configuração com valores comuns.

```
// Exemplo de trufa-box.json{  "ignore" : [ "README.md" , ".gitignore" ] ,    "comandos" : {     "Compilar contratos" : "trufa compilar" ,     "Migrar contratos" : "migrar trufas" ,     "Contratos de teste" : "teste de trufas"   },  "ganchos" : {     "pós-descompactar" : ""   }}
```

A desvantagem das caixas não é flexível quando você quer coisas específicas. Você precisa usar a caixa completa e não apenas uma parte dela, e quando quiser substituir ou estender o Truffle para adicionar funcionalidades específicas, como gerar uma gramática UML para cada contrato e usá-la em diferentes projetos, essa não é uma funcionalidade fácil de adicionar.



Teste

O Truffle vem com um conjunto de bibliotecas de teste para facilitar o teste imediatamente, a primeira maneira de testar seus contratos inteligentes é com javascript e typescript. Truffle vem com Mocha, Chai e Web3.js para escrever testes de javascript.

```
const MetaCoin = artefatos . require ( "MetaCoin" ) ;  contract ( "2nd MetaCoin test" , assíncrono ( contas ) => {      it ( "deve colocar 10.000 MetaCoin na primeira conta" , async ( ) => {        instância const = espera MetaCoin . implantado ( ) ;      const balance = aguardar instância . getBalance . chamada ( contas [ 0 ] ) ;     afirmar . igual ( saldo . valueOf ( ) , 10000 ) ;   });  it ( "deve chamar uma função que dependa de uma biblioteca vinculada" , async ( ) => {        const meta = espera MetaCoin . implantado ( ) ;      const outCoinBalance = await meta . getBalance . chamada ( contas [ 0 ] ) ;     const metaCoinBalance = outCoinBalance . toNumero ( ) ;    const outCoinBalanceEth = await meta . getBalanceInEth . chamada ( contas [ 0 ] ) ;     const metaCoinEthBalance = outCoinBalanceEth . toNumero ( ) ;    afirmar . igual ( metaCoinEthBalance , 2 * metaCoinBalance ) ;    });  it ( "deve enviar moeda corretamente" , assíncrono ( ) => {        const conta_um = contas [ 0 ] ;    const conta_dois = contas [ 1 ] ;    deixe o equilíbrio ;    quantidade const = 10 ;     instância const = espera MetaCoin . implantado ( ) ;      const meta = instância ;    saldo = espera meta . getBalance . chamar ( conta_um ) ;     const account_one_starting_balance = saldo . toNumero ( ) ;    saldo = espera meta . getBalance . chamar ( conta_dois ) ;     const account_two_starting_balance = saldo . toNumero ( ) ;    aguardo meta . sendCoin ( conta_dois , quantidade , { de : conta_um } ) ;      saldo = espera meta . getBalance . chamar ( conta_um ) ;     const account_one_ending_balance = saldo . toNumero ( ) ;    saldo = espera meta . getBalance . chamar ( conta_dois ) ;     const account_two_ending_balance = saldo . toNumero ( ) ;    afirmar . igual (      account_one_ending_balance ,      account_one_starting_balance - valor ,      "O valor não foi retirado corretamente do remetente"    );    afirmar . igual (      account_two_ending_balance ,      account_two_starting_balance + valor ,      "O valor não foi enviado corretamente ao destinatário"    );  });});
```

Saída:

```
Contrato: MetaCoin    √ deve colocar 10.000 MetaCoin na primeira conta ( 83ms )    √ deve chamar uma função que depende de uma biblioteca vinculada ( 43ms )    √ deve enviar moeda corretamente ( 122ms )  3 passes ( 293ms )
```

A outra forma de fazer testes é no Solidity, para testar seus contratos em cenários mais avançados. A estrutura de teste Solidity da Truffle foi feita com esses tipos de problemas em mente:

*   ▪︎Os testes de solidez não devem se estender de nenhum contrato. Isso lhe dá controle total dos contratos que você escreve.

*   ▪︎ Os testes de solidez não devem ser vinculados a nenhuma biblioteca de asserções. O Truffle vem com uma biblioteca de asserções padrão, mas você pode alterar essa biblioteca para atender aos requisitos do seu projeto.

*   ▪︎ Você deve ser capaz de executar seus testes de Solidity em qualquer cliente Ethereum.

Exemplo de teste de solidez:

```
solidez do pragma > = 0,4 , 25 < 0,6 , 0 ; import "trufa/Assert.sol" ; import "trufa/DeployedAddresses.sol" ; import "../contracts/MetaCoin.sol" ; contrato TestMetaCoin {   function testInitialBalanceUsingDeployedContract ( ) {      MetaCoin meta = MetaCoin ( DeployedAddresses . MetaCoin ( ) ) ;     uint esperado = 10000 ;     Afirmar . equal ( meta.getBalance ( tx.origem ) , esperado , " O proprietário deve ter 10.000 MetaCoin inicialmente " ) ;   }  function testInitialBalanceWithNewMetaCoin ( ) {      MetaCoin meta = new MetaCoin ( ) ;      uint esperado = 10000 ;     Afirmar . equal ( meta.getBalance ( tx.origem ) , esperado , " O proprietário deve ter 10.000 MetaCoin inicialmente " ) ;   }}
```

Saída:

```
$ teste de trufasCompilando seus contratos .. .===========================> Compilando ./test/TestMetaCoin.sol  TestMetaCoin    ✓ testInitialBalanceWithNewMetaCoin ( 65ms )  Contrato: MetaCoin    ✓ deve colocar 10000 MetaCoin na primeira conta ( 38ms )  1 passe ( 7s )
```




