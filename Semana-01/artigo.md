# DevOps, SRE e Platform Engineer: Quais São as Diferenças?

## Introdução

No cenário atual, os termos **DevOps**, **SRE (Site Reliability Engineer)** e **Platform Engineer** têm ganhado destaque nas organizações que buscam agilidade, confiabilidade e eficiência em seus processos de desenvolvimento e operação. Apesar de estarem interligadas, cada uma dessas funções possui objetivos, focos e habilidades distintas. Este artigo tem como objetivo esclarecer as diferenças entre essas funções, proporcionando uma compreensão mais clara para profissionais e entusiastas da área.

## Evolução das Funções de Infraestrutura

A jornada começou com o **SysAdmin**, o administrador de sistemas tradicional, responsável pela manutenção e configuração de servidores e infraestrutura. Com a necessidade de integrar equipes de desenvolvimento e operações para acelerar a entrega de software, surgiu o **DevOps Engineer**. À medida que a complexidade dos sistemas aumentou, especialmente em ambientes em nuvem, a função de **SRE** emergiu, focando na confiabilidade e disponibilidade dos serviços. Recentemente, o **Platform Engineer** entrou em cena para criar plataformas internas que suportam e facilitam o ciclo de vida do desenvolvimento de produtos.

### Do SysAdmin ao Platform Engineer

- **SysAdmin**: Foco na manutenção e configuração de servidores.
- **DevOps Engineer**: Integração entre desenvolvimento e operações, automação e entrega contínua.
- **SRE**: Garantia de confiabilidade, resiliência e desempenho dos sistemas em produção.
- **Platform Engineer**: Criação e manutenção de plataformas internas para suportar o desenvolvimento e operações.

### Transições de Carreira

É comum profissionais de **SysAdmin** evoluírem para **DevOps**, **SRE** ou **Platform Engineer** devido à sua experiência em infraestrutura. No entanto, é menos frequente que desenvolvedores façam essa transição, já que essas funções exigem um conhecimento profundo de operações e infraestrutura.

### DBRE (Database Reliability Engineer)

Uma especialização dentro do SRE é o **DBRE**, que combina habilidades de um administrador de banco de dados (DBA) com práticas de confiabilidade, garantindo que os sistemas de banco de dados sejam escaláveis, confiáveis e eficientes.

## DevOps Engineer

### Objetivo Principal

Promover a colaboração e automação para a entrega contínua de software, integrando equipes de desenvolvimento e operações.

### Foco

- **Processos**: Otimização dos processos de desenvolvimento e implantação.
- **Integração**: Facilitar a comunicação entre equipes de desenvolvimento (Dev) e operações (Ops).

### Métricas

- **Velocidade de Entrega**: Rapidez com que o software é entregue ao usuário final.
- **Frequência de Deploy**: Quantidade de implantações realizadas em um determinado período.

### Ferramentas

- **CI/CD**: GitLab CI, GitHub Actions, Jenkins.
- **Contêineres e Orquestração**: Docker, Kubernetes, Rancher, OpenShift.
- **Infraestrutura como Código (IaC)**: Terraform, Ansible.
- **Linguagens de Scripting**: Bash, Python.

### Habilidades

- **Scripting e Automação**: Capacidade de escrever scripts para automatizar tarefas.
- **Colaboração Interequipes**: Habilidade de trabalhar em conjunto com diferentes equipes.
- **Conhecimento de CI/CD**: Implementação e manutenção de pipelines de integração e entrega contínuas.

## Site Reliability Engineer (SRE)

### Objetivo Principal

Garantir a confiabilidade, resiliência, disponibilidade e performance dos sistemas em produção.

### Foco

- **Operação em Produção**: Manutenção e monitoramento de sistemas em tempo real.
- **Observabilidade**: Implementação de métricas, logs e traços para entender o comportamento do sistema.

### Métricas

- **SLA (Service Level Agreement)**: Acordo de nível de serviço com o cliente.
- **SLO (Service Level Objective)**: Objetivos internos de nível de serviço.
- **SLI (Service Level Indicator)**: Indicadores que mostram o desempenho real do serviço.

### Ferramentas

- **Monitoramento e Observabilidade**: Prometheus, Grafana, Datadog, Kiali.
- **Service Mesh**: Istio para gerenciamento de tráfego e políticas.
- **Orquestração de Contêineres**: Kubernetes.
- **Linguagens de Programação**: Python, Go.

### Habilidades

- **Programação Avançada**: Habilidade de codificar scripts e ferramentas personalizados.
- **Gerenciamento de Crises**: Capacidade de resolver incidentes rapidamente.
- **Automação e Observabilidade**: Implementação de soluções automatizadas para monitoramento.
- **Conhecimento em Cloud**: Design e arquitetura em ambientes de nuvem e multicloud.
- **Senso de Curiosidade**: Proatividade em aprender e implementar novas soluções.

## Platform Engineer

### Objetivo Principal

Fornecer e manter plataformas internas que suportam o desenvolvimento e operações, facilitando o ciclo de vida dos produtos.

### Foco

- **Infraestrutura como Produto**: Tratamento da infraestrutura como um produto para uso interno.
- **Padronização e Produtização**: Criação de padrões e módulos reutilizáveis.
- **Redução da Complexidade**: Simplificação de processos para desenvolvedores e operadores.

### Métricas

- **Tempo de Provisionamento**: Rapidez na criação de ambientes.
- **Satisfação do Desenvolvedor**: Feedback positivo dos usuários internos da plataforma.

### Ferramentas

- **IaC e Automação**: Terraform, Ansible.
- **Plataformas Internas**: Backstage.
- **Orquestração e GitOps**: Kubernetes, ArgoCD.
- **Linguagens de Programação**: Python, Go.

### Habilidades

- **Programação Avançada**: Desenvolvimento de ferramentas e plataformas internas.
- **Conhecimento Profundo de Infraestrutura**: Entendimento detalhado de sistemas e operações.
- **Automação em Larga Escala**: Implementação de soluções que atendam a toda a organização.
- **Arquitetura e Design**: Planejamento de sistemas escaláveis e eficientes.
- **Gerenciamento de Stakeholders**: Comunicação eficaz com diferentes partes interessadas.
- **Observabilidade**: Monitoramento da plataforma para garantir desempenho e confiabilidade.

## Ferramentas e Conhecimentos Comuns

Independentemente da função, alguns conhecimentos e ferramentas são essenciais:

- **Infraestrutura como Código (IaC)**: Terraform, Ansible.
- **Controle de Versão**: Git.
- **Contêineres**: Docker, Kubernetes.
- **Computação em Nuvem**: AWS, Azure, Google Cloud.
- **Observabilidade**: Monitoramento e logging.
- **CI/CD**: Pipelines de integração e entrega contínuas.
- **Scripting**: Bash, Python.
- **Sistemas Operacionais**: Linux.

## Conclusão

Compreender as diferenças entre **DevOps**, **SRE** e **Platform Engineer** é fundamental para organizações e profissionais que desejam otimizar seus processos de desenvolvimento e operações. Cada função possui um papel específico que, quando combinados, contribuem para a entrega de software de alta qualidade, confiável e eficiente. Investir no desenvolvimento dessas áreas pode trazer benefícios significativos em termos de agilidade, escalabilidade e satisfação tanto dos clientes quanto das equipes internas.

## Referências

- [Site Reliability Engineering - Google](https://sre.google/sre-book/table-of-contents/)
- [What is Platform Engineering? - Humanitec](https://humanitec.com/blog/what-is-platform-engineering)
- [The DevOps Handbook - Gene Kim, Jez Humble, Patrick Debois, John Willis](https://itrevolution.com/book/the-devops-handbook/)