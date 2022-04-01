---
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: Lógica confiável
date: '2022-03-28'
excerpt: >-
  O blockchain nos permite armazenar dados que sejam consistentes e que possam
  ser confiáveis. Como adicionar lógica que execute a mesma coisa em cada nó?


  Em nosso cenário, precisamos de lógica para transferir a responsabilidade do
  produto de um participante para outro. Também precisamos usar dados do sensor
  de temperatura IoT para saber se a temperatura está muito alta.


  Um DApp (aplicativo descentralizado) é um aplicativo em um sistema de
  computação distribuída. Neste módulo, vamos nos concentrar no uso do protocolo
  de blockchain Ethereum. Os DApps do Ethereum são chamados de contratos
  inteligentes. Um contrato inteligente contém a lógica que é executada como
  parte de uma transação. No Ethereum, você programa a lógica usando uma
  linguagem de programação chamada Solidity.


  Os contratos inteligentes são implantados no blockchain e são referenciados
  por um endereço. Para usar um contrato inteligente, você cria uma instância.
  Uma instância de contrato inteligente contém dados de estado e lógica de
  programa. Em nosso cenário, uma instância de contrato inteligente contém dados
  como, o participante responsável, a localização e se a temperatura do produto
  está fora de conformidade. Podemos executar funções para transferir a
  responsabilidade ou receber telemetria de temperatura de uma instância.
featuredImage:
  type: ImageBlock
  url: /images/3d.gif
  altText: Post thumbnail image
  caption: ''
bottomSections: []
layout: PostLayout
---
Um DApp (aplicativo descentralizado) é um aplicativo em um sistema de computação distribuída. Vamos nos concentrar no uso do protocolo de blockchain Ethereum. Os DApps do Ethereum são chamados de contratos inteligentes. Um contrato inteligente contém a lógica que é executada como parte de uma transação. No Ethereum, você programa a lógica usando uma linguagem de programação chamada Solidity.

Os contratos inteligentes são implantados no blockchain e são referenciados por um endereço. Para usar um contrato inteligente, você cria uma instância. Uma instância de contrato inteligente contém dados de estado e lógica de programa. Em nosso cenário, uma instância de contrato inteligente contém dados como, o participante responsável, a localização e se a temperatura do produto está fora de conformidade. Podemos executar funções para transferir a responsabilidade ou receber telemetria de temperatura de uma instância.

![](https://docs.microsoft.com/pt-br/learn/modules/intro-to-blockchain/media/smart-contract.png)

Quando a responsabilidade de um produto é transferida para outra parte, uma transação é executada. A lógica do contrato inteligente atualiza os dados de estado. Em  um cenário de distribuição de sorvetes, o sistema de transporte da fábrica de sorvete cria uma instância de contrato inteligente para uma nova remessa de sorvete. O sistema de transporte da fábrica envia uma transação que chama a função *TransferResponsibility* para transferir a responsabilidade da remessa para a Contoso East Shipping. A rede blockchain envia a transação para todos os nós. A lógica do contrato inteligente é executada em cada nó.

![](https://docs.microsoft.com/pt-br/learn/modules/intro-to-blockchain/media/smart-contract-transaction.png)

E se, durante a remessa, a unidade de refrigeração falhar e a temperatura do sorvete ficar acima da temperatura de congelamento? Um sensor de temperatura IoT monitora a temperatura do sorvete e envia transações periodicamente. Se a temperatura estiver acima do congelamento, a lógica do contrato inteligente marcará a remessa como fora de conformidade.

![](https://docs.microsoft.com/pt-br/learn/modules/intro-to-blockchain/media/iot-transaction.png)

Como a transação está incluída em uma cadeia de blocos, há um registro imutável de quando a remessa ficou fora de conformidade. A sorveteria pode recusar a entrega e pode evitar problemas com a segurança dos alimentos.

Assim como os dados no blockchain, um contrato inteligente é imutável. Uma vez implantado, a lógica não pode ser alterada. Portanto, você pode confiar que a lógica do contrato inteligente sempre executa da mesma forma em todos os nós. Qualquer alteração de código exige que um novo contrato inteligente seja implantado em um novo endereço.
