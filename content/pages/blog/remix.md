---
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Remix
date: '2022-03-24'
excerpt: >-
  Remix é um aplicativo de web e desktop de código aberto. O Remix é usado para
  escrever, testar e implantar contratos inteligentes, você pode usá-lo como um
  playground para aprender e ensinar o desenvolvimento de blockchain. O Remix
  IDE faz parte do projeto Remix que é uma plataforma para ferramentas de
  desenvolvimento que usam uma arquitetura de plugins.


  O Remix é composto por uma cadeia de subprojetos, incluindo Remix Plugin
  Engine, Remix Libs e, claro, Remix IDE. Ele é escrito em javascript e suporta
  uma versão de navegador e desktop.
featuredImage:
  type: ImageBlock
  url: /images/remix.png
  altText: Post thumbnail image
  caption: ''
bottomSections: []
layout: PostLayout
---
Remix é um aplicativo de web e desktop de código aberto. O Remix é usado para escrever, testar e implantar contratos inteligentes, você pode usá-lo como um playground para aprender e ensinar o desenvolvimento de blockchain. O Remix IDE faz parte do projeto Remix que é uma plataforma para ferramentas de desenvolvimento que usam uma arquitetura de plugins.

O Remix é composto por uma cadeia de subprojetos, incluindo Remix Plugin Engine, Remix Libs e, claro, Remix IDE. Ele é escrito em javascript e suporta uma versão de navegador e desktop.

## Documentação

[A documentação](https://remix-ide.readthedocs.io/en/latest/) do Remix é feita de forma que mesmo você não tenha experiência em desenvolver software blockchain será fácil para você começar a aprender. Você verá várias imagens com setas e texto para identificar cada ferramenta do Remix, assim, você se familiarizará com ela muito rapidamente e começará a personalizar o Remix para suas próprias necessidades. A documentação não se limita apenas a mostrar partes da interface do usuário, eles mostram como usar o remix com diferentes integrações, por exemplo , [Hardhat](https://remix-ide.readthedocs.io/en/latest/hardhat.html) , como fazer testes de unidade e outros aspectos importantes para dominar o Remix.

A outra parte boa é que eles atualizam a documentação com frequência, isso é uma coisa muito boa porque a documentação sobre ferramentas blockchain geralmente não é atualizada e esse é um aspecto importante para esse ambiente em constante mudança, mesmo que você veja um erro, você pode abrir um problema em Github ou corrija essa edição você mesmo e fez um pull request para o repositório de documentação.

Exemplo de documentação do Remix explicando a guia do compilador.![](https://theblockchainguy.dev/static/github-edit-5155d610b99d403f4ad59fd31289a3ca.png)Você pode editar a documentação do Remix se vir algum erro ou quiser adicionar mais conteúdo.

## Comunidade

A comunidade do Remix é muito solidária, você pode encontrar a resposta de suas dúvidas se estiver preso no canal principal do [gitter](https://gitter.im/ethereum/remix) e pedir ajuda de qualquer membro da comunidade.

Se você quer ajudar a desenvolver um plugin customizado ou tem dúvidas em desenvolver um plugin para você ou para a empresa que você trabalha pode ir ao [canal dos contribuidores](https://gitter.im/ethereum/remix-dev) se quiser mais informações sobre como trabalhar nas ferramentas do Remix.

A comunidade tem algum tempo para encontrar respostas em outros lugares fora da comunidade principal, quando você está preso, sua fonte primária será [StackOverflow](https://stackoverflow.com/search?q=remix) e depois [Stackexchange](https://stackexchange.com/) .

Teste

O teste com o Remix é feito apenas com solidez e é a maneira mais fácil de implementar testes em seus contratos inteligentes, especialmente quando você está começando a aprender sobre desenvolvimento de blockchain. O plug-in de teste de unidade de solidez já está ativo e você verá um exemplo de teste de contrato para ter um exemplo de como o teste funciona dentro do Remix.

Exemplo de teste de solidez com Remix:

```
// SPDX-License-Identifier: GPL-3.0solidez do pragma > = 0,7 ,0 < 0,9 , 0 ; import "remix_tests.sol" ; // esta importação é injetada automaticamente pelo Remix.  import "../contracts/3_Ballot.sol" ; contrato VotoTeste {    bytes32[] proposalNames;    Votação ballotToTest ;    function beforeAll ( ) public {            propostaNomes . push ( bytes32 ( "candidato1" ) ) ;        ballotToTest = new Ballot ( propostaNomes ) ;      }    função checkWinningProposal ( ) public {            ballotToTest . voto ( 0 ) ;        Afirmar . equal ( ballotToTest .winningProposal ( ) , uint ( 0 ) , " a proposta no índice 0 deve ser a proposta vencedora" ) ;          Afirmar . equal ( ballotToTest . WinnerName ( ) , bytes32 ( "candidate1" ) , "candidate1 deve ser o nome do vencedor" ) ;      }    function checkWinninProposalWithReturnValue ( ) public view return ( bool ) {             return ballotToTest . Proposta vencedora ( ) == 0 ;      }}
```

Para ver se seu teste foi aprovado ou reprovado, clique no ícone de verificação e clique em executar para executar seus testes. Você pode pesquisar o motivo pelo qual eles estão falhando, haverá detalhes da afirmação para o motivo da falha. Se você clicar no teste com falha, verá a linha de código em que o teste falha.

Você pode personalizar seus testes com apenas alguns cliques, como a versão do compilador do solidity ou a versão EVM para testar seus contratos inteligentes em diferentes cenários.

![](https://theblockchainguy.dev/static/remix-test-d306c33833104c27f8d4571270a1d0a0.png)Teste de remixagem usando o plug-in de teste de unidade de solidez.![](https://theblockchainguy.dev/static/remix-test-customization-e1019222291d0099c8ec8997369aa45b.png)Aba de personalização de remixes.

## **Quais empresas usam o Remix?**

OpenSea é um mercado de token não fungível (NFT) descentralizado para compra, venda e negociação de NFTs. A marca OpenSea como o maior mercado para produtos digitais foi construída por meio de uma colaboração enxuta e uma vontade de investir em novas tecnologias empolgantes.

O Ethereum.org é um recurso público e de código aberto para a comunidade Ethereum com o qual qualquer pessoa pode contribuir, é um recurso educacional, projetado para ajudar novos usuários a se familiarizarem com o Ethereum e seus principais conceitos.

Moonbeam é uma blockchain orientada para o desenvolvedor que se esforça para fornecer compatibilidade com a cadeia de ferramentas e a rede do desenvolvedor Ethereum existente. Ele faz isso fornecendo uma implementação completa de EVM, uma API compatível com Web3 e pontes que conectam o Moonbeam às redes Ethereum existentes.

