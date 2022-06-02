# install-free

- istio-tracing: 실환경 설정 포함한 배포 with gatekeeper

- os-jaeger: opensearch-jaeger 연동 테스트끝난거 local환경

- opensearch-jaeger.yaml : opensearch-jaeger with certmanager

- 01_elasticsearch.yaml : elasticsearch with minikube 

  https://github.com/tmax-cloud/install-EFK

## istio-1.12
- base.yaml : istio-base
- istiod.yaml : istio-core
- IngressGateway.yaml : ingressgateway
=> kubernetes v1.19 & v1.22