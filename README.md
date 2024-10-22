
# Dio. Bootcamp - Microsoft Azure Essentials

Bootcamp da plataforma [Dio](https://www.dio.me/ "Dio")

## Azure

Nuvem pública com diversos servicos cloud. Mantida pela Microsoft. 

A azure oferece um plano trial que oferece 30 dias trial além de diversos serviços que são gratuitos permanementes. é importante visitar a plataforma para conchecer mais sobre contratação e que serviços são ofertados gratuitamente.

[Free Services Azure](https://azure.microsoft.com/pt-br/pricing/free-services "https://azure.microsoft.com/pt-br/pricing/free-services")

### Nuvem Pública
Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas.

O [Azure](https://azure.microsoft.com/pt-br "azure"), o AWS e O Google Cloud são exemplos de núvem pública. Pois são provedores de serviços nuvem para qualquer empresa que precisa de uma infraestrutura cloud.

### Serviços azure
Os [serviços ofertados pela azure](https://azure.microsoft.com/pt-br/products/ "serviços azures") são os mais diversos. Incluem também voltados para inteligência artificial assim como outros. Há mais de 200 serviços ofertados pela microsoft. Que podem se enquadrar em categorias como ia + machine learning, computação, contêiners, banco de dados, devops, internet das coisas (IoT) dentre outros. 

### Serviços em versão prévia
Serviços em versão prévia são serviços em desenvolvimento pela microfost que podem ou não ser mantidos no futuro portanto deve-se tomar atenção ao se utilizar estes serviços.

### Regiões e Zonas de disponibilidade

**Regiões**: Uma região é uma área geográfica do planeta que contém pelo menos um data center, mas possivelmente vários, nas proximidades e conectado a uma rede de baixa latência. Quando você implanta um recurso no Azure, geralmente precisa escolher a região em que deseja que ele seja implantado

> Alguns serviços ou recursos de VM (máquina virtual) estão disponíveis somente em determinadas regiões, como tamanhos específicos de VMs ou tipos de armazenamento.

> Exemplo de serviços Azures que não são necessários especificar a região:  o Azure Active Directory, o Gerenciador de Tráfego do Azure e o DNS do Azure.

**Zona de Disponibilidade**:  Zonas de disponibilidade são datacenters separados fisicamente dentro de uma região do Azure. Cada zona de disponibilidade é composta de um ou mais datacenters equipados com energia, resfriamento e rede independentes. Uma zona de disponibilidade é configurada para ser um limite de isolamento. Se uma zona ficar inativa, as outras continuarão funcionando. Zonas de disponibilidade são conectadas por meio de redes de fibra óptica privadas de alta velocidade.

## SLA
os serviços da azure tem valores de SLA que iniciam em 99% de disponibilidade e podendo chegar a 99,999% de garantia de disponibilidade quanto mais o valor de disponibilidade menos tempo de inatitividade dentro de um período de um mês/ano irá ocorrer. Sendo isto uma garantia da azure. No caso de ocorrer indisponibilidade maior que o acordado pelo SLA do serviço utilizado na azure. A azure disponibilizar em forma de voucher descontos para faturas disponível.
O uso adequado de regiões e zonas de disponibilidade podem influenciar na disponibilidade de um serviço. Por isso também é adequado se antentar nestas configurações. Além de influenciar também nos custos. 

#### Modelo de Cobrança em Nuvem
Ao comparar modelos de infraestrutura de TI, há dois tipos de despesas a serem consideradas. CapEx (despesas de capital) e OpEx (despesas operacionais).

A **CapEx** normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.

Ao contrário, a **OpEx** é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de **serviços de nuvem são exemplos de OpEx**.

## IaaS
IaaS (Infraestrutura como Serviço) : a maior responsabilidade está no consumidor, o provedor fica responsável por questões básicas de segurança física, energia e conectividade. 

## SaaS 
SaaS (Software como Serviço) : a maior parte da responsabilidade está no provedor.

O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Com o SaaS, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de SaaS.

Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

## PaaS 
PaaS (Plataforma como Serviço): sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

O PaaS (Plataforma como serviço) é um meio termo entre alugar espaço em um datacenter (infraestrutura como serviço) e pagar uma solução completa e implantada (software como serviço). Em um ambiente de PaaS, o provedor de nuvem mantém a infraestrutura física, a segurança física e a conexão com a Internet. Ele também mantém os sistemas operacionais, o middleware, as ferramentas de desenvolvimento e os serviços de business intelligence que compõem uma solução de nuvem. Em um cenário de PaaS, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.

O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento.



