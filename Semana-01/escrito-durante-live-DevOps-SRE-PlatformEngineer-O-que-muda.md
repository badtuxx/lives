# DevOps, SRE e Platform Engineer, o que muda?

## Entendo cada uma das funções

SysAdmin -> DevOps - SRE - Platform Engineer

Dificilmente -> Dev -> DevOps/SRE/PE

DBRE - Um DBA com SRE

### DevOps Engineer
- **Integração** entre os times, inicialmente Dev e Ops.
- **Pipelines** - CI/CD - Gitlab CI, Github Actions, Jenkins
- **Dockerização** - Docker, Kubernetes, Rancher, OpenShift
- **IaC** - Começou aqui, mas hoje já não é mais tanto responsabilidade do DevOps -> CFEngine (láaaa em 2012), Terraform, Puppet (laaaaá em 2014), Ansible, Crossplane, Pulumi (hoje menos, mas ainda sim)
**- Observabilidade???**

#### Objetivo Principal
- Colaboração e automação para a entrega contína de software

#### Foco
- Processo e na integração entre Desenvolvimento e Operações

#### Métricas
- Velocidade de entrega e frequência de deploy

#### Ferramentas
- CI/CD
- Docker
- Kubernetes
- Cloud
- Bash / Python+++

#### Habilidades
- Scripting
- Automação
- Colaboração entre equipes
- CI/CD

### SRE
- **Responsável pelo ambiente produtivo**
- **Observabilidade** - SLA e SLO, Uptime, performance da app, qtde de erros, tempo de resposta, timeouts..
- **Service Mesh** - Melhorar response times, rotas, observabilidade, etc 
- **IaC** - É importante, mas ele não é o dono. Tem que conhecer, vai utilizar, mas não não é o foco
- **Cloud** - Muito importante do que para um DevOps.
- **Multi-Cloud** - É responsa dividida com o PE
- **Custos** - Importante, não somente para ele

#### Objetivo Principal
- Garantir a confiabilidade, resiliência, disponibilidade e performance do sistema/site/app/serviço

#### Foco
- Operação e a manutenção do serviço em produção

#### Métricas
- SLO, SLI e SLA - São importantes pois definem o acordo de nível de serviço com o cliente (SLA), com a equipe interna (SLO) e claro, precisamos saber a foto real (SLI)

#### Ferramentas
- Prometheus/Grafana/Kiali
- Istio
- Kubernetes
- Python / Go - Scripting
- Java (nem tanto assim) - Observabilidade - Instrumentar muito código Java.
- IaC
- Datadog e similares - Para mais recursos relacionados a observabilidade

#### Habilidades
- Programação - Não um Dev, mas tem que ter um conhecimento maior que um devops precisa
- Gerenciamento de crise
- Automação
- Observabilidade
- Cloud - Interessante ter Design/arquitetura de cloud/multi-cloud
- Senso de Curiosidade

### Platform Engineer
- **Responsável por criar e manter uma plataforma interna**
- **Produtização** de serviços em sua infraestrutura
- **Padronização** do ambiente
- **Facilitar a construção e entrega de software no ambiente**
- **Reduzir a complexidade** para criação de coisas em nosso ambiente/infra
- **Reduzir a carga cognitiva** da equipe
- **Criar módulos** das peças da nossa infra/sistema

#### Objetivo Principal
Fornecer plataformas internas para suportar o desenvolvimento de produtos

#### Foco
Infraestrutura e no suporte no ciclo de vida do desenvolvimento de produtos

#### Métricas
Tempo de provisionamento de ambientes, satisfação do desenvolvedor

#### Ferramentas
- Terraform
- Backstage
- Ansible
- kubernetes
- Cloud
- GitOps/Argocd
- Python / Go

#### Habilidades
- Programação - Mais um pouco do que o SRE e muito mais do que o DevOps
- Conhecimento de Infra e Operação
- Automação
- Arquitetura/Design
- Dono de uma porção de peças importantes, portanto, importante ter StackHolders Management
- Observabilidade


### Ferramentas em Comum que precisamos saber para qualquer das três
- IaC (Terraform, Ansible, etc) 
- Git
- Containers
- Cloud
- Observabilidade
- CI/CD
- Scripting
- Linux