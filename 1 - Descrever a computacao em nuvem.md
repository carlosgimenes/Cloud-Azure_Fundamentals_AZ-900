# Microsoft Certifield: Microsoft Azure Fundamentals AZ-900

## [Módulo 1 - Descrever a computação em nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/)

Este módulo apresenta a computação em nuvem. Ele aborda coisas como conceitos de nuvem, modelos de implantação e compreensão da responsabilidade compartilhada na nuvem.

Visão geral

- [Introdução aos conceitos básicos do Microsoft Azure](#introdução-aos-conceitos-básicos-do-microsoft-azure)
- [Introdução à computação em nuvem](#introdução-à-computação-em-nuvem)
- [O que é computação em nuvem](#o-que-é-computação-em-nuvem)
- [Descrever o modelo de responsabilidade compartilhada](#descrever-o-modelo-de-responsabilidade-compatilhada)
- [Definir modelos de nuvem](#definir-modelos-de-nuvem)
- [Descrever o modelo baseado em consumo](#descrever-o-modelo-baseado-em-consumo)
- [Veficiação de conhecimentos](#veficiação-de-conhecimentos)
- [Resumo](#resumo)

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

Você já deve ter ouvido falar do modelo de responsabilidade compartilhada, mas talvez não entenda o que isso significa ou como ele afeta a computação em nuvem. Comece com um datacenter corporativo tradicional.

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

### ☁️ Nuvem Privada

- Usada por **uma única organização**.
- Hospedada em datacenter **local** ou **dedicado externo**.
- **Vantagens**: maior controle sobre recursos e segurança.
- **Desvantagens**: custos mais altos, responsabilidade pela manutenção e atualização de hardware.

---

### ☁️ Nuvem Pública

- Criada e mantida por **provedor de terceiros** (ex.: Microsoft Azure).
- Recursos disponíveis para **qualquer cliente**.
- **Vantagens**:
  - Sem despesas de capital para escalar.
  - Provisionamento/desprovisionamento rápido.
  - Pagamento apenas pelo uso.
- **Desvantagens**: menos controle sobre segurança e recursos.

---

### ☁️ Nuvem Híbrida

- Combina **pública + privada** em ambiente interconectado.
- **Vantagens**:
  - Flexibilidade para escalar (burst para nuvem pública).
  - Escolha de onde executar aplicativos (privado ou público).
  - Controle adicional sobre segurança, conformidade e requisitos legais.

---

### 📊 Comparativo Rápido

| Modelo        | Pontos Fortes | Pontos Fracos |
|---------------|---------------|---------------|
| **Pública**   | Escalabilidade rápida, custo sob demanda | Menos controle de segurança |
| **Privada**   | Controle total, dados isolados | Alto custo, manutenção própria |
| **Híbrida**   | Maior flexibilidade, escolha de execução | Complexidade de gerenciamento |

---

### 🌐 Cenário de Múltiplas Nuvens

- Uso de **vários provedores de nuvem pública**.
- Pode ocorrer por estratégia ou migração.
- Desafio: gerenciar **recursos e segurança em diferentes ambientes**.

---

### 🛠️ Tecnologias Relacionadas

- **Azure Arc**: gerenciamento unificado de ambientes (público, privado, híbrido, múltiplas nuvens).
- **Solução VMware no Azure**: permite rodar cargas VMware no Azure com integração e escalabilidade.

---

## 🎯 Pontos que podem cair no exame

- Diferença entre **nuvem pública, privada e híbrida**.  
- **Vantagens e desvantagens** de cada modelo.  
- Conceito de **múltiplas nuvens**.  
- Função do **Azure Arc**.  
- Uso da **Solução VMware no Azure** para migração.  

---

## [Descrever o modelo baseado em consumo](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/6-describe-consumption-based-model)

Ao comparar modelos de infraestrutura de TI, há dois tipos de despesas a serem consideradas. CapEx (despesas de capital) e OpEx (despesas operacionais).

### 🔹 CapEx vs. OpEx

- **CapEx (Capital Expenditure)**  
  - Despesa inicial única para aquisição de ativos tangíveis.  
  - Exemplos: construção de datacenter, compra de veículos, obras físicas.  
  - Exige investimento alto antecipado e planejamento de capacidade futura.  

- **OpEx (Operational Expenditure)**  
  - Custos recorrentes ao longo do tempo, relacionados a serviços/produtos.  
  - Exemplos: aluguel de espaço, leasing de veículos, assinatura de serviços de nuvem.  
  - Mais flexível, ajusta-se à demanda real.  

---

### ☁️ Modelo baseado em consumo (Cloud)

- A nuvem é **OpEx**: paga-se apenas pelo uso dos recursos.  
- Não há custos com infraestrutura física, energia, segurança ou manutenção de datacenter.  
- Se não usar recursos, não há cobrança.  

---

### ✅ Benefícios

- **Sem custos prévios** (não há investimento inicial em hardware).  
- **Elasticidade**: pagar por mais recursos quando necessário.  
- **Eficiência**: parar de pagar por recursos não usados.  
- **Escalabilidade rápida**: adicionar/remover máquinas virtuais conforme demanda.  
- **Previsibilidade de custos**: planejar e gerenciar gastos operacionais com mais precisão.  

---

### ⚖️ Comparação com datacenter tradicional

- **Datacenter tradicional**: exige estimar capacidade futura.  
  - Superestimar → desperdício de capital.  
  - Subestimar → falta de capacidade, queda de desempenho, demora para expandir.  
- **Nuvem**: elimina a necessidade de estimar com precisão.  
  - Recursos podem ser ajustados dinamicamente.  
  - Pagamento apenas pelo uso real.  

---

### 📊 Modelo de preços da nuvem

- **Pay-as-you-go (pague conforme o uso)**.  
- Permite:  
  - Planejar custos operacionais.  
  - Executar infraestrutura com eficiência.  
  - Escalar operações conforme necessidades do negócio.  
- Analogia: **aluguel de capacidade computacional e armazenamento** em vez de compra definitiva.  

---

## 🎯 Pontos que podem cair no exame

- Diferença entre **CapEx e OpEx**.  
- Por que a nuvem é considerada **OpEx**.  
- Benefícios do **modelo baseado em consumo**.  
- Diferença entre **datacenter tradicional** e **nuvem** em termos de custos e escalabilidade.  
- Conceito de **pay-as-you-go**.  

---

## [Veficiação de conhecimentos](https://learn.microsoft.com/pt-br/training/modules/describe-cloud-compute/7-knowledge-check)

![img-AvaliacaoModulo1.png](./images/AvaliacaoModulo1.png)

---

## Resumo

Neste módulo, você aprendeu os conceitos gerais de nuvem. No início, você começou com coisas como simplesmente entender o que é computação em nuvem. Você também entendeu o modelo de responsabilidade compartilhada e como você e o provedor de nuvem compartilham a responsabilidade de manter a segurança das informações na nuvem. Você abordou brevemente as diferenças entre os modelos de nuvem (pública, privada, híbrida e multinuvem). Depois, concluímos com uma unidade explicando como a nuvem muda os gastos de TI de despesa de capital para despesa operacional.

### Objetivos de aprendizagem

Agora você deve estar apto a:

- Definir a computação em nuvem.
- Descrever o modelo de responsabilidade compartilhada.
- Definir modelos de nuvem, incluindo público, privado e híbrido.
- Identificar os casos de uso apropriados para cada modelo de nuvem.
- Descrever o modelo baseado no consumo.
- Comparar os modelos de preços de nuvem.

---

### Recursos adicionais

Os recursos a seguir oferecem mais informações sobre os tópicos neste módulo ou relacionados a ele.

- [Modelo de responsabilidade compartilhada](https://learn.microsoft.com/pt-br/azure/security/fundamentals/shared-responsibility) o modelo de responsabilidade compartilhada é a divisão de responsabilidades pela nuvem entre você e seu provedor de nuvem.
- [Introdução à Solução VMware no Azure](https://learn.microsoft.com/pt-br/learn/modules/intro-azure-vmware-solution/) é um curso do Microsoft Learn que aprofunda o conhecimento sobre a Solução VMware no Azure.
- [Introdução aos serviços de nuvem híbrida do Azure](https://learn.microsoft.com/pt-br/learn/modules/intro-to-azure-hybrid-services/) é um curso do Microsoft Learn que explica a nuvem híbrida com mais detalhes.

---
