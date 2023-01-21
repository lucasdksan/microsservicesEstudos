# microsservicesEstudos

Estudos relacionados aos micros serviços

## O que são microsserviços?

Microsserviços são uma abordagem arquitetônica e organizacional do desenvolvimento de software na qual consiste em pequenos serviços independentes que se comunicam usando APIs bem definidas. Esses serviços pertencem a pequenas equipes autossuficientes. Resumindo, referem a um software dividido em pequenos softwares (micro-software) que têm responsabilidades reduzidas e são independentes.

As arquiteturas de microsserviços facilitam a escalabilidade e agilizam o desenvolvimento da aplicativos, habilitando a inovação e acelerando o tempo de introdução de novos recursos no mercado.

## Diferenças entre as arquiteturas monolítica e de microsserviços

* Arquiteturas Monolíticas:

O grande conceito por trás da arquitetura monolítica é acoplar todas as funcionalidades de um sistema em um só núcleo. Isso significa que se um processo do aplicativo apresentar um pico de demanda, toda a arquitetura deverá ser escalada. A complexidade da adição ou do aprimoramento de recursos de aplicativos monolíticos aumenta com o crescimento da base de código. Essa complexidade limita a experimentação e dificulta a implementação de novas ideias.

* Arquiteturas Microsservices: 

Um aplicativo é criado como componentes independentes que executam cada processo do aplicativo como um serviço. Esses serviços se comunicam por meio de uma interface bem definida usando APIs leves. Como são executados de forma independente, cada serviço pode ser atualizado, implementado e escalado para atender a demanda de funções específicas de um aplicativo.

## Características dos microsserviços

* Autônomos: 

Cada serviço do componente de uma arquitetura de microsserviço pode ser desenvolvido, implantado, operado e escalado sem afetar o funcionamento de outros serviços. Os serviços não precisam compartilhar nenhum código ou implementação com os outros serviços. Todas as comunicações entre componentes individuais ocorrem por meio de APIs bem definidas.

* Especializados:

Cada serviço é projetado para ter um conjunto de recursos e é dedicado à solução de um problema específico. Se os desenvolvedores acrescentarem mais código a um serviço ao longo do tempo, aumentando sua complexidade, ele poderá ser dividido em serviços menores.

* Heterogeneidade de tecnologias:

Uma outra grande vantagem de se trabalhar com microsservices é a heterogeneidade de tecnologias. Isso quer dizer que é possível utilizar tecnologias distintas ao mesmo tempo. Cada serviço pode ser escrito em uma tecnologia diferente, desde que eles consigam se comunicar entre si (se for um projeto web, geralmente esta comunicação é feita via protocolo HTTP através de APIs).

## Benefícios dos Microsserviços

* Agilidade:

Os microsserviços promovem uma organização de equipes pequenas e independetes que são proprietárias de seus serviços. As equipes atuam dentro de um contexto pequeno e claramente compreendido e têm autonomia para trabalhar de forma mais independete e rápida. O resultado é a aceleração dos ciclos de desenvolvimento. Você obtém benefícios significativos do thoroughput agregado da organização.

* Escabilidade Flexível:

Os microsserviços permitem que cada serviço seja escalado de forma independente para atender à demanda do recurso de aplicativo oferecido por esse serviço. Isso permite que as equipes dimensionem corretamente as necessidades de infraestrutura, meçam com precisão o custo de um recurso e mantenham a disponibilidade quando um serviço experimenta um pico de demanda.

* Fácil implantação:

Os microsserviços permitem a integração e a entrega contínuas, o que facilita o teste de novas ideias e sua reversão caso algo não funcione corretamente. O baixo custo de falha permite a experimentação, facilita a atualização do código e acelera o tempo de introdução de novos recursos no mercado.

* Código reutilizável

A divisão do software em módulos pequenos e vem definidos permite que as equipes usem funções para várias finalidades. Um serviço criado para uma determinada função pode ser usado como componente básico para outro recurso. Isso permite que os aplicativos sejam reutilizados, pois os desenvolvedores podem criar recursos sem precisar escrever código.

* Resiliência

A independência do serviço aumenta a resistência a falhas do aplicativo. Em uma arquitetura monolítica, a falha de um único componente poderá causar a falha de todo o aplicativo. Com os microsserviços, os aplicativos lidam dom a falha total do serviço degradado a funcionalidade, sem interromper todo o aplicativo.

*** Dominíos/Áreas de atuação