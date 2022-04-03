---
layout: PostLayout
metaTitle: null
metaDescription: null
addTitleSuffix: true
socialImage: null
metaTags: []
title: |-
  CONTRATO INTELIGENTE
  VERIFICAÇÃO DE SEGURANÇA
  PADRÃO
date: '2022-04-03'
excerpt: CONTRATO INTELIGENTE
featuredImage:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/post-4.jpeg'
  altText: CONTRATO INTELIGENTE
  caption: CONTRATO INTELIGENTE
bottomSections: []
---
# VERIFICAÇÃO PADRÃO DE SEGURANÇA 

O Smart Contract Security Verification Standard é uma lista de verificação para padronizar a segurança de contratos inteligentes. Esta lista ajuda a evitar a maioria dos problemas de segurrança e vulnerabilidades conhecidos. A lista está disponibilizado em todas as fases do ciclo de desenvolvimento da contratação.


## Gravidade do risco

O padrão não inclui a gravidade dos riscos relacionados aos requisitos. A modelagem de ameaças e a análise de risco são partes importantes da avaliação de segurança. Cada aplicativo é única, assim como os agentes de ameaças, seus objetivos e o impacto de uma violação. 

A categoria da lista os requisitos relacionados à arquitetura, design e modelagem de ameaças dos contratos inteligentes. Os projetistas devem garantir que um contrato verificado satisfaça os seguintes requisitos de alto nível:. 

1\) Todos os contratos inteligentes relacionados são identificados e usados adequadamente, 

2\) Suposições de segurança específicas de contratos inteligentes são consideradas durante a fase de design  

3\) Os modelos de ameaças devem considerar todas as ameaças possíveis antes da implementação de tal contrato inteligente.

## Requisitos de verificação de segurança

Verifique se há uma política para rastrear novos bugs de segurança e atualizar as bibliotecas para a versão segura mais recente. Existe um componente que monitora a atividade do contrato por meio de eventos. O valor das criptomoedas mantidas em contrato é controlado e no nível mínimo aceitável. Se a função de fallback puder ser chamada por qualquer pessoa, ela será incluída na modelagem de ameaças.

## CONTROLE DE ACESSO

O controle de acesso é o processo de conceder ou negar solicitações específicas para obter e usar informações e serviços de processamento relacionados. Um contrato verificado deve satisfazer os seguintes requisitos de alto nível:. Os usuários e outros contratos estão associados a um conjunto bem definido de funções e privilégios, e o acesso é concedido apenas a usuários e contratos privilegiados.

Verifique se outros contratos só podem acessar funções ou dados para os quais possuem autorização específica. Os contratos devem ter uma permissão mínima ou nenhuma permissão até que o acesso aos novos recursos seja explicitamente concedido. Deve haver um mecanismo central para proteger o acesso a cada tipo de recurso protegido.

## DADOS DA CADEIA DE BLOCOS

Contratos inteligentes em blockchains públicos não possuem mecanismo embutido para armazenar dados secretos com segurança. É importante proteger os dados confidenciais da leitura por um agente não confiável e garantir que um contrato verificado satisfaça os seguintes requisitos de alto nível. Os dados armazenados em contratos inteligentes devem ser identificados e protegidos e não devem ser vulneráveis devido à deturpação de dados ou deturpação de dados.

Verifique se quaisquer dados salvos nos contratos não são considerados seguros ou privados (mesmo privados). 3.2 verifique se nenhum dado confidencial está armazenado no blockchain (senhas, dados pessoais, token etc.). 3.3 Verifique se a lista de dados confidenciais processados pelo contrato inteligente está identificada e se há uma política explícita de como o acesso a esses dados deve ser controlado.

# COMUNICAÇÕES

Verifique se as chamadas externas de e para outros contratos consideraram casos de abuso e estão autorizadas, e se as bibliotecas usadas são seguras e se são usadas bibliotecas de segurança de última geração. A categoria "V4" lista os requisitos relacionados às chamadas de função entre os contratos verificados e outros contratos fora do escopo do aplicativo.

Verifique se as bibliotecas que não fazem parte do aplicativo (mas o contrato inteligente depende para operar) estão identificadas. Não use a função de chamada e envio a menos que seja uma obrigação. Certifique-se de que os contratos e bibliotecas que chamam serviços de segurança externos tenham uma implementação centralizada.

## ARITMÉTICA

Um contrato verificado é um contrato inteligente que atende aos seguintes critérios de alto nível:. 1) Todas as operações matemáticas e valores extremos de variáveis são tratados de forma segura e previsível, e 2) Deve ser escrito em linguagens de programação C como C, C#, C++, Java, Python e Ruby.

Verifique se os valores e as operações matemáticas são resistentes a estouros de inteiros. Verifique se a desigualdade não estrita é usada para igualdade de equilíbrio. Verifique se os valores extremos do tipo de variável não alteram o fluxo lógico do contrato.

# MANIPULAÇÃO DE ENTRADA MALICIOSA

A V6 requer que um contrato verificado satisfaça os seguintes requisitos de alto nível antes que possa ser implementado:

Verifique se a entrada (parâmetros de função) é validada, a abordagem de validação positiva (lista branca) é usada. verifique se o comprimento do endereço que está sendo passado é determinado e validado pelo contrato inteligente.

## USO DE GÁS E LIMITAÇÕES

Certifique-se de que um contrato verificado satisfaça os seguintes requisitos de alto nível:. 

1\) O uso do gás é otimizado e perdas desnecessárias são evitadas. 

2\) Os contratos inteligentes possuem diferentes limitações que, se não forem levadas em consideração, podem causar diferentes vulnerabilidades.

3\) A implementação está de acordo com as limitações dos contratos inteligentes.

Verifique se o uso de gás no contrato inteligente está previsto, definido e tem limitações claras. Tanto a estrutura do código quanto a entrada maliciosa não devem causar exaustão de gases. Existe um mecanismo que protege o contrato de um ataque de repetição no caso de um hard-fork. Todas as funções de biblioteca que devem ser atualizadas não são internas.

## LOGÍCA DE NEGÓCIOS

Some of the components used in smart contracts should not be considered safe without verification. A verified contract satisfies the following high-level requirements:. The business logic flow is sequential and in order. Business limits are specified and enforced. Cryptocurrency and token business logic flows have considered abuse cases and maliciousactors.

Verifique se os fluxos de lógica de negócios dos contratos inteligentes procedem em uma ordem de etapas sequenciais e não é possível pular nenhuma parte ou fazê-lo em uma ordem diferente da projetada. 8.3 verificar se o contrato tem limites de negócios e os aplica corretamente. 8.4 verifique se ele não depende dos valores recuperados de contratos não confiáveis com várias chamadas da mesma função.

## NEGAÇÃO DE SERVIÇO

Um contrato verificado deve atender aos seguintes requisitos de alto nível antes de ser considerado válido para uso na rede Bitcoin:. 1. A lógica do contrato evita influenciar a disponibilidade do contrato.

https://media-exp1.licdn.com/dms/document/C4D1FAQFppuRcIQrjeQ/feedshare-document-pdf-analyzed/0/1648668033458?e=2147483647\&v=beta\&t=PK2EM0\_mfZvLx68FG\_7xXX5qiBDFLY8bwPH9Ws2E3WY

https://quillbot.com/summarize



