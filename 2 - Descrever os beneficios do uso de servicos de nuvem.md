# Microsoft Certifield: Microsoft Azure Fundamentals AZ-900

## [Módulo 2 - Descrever os benefícios do uso de serviços de nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/)

Este módulo apresenta os benefícios que a computação em nuvem pode oferecer a você ou à organização.

Visão geral

- [Introdução](#introdução)
- [Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem](#descrever-os-benefícios-da-alta-disponibilidade-e-da-escalabilidade-na-nuvem)
- [Descrever os benefícios da confiabilidade e previsibilidade na nuvem](#descrever-os-benefícios-da-confiabilidade-e-previsibilidade-na-nuvem)
- [Descrever os benefícios da segurança e da governança na nuvem](#descrever-os-benefícios-da-segurança-e-da-governança-na-nuvem)
- [Descrever os benefícios da capacidade de gerenciamento na nuvem](#descrever-os-benefícios-da-capacidade-de-gerenciamento-na-nuvem)
- [Verificação de conhecimentos](#verificação-de-conhecimentos)
- [Resumo](#resumo)

---

## [Introdução](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/1-introduction/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

Neste módulo, conheceremos alguns benefícios oferecidos pela computação em nuvem. Aprenderemos como a computação em nuvem pode nos ajudar a atender à demanda variável e ainda oferecer uma ótima experiência ao cliente. Também aprenderemos sobre segurança, governança e capacidade de gerenciamento geral na nuvem.

### Objetivos de aprendizagem

Depois de concluir este módulo, poderemos:

- Descrever os benefícios da alta disponibilidade.
- Descrever os benefícios da confiabilidade e da previsibilidade na nuvem.
- Descrever os benefícios da segurança e da governança na nuvem.
- Descrever os benefícios da capacidade de gerenciamento na nuvem.

---

## [Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/2-high-availability-scalability-cloud/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

Ao criar ou implantar um aplicativo de nuvem, duas das maiores considerações são o tempo de atividade (ou disponibilidade) e a capacidade de lidar com a demanda (ou a escala).

---

### 🔹 Alta disponibilidade

- **Definição**: capacidade de manter recursos e serviços disponíveis **mesmo diante de falhas ou interrupções**.  
- **Importância**: garante que aplicativos e serviços estejam acessíveis quando necessário.  
- **Azure**: oferece **SLAs (Service Level Agreements)** com garantias de tempo de atividade específicas por serviço.  
- **Benefício-chave**: confiança de que os serviços críticos terão **tempo de atividade elevado**.

[Este breve vídeo descreve os SLAs do Azure com mais detalhes](https://learn-video.azurefd.net/vod/player?id=638d4983-a571-47a3-a7be-382ed4a028ce&locale=pt-br&embedUrl=%2Ftraining%2Fmodules%2Fdescribe-benefits-use-cloud-services%2F2-high-availability-scalability-cloud)

---

### 🔹 Escalabilidade

- **Definição**: capacidade de **ajustar recursos** para atender à demanda variável.  
- **Benefícios**:
  - Adicionar recursos em picos de tráfego.  
  - Reduzir recursos quando a demanda cai → **otimização de custos**.  
  - Modelo baseado em consumo: paga-se apenas pelo uso real.  

---

### ⚖️ Tipos de Escala

- **Vertical (scale up/down)**  
  - Aumentar ou reduzir a capacidade de um recurso existente.  
  - Exemplo: adicionar mais CPU/RAM a uma máquina virtual.  
  - Útil para **melhorar desempenho de um recurso específico**.  

- **Horizontal (scale out/in)**  
  - Adicionar ou remover instâncias de recursos.  
  - Exemplo: criar mais máquinas virtuais ou contêineres.  
  - Útil para **distribuir carga entre múltiplos recursos**.  

---

### 📊 Comparativo rápido

| Conceito             | Característica principal | Exemplo prático |
|----------------------|--------------------------|-----------------|
| **Alta disponibilidade** | Garantia de tempo de atividade | SLA do Azure assegura % de uptime |
| **Escala vertical**      | Aumenta capacidade de um recurso | Mais CPU/RAM em uma VM |
| **Escala horizontal**    | Multiplica instâncias de recursos | Adicionar várias VMs para atender tráfego |

---

## 🎯 Pontos que podem cair no exame

- Conceito de **alta disponibilidade** e relação com **SLAs**.  
- Diferença entre **escala vertical** e **escala horizontal**.  
- Benefícios da escalabilidade: **ajuste dinâmico de recursos** e **redução de custos**.  
- Como a nuvem elimina a necessidade de superestimar ou subestimar capacidade.  

---

👉 Memorize **exemplos práticos** (CPU/RAM = vertical, adicionar VMs = horizontal) e associe **alta disponibilidade** diretamente aos **SLAs do Azure**. Isso ajuda a responder questões de múltipla escolha com mais segurança.

---

## [Descrever os benefícios da confiabilidade e previsibilidade na nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/3-reliability-predictability-cloud/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

Confiabilidade e previsibilidade são dois benefícios cruciais na nuvem que ajudam você a desenvolver soluções com confiança.

### 🔹 Confiabilidade

- **Definição**: capacidade de um sistema se recuperar de falhas e continuar funcionando.  
- **Pilar do Azure Well-Architected Framework**.  
- **Design descentralizado da nuvem**:
  - Recursos distribuídos em **múltiplas regiões globais**.  
  - Se uma região falhar, outras continuam operando.  
  - Em alguns casos, o ambiente de nuvem **migra automaticamente** para outra região sem intervenção manual.  
- **Benefício-chave**: infraestrutura resiliente e confiável, mesmo diante de eventos catastróficos.

---

### 🔹 Previsibilidade

- **Definição**: capacidade de avançar com confiança, prevendo **desempenho** e **custos**.  
- Também apoiada pelo **Azure Well-Architected Framework**.  

#### ⚡ Previsibilidade de desempenho

- Garantia de experiência consistente para os clientes.  
- Recursos que suportam:
  - **Dimensionamento automático** → adiciona ou remove recursos conforme demanda.  
  - **Balanceamento de carga** → distribui tráfego para evitar sobrecarga.  
  - **Alta disponibilidade** → mantém serviços acessíveis.  

#### 💰 Previsibilidade de custos

- Possibilidade de **monitorar uso em tempo real**.  
- **Análise de dados** para identificar padrões e planejar melhor.  
- Ajuste de recursos conforme necessidade → evita gastos desnecessários.  
- Ferramentas de apoio:
  - **TCO (Total Cost of Ownership)**.  
  - **Calculadora de Preços do Azure**.  

---

### 📊 Comparativo rápido

| Conceito              | Benefício principal | Exemplos |
|-----------------------|---------------------|----------|
| **Confiabilidade**    | Recuperação de falhas, resiliência | Recursos distribuídos em várias regiões |
| **Previsibilidade (desempenho)** | Experiência consistente | Autoescala, balanceamento de carga |
| **Previsibilidade (custos)** | Planejamento financeiro | Monitoramento em tempo real, TCO, Calculadora de Preços |

---

## 🎯 Pontos que podem cair no exame

- Definição de **confiabilidade** e relação com o **Azure Well-Architected Framework**.  
- Como a nuvem garante confiabilidade via **design descentralizado e escala global**.  
- Diferença entre **previsibilidade de desempenho** e **previsibilidade de custos**.  
- Ferramentas para prever custos: **TCO** e **Calculadora de Preços**.  

---

**O Azure Well-Architected Framework (WAF) é um conjunto de princípios e boas práticas que ajudam arquitetos e equipes técnicas a projetar, avaliar e otimizar cargas de trabalho na nuvem, garantindo que sejam seguras, confiáveis, eficientes e econômicas.**

---

## 📘 Resumo – Azure Well-Architected Framework (AZ-900)

### 🔹 O que é

- Estrutura criada pela Microsoft para orientar **design e operação de workloads no Azure**.  
- Baseada em **5 pilares fundamentais**, que representam os atributos de uma arquitetura bem construída.  
- Oferece ferramentas como o **Well-Architected Review** para avaliar e melhorar continuamente soluções na nuvem.

---

### 🏛 Os 5 Pilares do WAF

| Pilar                  | Objetivo principal | Exemplos de práticas |
|------------------------|-------------------|----------------------|
| **Confiabilidade**     | Garantir alta disponibilidade e recuperação de falhas | Redundância regional, planos de recuperação de desastre |
| **Segurança**          | Proteger dados, identidades e aplicações | Controle de acesso, criptografia, monitoramento de ameaças |
| **Otimização de custos** | Maximizar valor e reduzir desperdícios | Uso de reservas, monitoramento de consumo, ajuste de recursos |
| **Excelência operacional** | Automatizar, monitorar e manter operações eficientes | Observabilidade, DevOps, automação de processos |
| **Eficiência de desempenho** | Escalar e responder a demandas com agilidade | Autoescala, balanceamento de carga, testes de performance |

---

### 🔹 Benefícios

- **Orientação prática**: traduz princípios em decisões arquiteturais aplicáveis.  
- **Melhoria contínua**: permite revisar workloads periodicamente e ajustar conforme evolução do negócio.  
- **Base técnica sólida**: ajuda a alinhar soluções com objetivos de confiabilidade, segurança, custo e desempenho.  
- **Ferramentas de apoio**: Azure Advisor, Calculadora de Preços, TCO e Well-Architected Review.  

---

### 🎯 Pontos que podem cair no exame AZ-900

- Saber que o **WAF é baseado em 5 pilares**.  
- Reconhecer o papel de cada pilar (ex.: confiabilidade = resiliência, segurança = proteção de dados).  
- Entender que o WAF é usado para **avaliar e otimizar workloads** no Azure.  
- Relacionar ferramentas como **Well-Architected Review** e **Azure Advisor** ao framework.  

---

👉 Em resumo, o **Azure Well-Architected Framework** é o “manual técnico” da Microsoft para construir soluções de nuvem que sejam **seguras, escaláveis, econômicas e confiáveis**. Ele serve como guia para arquitetos e também como referência para o exame AZ-900.  

---

## 📊 Quadro comparativo – WAF x Benefícios da Nuvem

| Pilar do WAF              | Objetivo principal | Benefícios da nuvem relacionados | Exemplos práticos |
|---------------------------|-------------------|----------------------------------|------------------|
| **Confiabilidade**        | Recuperação de falhas e continuidade | Alta disponibilidade, resiliência | Recursos distribuídos em várias regiões; failover automático |
| **Segurança**             | Proteção de dados, identidades e workloads | Governança, conformidade, proteção contra ameaças | Azure Security Center, criptografia, controle de acesso |
| **Otimização de custos**  | Maximizar valor e reduzir desperdícios | Modelo baseado em consumo, previsibilidade de custos | Pay-as-you-go, reservas de instância, Calculadora de Preços |
| **Excelência operacional**| Operações eficientes e automatizadas | Agilidade, previsibilidade de desempenho | Monitoramento, DevOps, automação de tarefas |
| **Eficiência de desempenho** | Escalar e responder à demanda | Escalabilidade (vertical e horizontal), elasticidade | Autoescala, balanceamento de carga, otimização de VMs |

---

## 🎯 Pontos-chave para o exame

- O **WAF tem 5 pilares** → memorize a lista.  
- Cada pilar está conectado a um **benefício da nuvem**.  
- Exemplos práticos ajudam a diferenciar:  
  - **Confiabilidade** → disponibilidade global.  
  - **Segurança** → proteção e conformidade.  
  - **Custos** → modelo baseado em consumo.  
  - **Operacional** → automação e monitoramento.  
  - **Desempenho** → escalabilidade e elasticidade.  

---

## [Descrever os benefícios da segurança e da governança na nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/4-security-governance-cloud/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

**Segurança e Governança** são pilares fundamentais da nuvem e aparecem com frequência no exame **AZ-900**.

### 🔹 Governança

- **Definição**: conjunto de práticas para garantir que recursos de nuvem estejam em conformidade com **padrões corporativos e regulatórios**.  
- **Ferramentas e práticas**:
  - **Modelos de conjunto (templates)** → garantem que recursos sejam implantados conforme padrões definidos.  
  - **Atualizações centralizadas** → aplicar novos padrões em todos os recursos já implantados.  
  - **Auditoria baseada em nuvem** → identifica recursos fora de conformidade e sugere mitigação.  
  - **Automação de patches e atualizações** → mantém sistemas atualizados e seguros.  
- **Benefício-chave**: presença na nuvem **bem gerenciada, atualizada e em conformidade**.

---

### 🔹 Segurança

- **Infraestrutura como Serviço (IaaS)**  
  - Maior controle sobre segurança.  
  - Responsabilidade do cliente: gerenciar sistemas operacionais, software, patches e manutenção.  

- **Plataforma como Serviço (PaaS) / Software como Serviço (SaaS)**  
  - Patches e manutenção aplicados **automaticamente pelo provedor**.  
  - Menos responsabilidade direta do cliente.  

- **Proteção contra ataques**  
  - Provedores de nuvem oferecem defesa contra **DDoS (Distributed Denial of Service)**.  
  - Rede mais robusta e segura por padrão.  

---

### 📊 Comparativo rápido

| Modelo de serviço | Responsabilidade do cliente | Responsabilidade do provedor |
|-------------------|-----------------------------|-------------------------------|
| **IaaS**          | SO, software, patches, manutenção | Infraestrutura física |
| **PaaS**          | Aplicações e dados | SO, patches, manutenção |
| **SaaS**          | Uso da aplicação | Toda a infraestrutura e manutenção |

---

## 🎯 Pontos que podem cair no exame

- Diferença entre **IaaS, PaaS e SaaS** em termos de responsabilidade de segurança.  
- Função da **governança**: conformidade, auditoria e aplicação de padrões.  
- Benefícios da **automação de patches e atualizações**.  
- Papel da nuvem na **proteção contra ataques DDoS**.  
- Importância de estabelecer governança desde o início para manter ambiente seguro e bem gerenciado.  

---

## [Descrever os benefícios da capacidade de gerenciamento na nuvem](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/5-manageability-cloud/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que aprederemos nesta série e ambos trazem excelentes benefícios.

### 🔹 Gerenciamento **da nuvem**

Focado em **administrar os recursos implantados**.  
Principais benefícios:

- **Escalabilidade automática** → ajusta recursos conforme necessidade.  
- **Implantação via modelos pré-configurados** → elimina configuração manual, garante consistência.  
- **Monitoramento de integridade** → substitui automaticamente recursos com falha.  
- **Alertas automáticos** → baseados em métricas configuradas, fornecem visibilidade em tempo real.  

👉 Benefício-chave: **eficiência operacional** e **redução de erros humanos**.

---

### 🔹 Gerenciamento **na nuvem**

Focado em **como você interage e administra o ambiente de nuvem**.  
Opções de gerenciamento:

- **Portal da Web (Azure Portal)** → interface gráfica, intuitiva.  
- **CLI (Command-Line Interface)** → comandos diretos, ideal para automação rápida.  
- **APIs** → integração com sistemas e aplicações.  
- **PowerShell** → scripts avançados para automação e administração.  

👉 Benefício-chave: **flexibilidade de gerenciamento**, adaptando-se ao perfil da equipe (visual, script, integração).

---

### 📊 Comparativo rápido

| Tipo de gerenciamento | Foco | Exemplos de benefícios |
|-----------------------|------|------------------------|
| **Da nuvem**          | Recursos implantados | Autoescala, monitoramento, alertas |
| **Na nuvem**          | Forma de administrar | Portal, CLI, APIs, PowerShell |

---

## 🎯 Pontos que podem cair no exame
- Diferença entre **gerenciamento da nuvem** (recursos) e **gerenciamento na nuvem** (formas de administrar).  
- Benefícios da automação: **autoescala, monitoramento, alertas**.  
- Ferramentas de gerenciamento: **Azure Portal, CLI, APIs, PowerShell**.  

---

## [Verificação de conhecimentos](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/6-knowledge-check/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

![img-AvaliacaoModulo2.png](./images/AvaliacaoModulo2.png)

---

## [Resumo](https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/7-summary/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.microsoft-azure-fundamentals-describe-cloud-concepts)

Neste módulo, conhecemos alguns dos benefícios de operar na nuvem. Aprendemos sobre alta disponibilidade e confiabilidade e como elas funcionam para manter os aplicativos em execução. Também aprendemos como a nuvem pode oferecer um ambiente mais seguro. Por fim, aprendemos que a nuvem oferece um ambiente altamente gerenciável para os recursos.

### Objetivos de aprendizagem

Agora você deve estar apto a:

- Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem.
- Descrever os benefícios da confiabilidade e da previsibilidade na nuvem.
- Descrever os benefícios da segurança e da governança na nuvem.
- Descrever os benefícios da capacidade de gerenciamento na nuvem.

### Recursos adicionais

Os recursos a seguir oferecem mais informações sobre os tópicos neste módulo ou relacionados a ele.

[Criar ótimas soluções com o Microsoft Azure Well-Architected Framework](https://learn.microsoft.com/pt-br/learn/paths/azure-well-architected-framework/) é um curso do Microsoft Learn que apresenta o Microsoft Azure Well-Architected Framework.

---
