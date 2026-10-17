# ToggleMaster — GitOps

Repositório de configurações para implantação do ToggleMaster
no Kubernetes, desenvolvido para o Tech Challenge Fase 2 da FIAP.

## Status

Em preparação. Nenhum recurso foi implantado por este repositório.

## Conteúdo planejado

- Manifestos Kubernetes dos cinco microsserviços.
- Configurações de acesso externo com Ingress.
- Integração com Argo CD.
- Integração com External Secrets Operator.
- HPA por CPU para evaluation-service.
- KEDA por fila SQS para analytics-service, conforme as permissões da AWS.
- Documentação da implantação e da arquitetura.

## Código da aplicação

Os microsserviços, Dockerfiles e o ambiente local com Docker Compose
ficam no repositório:

https://github.com/RaiTulik/ToggleMaster

## Segredos

Credenciais reais não devem ser versionadas.
Este repositório manterá apenas referências e configurações
necessárias à integração com o gerenciador de segredos.