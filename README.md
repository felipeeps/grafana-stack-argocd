# Grafana Stack - Deploy com ArgoCD
  Os projetos foram todos configurado levando em consideração alta disponibilidade, escalabilidade, e resiliência, dentro do padrão de projetos do ArgoCD foi considerado as configurações de parâmetros para especificar todas as características e sizings das aplicações, e o values considerando todas as configuração especificas de cada ambiente, como por exemplo Ingress e NodeSelector.

## Kube-prometheus-stack:
  Instala a pilha kube-prometheus , uma coleção de manifestos do Kubernetes , painéis do Grafana e regras do Prometheus combinadas com documentação e scripts para fornecer monitoramento de cluster do Kubernetes de ponta a ponta fácil de operar com o Prometheus usando o Prometheus Operator.

## Grafana Loki:
  O Loki é um sistema de agregação de log multilocatário escalável horizontalmente, altamente disponível e inspirado no Prometheus. Ele foi projetado para ser muito econômico e fácil de operar. Ele não indexa o conteúdo dos logs, mas sim um conjunto de rótulos para cada fluxo de log.

## Grafana Tempo:
  O Grafana Tempo é um back-end de rastreamento distribuído de código aberto, fácil de usar e de alta escala. O Tempo é econômico, exigindo apenas armazenamento de objetos para operar e está profundamente integrado ao Grafana, Prometheus e Loki. O Tempo pode ingerir protocolos comuns de rastreamento de código aberto, incluindo Jaeger, Zipkin e OpenTelemetry.
