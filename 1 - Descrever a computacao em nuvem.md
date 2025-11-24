# Microsoft Certifield: Microsoft Azure Fundamentals AZ-900

## [Módulo 1 - Descrever a computação em nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/)

Este módulo apresenta a computação em nuvem. Ele aborda coisas como conceitos de nuvem, modelos de implantação e compreensão da responsabilidade compartilhada na nuvem.

Visão geral

- [Introdução aos conceitos básicos do Microsoft Azure](#introdução-aos-conceitos-básicos-do-microsoft-azure)
- [Introdução à computação em nuvem](#introdução-à-computação-em-nuvem)
- [O que é computação em nuvem](#o-que-é-computação-em-nuvem)
- [Descrever o modelo de responsabilidade compartilhada](#descrever-o-modelo-de-responsabilidade-compatilhada)
- [Definir modelos de nuvem](#definir-modelos-de-nuvem)
- [Descrever o modelo baseado em consumo](#descrever-o-modelo-de-responsabilidade-compatilhada)
- [Veficiação de conhecimentos](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/7-knowledge-check)
- [Resumo](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/8-summary)

## [Introdução aos conceitos básicos do Microsoft Azure](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/1-introduction-microsoft-azure-fundamentals)

O Microsoft Azure é uma plataforma de computação em nuvem com um conjunto de serviços em constante expansão para ajudar você a criar soluções para atingir suas metas de negócios. Os serviços do Azure dão suporte a tudo, do simples ao complexo.

O Azure fornece uma infinidade de serviços baseados em nuvem, como:

- Armazenamento remoto
- Hospedagem de banco de dados
- Gerenciamento de contas centralizado
- IA (inteligêcnia artificial)
- Serviços focados em IoT (Internet das Coisas)

## Por que devo estudar os Conceitos Básicos do Azure?

A série de roteiros de aprendizagem dos Conceitos Básicos do Azure pode ajudar você a se preparar para o Exame AZ-900. Esse exame inclui três áreas de domínio de conhecimento:

| Área de domínio do AZ-900 | Weight |
| ----------- | ----------- |
| Descrever os conceitos da nuvem | 25 a 30% |
| Descrever a arquitetura e os serviços do Azure | 35 a 40% |
| Descrever o gerenciamento e a governança do Azure | 30 a 35% |

Cada área de domínio é mapeada para um roteiro de aprendizagem nos Conceitos Básicos do Azure. As porcentagens mostradas indicam o peso relativo de cada área no exame. Quanto maior a porcentagem, mais perguntas haverá nessa parte do exame.

Este treinamento ajuda você a desenvolver uma ampla compreensão do Azure.

## [Introdução à computação em nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/2-introduction-cloud-compute)

Neste módulo, você conhecerá os conceitos gerais de nuvem. Você começará com uma introdução à nuvem em geral. Em seguida, você se aprofundará em conceitos como responsabilidade compartilhada, diferentes modelos de nuvem e explorará o método de preço exclusivo da nuvem.

## [O que é computação em nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/3-what-cloud-compute)

A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como:

- Máquinas virtuais
- Armazenamento
- Banco de Dados
- Rede
- IoT (Internet das Coisas)
- ML (machine learning)
- IA (inteligência artificial)

Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua estrutura de TI, não precisará esperar para construir um novo datacenter, você pode usar a nuvem para expandir rapidamente seu volume de TI

## [Descrever o modelo de responsabilidade compatilhada](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/4-describe-shared-responsibility-model)

Comece com um datacenter corporativo tradicional.

### A empresa é responsável por

- Manter o espaço físico
- Garantir a segurança
- Manter ou substituir os servidores se algo acontecer

### O departamento de TI é responsável por

- Manter toda a infraestrutura e software necessário
- Manter todos os sistemas corrigidos e na versão correta

Com o modelo de responsabilidade compartilhada, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor.

### Provedor de nuvem é responsável por

- Segurança física
- Energia
- Resfriamento
- Conectividade de rede

### O consumidor é responsável por

- Pelos dados e informações armazenadas na nuvem
- Segurança de acesso

A responsabilidade depende da situação. Se você estiver usando um Banco de Dados SQL na nuvem, o provedor de nuvem será responsável pela manutenção do banco de dados real. No entanto, você ainda será responsável pelos dados que são ingeridos no banco de dados. Já se você implantasse uma máquina virtual e instalasse um banco de dados SQL nela, seria responsável pelos patches e atualizações do banco de dados, além da manutenção dos dados e das informações armazenados no banco de dados.

Com um datacenter local, você é responsável por tudo. Com a computação em nuvem, essas responsabilidades mudam.

Modelo de responsabilidade compartilhada está fortemente vinculado aos tipos de serviço de nuvem:

- IaaS = Infraestrutura como serviço
  - Coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade
- PaaS = Plataforma como serviço
  - Meio do caminho entre IaaS e SaaS, distribui uniformemente a responsabilidade entre provedor de nuvem e consumidor
- SaaS = Software como serviço
  - Coloca a maior parte da responsabilidade no provedor de nuvem

O diagrama a seguir ilustra o Modelo de Responsabilidades

![img-ModeloDeResponsabilidade.svg](./images/ModeloDeResponsabilidade.svg)

Ao usar um provedor de nuvem, **você será responsável por**:

- Informações e dados armazenados na nuvem
- Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
- Contas de identidade das pessoas, serviços e dispositivos em sua organização

O provedor de nuvem **é sempre responsável por**:

- Datacenter físico
- Rede física
- Hosts físicos

Seu modelo de serviço derterminará a responsabilidade por coisas como:

- Sistemas operacionais
- Controles de rede
- Aplicativos
- Identidade e infraestrutura

## [Definir modelos de nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/5-define-cloud-models)

O que são modelos de nuvem? _**Os modelos de nuvem definem o tipo de implantação de rescursos de nuvem.**_ Os três principais modelos de nuvem são: privado, público e híbrido.

### Nuvem privada

Parei aqui: https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/5-define-cloud-models