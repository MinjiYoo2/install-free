# install-free

- istio-tracing: 실환경 설정 포함한 배포 with gatekeeper

- os-jaeger: opensearch-jaeger 연동 테스트끝난거 local환경

- opensearch-jaeger.yaml : opensearch-jaeger with certmanager

- 01_elasticsearch.yaml : elasticsearch with minikube 

  https://github.com/tmax-cloud/install-EFK
  
- es-jaeger.yaml : elasticsearch v7.2.1 - jaeger v1.27 연동 install yaml

- nginx-ingress-system.yaml : 기존에 사용하던 설치 버전 v0.33.0 ( extensions deprecated)

- ingress-nginx.yaml : latest version (k8s v1.22) 

- jaeger-opensearch-with-gatekeeper.yaml : jaeger-opensearch 연동 gatekeeper설정 포함 실환경 배포 yaml

## istio-1.12
- base.yaml : istio-base

- istiod.yaml : istio-core

- IngressGateway.yaml : ingressgateway

  => kubernetes v1.19 & v1.22

## istio-1.5.1

- 1.istio-base.yaml : istio-base
- 3.istio-core.yaml : istiod
- 4.istio-ingressgateway.yaml : istio-ingressgateway

