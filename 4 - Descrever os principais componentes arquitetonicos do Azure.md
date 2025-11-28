# Microsoft Certifield: Microsoft Azure Fundamentals AZ-900

[Módulo 1 - Descrever os principais componentes arquitetônicos do Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/)

Este módulo explica os componentes básicos de infraestrutura do Microsoft Azure. Você aprenderá sobre a infraestrutura física, como os recursos são gerenciados e terá a oportunidade de criar um recurso do Azure.

Visão geral

- [Introdução](#introdução)
- [O que é o Microsoft Azure](#o-que-é-o-microsoft-azure)
- [Introdução a contas do Azure](#introdução-a-contas-do-azure)
- [Exercício - Explorar a interação com o Azure](#exercício---explorar-a-interação-com-o-azure)
- [Descrever a infraestrutura física do Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/5-describe-azure-physical-infrastructure/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)
- [Descrever a infraestrutura de gerenciamento do Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/6-describe-azure-management-infrastructure/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)
- [Exercício - Criar uma conta do Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/7-exercise-create-azure-resource/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)
- [Avaliação do módulo](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/8-knowledge-check/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)
- [Resumo](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/9-summary/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)

---

## [Introdução](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/1-introduction/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)

Neste módulo, você será apresentado aos principais componentes arquitetônicos do Azure. Você aprenderá sobre a organização física do Azure: datacenters, zonas de disponibilidade e regiões; e você aprenderá sobre a estrutura organizacional do Azure: recursos e grupos de recursos, assinaturas e grupos de gerenciamento.

### Objetivos de aprendizagem

Depois de concluir este módulo, você poderá:

- Descrever regiões do Azure, pares de regiões e regiões soberanas.
- Descrever zonas de disponibilidade.
- Descrever os datacenters do Azure.
- Descreva os recursos do Azure e os Grupos de Recursos.
- Descreva assinaturas.
- Descrever os grupos de gerenciamento.
- Descreva a hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento.

---

## [O que é o Microsoft Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/2-what-microsoft-azure/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)

[Este vídeo apresenta o Microsoft Azure](https://learn-video.azurefd.net/vod/player?id=c27bf1d6-d1b6-410e-a271-e7ae999f2434&locale=pt-br&embedUrl=%2Ftraining%2Fmodules%2Fdescribe-core-architectural-components-of-azure%2F2-what-microsoft-azure)

### 🔹 Definição

- **Microsoft Azure** = conjunto em constante expansão de serviços de nuvem.  
- Permite **criar, gerenciar e implantar aplicativos** em uma **rede global massiva**.  
- Oferece liberdade para usar suas **ferramentas e frameworks favoritos**.  

👉 Benefício-chave: **plataforma flexível e global para inovação e operação de soluções de TI**.

---

### 🔹 O que o Azure oferece

- **Inovação ilimitada** → criar soluções inteligentes com tecnologia avançada.  
- **Integração perfeita** → gerenciar infraestrutura, dados, análises e IA em uma plataforma única.  
- **Confiança** → segurança e responsabilidade de um provedor confiável.  
- **Serviços líderes de mercado** → IA, machine learning, armazenamento dinâmico, realidade misturada, bots inteligentes.  

---

### 🔹 O que posso fazer com o Azure

- Mais de **100 serviços disponíveis**.  
- Possibilidades:
  - Executar aplicativos existentes em **máquinas virtuais (VMs)**.  
  - Migrar workloads locais para a nuvem (**lift-and-shift**).  
  - Explorar novos paradigmas de software (IA, ML, bots, realidade mista).  
  - Usar **armazenamento escalável** para grandes volumes de dados.  

👉 A nuvem não é apenas “um lugar diferente para rodar VMs” → ela habilita soluções **inviáveis sem a escala e potência da nuvem**.

---

### 📊 Exemplos de serviços do Azure

- **Infraestrutura**: Máquinas Virtuais, Redes Virtuais.  
- **Dados e Armazenamento**: Azure Blob Storage, Azure SQL Database.  
- **IA e ML**: Azure Cognitive Services, Azure Machine Learning.  
- **Aplicações modernas**: Bots, realidade misturada, aplicativos inteligentes.  

---

## 🎯 Pontos que podem cair no exame

- Definição de **Azure** como plataforma de nuvem global e expansível.  
- Benefícios principais: **inovação, integração, confiança**.  
- Exemplos de serviços: **VMs, IA/ML, armazenamento dinâmico**.  
- Entender que a nuvem é mais do que apenas rodar VMs → habilita **novos cenários**.  

---

## [Introdução a contas do Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/3-get-started-azure-accounts/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)

### 🔹 Conta e Assinatura

- Para usar o Azure, é necessário criar uma **conta do Azure**.  
- Ao criar a conta, uma **assinatura** é gerada automaticamente.  
- É possível criar **assinaturas adicionais** dentro da mesma conta (ex.: uma conta corporativa com assinaturas separadas para desenvolvimento, marketing e vendas).  
- Dentro de cada assinatura, você cria e gerencia **recursos do Azure**.  

👉 Escopo hierárquico: **Conta → Assinatura → Recursos**.

![img-EscopoHierarquicoContaAssinatura.svg](./images/account-scope-levels.png)

---

### 🔹 Tipos de contas

- **Conta gratuita do Azure**:
  - Produtos populares gratuitos por **12 meses**.  
  - **Crédito inicial** para usar nos primeiros 30 dias.  
  - Mais de **25 produtos sempre gratuitos**.  
  - Requisitos: número de telefone, cartão de crédito (apenas para verificação), conta Microsoft ou GitHub.  
  - Não há cobrança até atualizar para assinatura paga.  

- **Conta de estudante gratuita do Azure**:
  - Produtos gratuitos por **12 meses**.  
  - Crédito de **US$ 100** válido por 12 meses.  
  - Ferramentas gratuitas para desenvolvedores.  
  - Não exige cartão de crédito.  

---

### 🔹 Como adquirir

- Diretamente pelo site do Azure.  
- Por meio de representante da Microsoft.  
- Via **parceiros CSP (Cloud Solution Provider)** → oferecem soluções gerenciadas completas.  

[Este vídeo apresenta o processo de criação de uma conta no Azure](https://learn.microsoft.com/_themes/docs.theme/master/en-us/_themes/global/video-embed-one-stream.html?id=ac3ad75e-6841-4b66-b3b2-19c85b0e36c3&locale=pt-br&embedUrl=%2Ftraining%2Fmodules%2Fdescribe-core-architectural-components-of-azure%2F3-get-started-azure-accounts)

---

### 🔹 Exercícios BYOS (Bring Your Own Subscription)

- Muitos módulos de aprendizagem exigem que você tenha **sua própria assinatura** para praticar.  
- Cada exercício inclui uma **etapa de limpeza** → importante para evitar custos inesperados.  

---

### 📊 Comparativo rápido

| Tipo de conta | Benefícios | Requisitos |
|---------------|------------|------------|
| **Gratuita**  | 12 meses de produtos populares, crédito inicial de 30 dias, 25 produtos sempre gratuitos | Telefone, cartão de crédito (verificação), conta Microsoft/GitHub |
| **Estudante** | 12 meses de produtos, crédito de US$ 100, ferramentas de dev | Telefone, conta Microsoft/GitHub (sem cartão de crédito) |

---

## 🎯 Pontos que podem cair no exame

- Diferença entre **conta** e **assinatura**.  
- Benefícios da **conta gratuita** e da **conta de estudante gratuita**.  
- Escopo hierárquico: conta → assinatura → recursos.  
- Importância da **etapa de limpeza** nos exercícios BYOS.  
- Como adquirir uma conta: site, representante ou parceiro CSP.  

---

## [Exercício - Explorar a interação com o Azure](https://learn.microsoft.com/pt-br/training/modules/describe-core-architectural-components-of-azure/4-exercise-explore-learn-sandbox/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)

Neste exercício, você explora maneiras de interagir com o Microsoft Azure. Você pode interagir com o Azure de diferentes maneiras, incluindo por meio do portal da Web ou usando a CLI (interface de linha de comando) do Azure com comandos do PowerShell ou Bash.

### Acessar o Portal do Azure

### 🔹 Formas de interação

1. **Portal do Azure (GUI)**  
   - Interface gráfica acessada em [https://portal.azure.com](https://portal.azure.com).  
   - Permite navegar por serviços, gerenciar assinaturas, contas e configurações.  
   - Ideal para iniciantes ou administração visual.  

2. **CLI (Command-Line Interface)**  
   - Acessada pelo **Cloud Shell** dentro do portal.  
   - Suporte a **PowerShell** e **Bash**.  
   - Alternância rápida entre modos (`pwsh` ↔ `bash`).  
   - Comandos do Azure começam com `az`.  

3. **Modo interativo da CLI**  
   - Executado com `az interactive`.  
   - Funciona como um **IDE simplificado**: preenchimento automático, descrições de comando, exemplos.  
   - Não exige prefixo `az` nos comandos.  
   - Útil para quem não domina PowerShell ou Bash.  

---

### 🔹 Exemplos práticos

- **PowerShell**  
  - `Get-date` → retorna data/hora atuais.  
  - `az version` → verifica versão da CLI.  

- **Bash**  
  - `date` → retorna data/hora atuais.  
  - `az upgrade` → atualiza CLI.  

- **Modo interativo**  
  - `version` ou `upgrade` → executados sem `az`.  
  - `exit` → sair do modo interativo.  

---

### 📊 Comparativo rápido

| Método de interação | Características | Exemplos |
|---------------------|-----------------|----------|
| **Portal (GUI)**    | Interface gráfica, fácil de usar | Gerenciar recursos via navegador |
| **CLI PowerShell**  | Linha de comando, comandos `az` + PowerShell | `Get-date`, `az version` |
| **CLI Bash**        | Linha de comando, comandos `az` + Bash | `date`, `az upgrade` |
| **CLI Interativo**  | Preenchimento automático, estilo IDE | `version`, `upgrade`, `exit` |

---

## 🎯 Pontos que podem cair no exame

- Diferença entre **Portal do Azure** e **CLI**.  
- Alternância entre **PowerShell** e **Bash** no Cloud Shell.  
- Função do **modo interativo da CLI**.  
- Exemplos de comandos básicos (`Get-date`, `date`, `az version`, `az upgrade`).  

---
