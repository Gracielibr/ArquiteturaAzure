# Componentes de Arquiteturas no Azure

Principais serviços do Azure para construção de arquiteturas escaláveis, seguras e de alta disponibilidade:

## 1. **Azure Virtual Machines (VMs)**
   - Infraestrutura como Serviço (IaaS) para implantação de máquinas virtuais Windows/Linux
   - Ideal para migrações "lift-and-shift" e cargas de trabalho personalizadas
   - Escalabilidade vertical (tamanho da VM) e horizontal (conjunto de escalas)

## 2. **Azure App Service**
   - Plataforma como Serviço (PaaS) para hospedagem de aplicações web, APIs e mobile backends
   - Suporte para .NET, Java, Node.js, Python e PHP
   - Recursos de autoescalonamento e deploy contínuo

## 3. **Azure Kubernetes Service (AKS)**
   - Serviço gerenciado para orquestração de contêineres usando Kubernetes
   - Facilita o deploy, gerenciamento e escalonamento de aplicações conteinerizadas
   - Integração com Azure DevOps e monitoramento via Azure Monitor

## 4. **Azure Cosmos DB**
   - Banco de dados NoSQL multimodelo distribuído globalmente
   - Baixa latência garantida com SLAs de até 99,999% de disponibilidade
   - Suporte a APIs como SQL, MongoDB, Cassandra e Gremlin

## 5. **Azure Functions**
   - Plataforma serverless para execução de código orientado a eventos
   - Cobrança baseada no consumo (apenas quando executado)
   - Integração com diversos serviços Azure e HTTP triggers

## Casos de Uso Comuns
- **Aplicações híbridas**: VMs + App Service
- **Microserviços**: AKS + Azure Functions
- **Aplicações globais**: Cosmos DB (distribuição multi-região)
- **Processamento de eventos**: Functions + Event Grid
