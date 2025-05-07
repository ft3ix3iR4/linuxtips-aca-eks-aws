# linuxtips-aca-eks-aws
Repositório Central do Curso de Containers no AWS EKS. Materiais extras e guia do curso.
## Repositório das Aulas - EKS

| Recurso / Aula                | Repositório                                                                                                           |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| VPC / Networking              | [Link do Github](https://github.com/msfidelis/linuxtips-curso-containers-aws-eks-networking)
| EKS - Basico (Vanilla)          | [Link do Github](EM BREVE)
| EKS - Estratégias de Node Groups  | [Link do Github](EM BREVE)
| EKS - Fargate (Fargate Profiles)   | [Link do Github](EM BREVE)
| EKS - Cluster Full Fargate   | [Link do Github](EM BREVE)
| EKS - Karpenter               | [Link do Github](EM BREVE)
| EKS - Karpenter Groupless   | [Link do Github](EM BREVE)
| EKS - AWS Load Balancer Controller   | [Link do Github](EM BREVE)
| EKS - Nginx Controller   | [Link do Github](EM BREVE)
| EKS - Pod Identity, EBS S3 e EFS CSI Addons   | [Link do Github](EM BREVE)
| EKS - External Secrets com AWS Secrets Manager   | [Link do Github](EM BREVE)
| EKS - EKS Automode   | [Link do Github](EM BREVE)
| EKS - Prometheus  | [Link do Github](EM BREVE)
| EKS - Istio Service Mesh | [Link do Github](EM BREVE)
| EKS - Keda Autoscaler | [Link do Github](EM BREVE)
| EKS - Argo Rollouts | [Link do Github](EM BREVE)
| EKS - Helm Chart | [Link do Github](EM BREVE)
| EKS - ArgoCD | [Link do Github](EM BREVE)
| EKS - Projeto Final (MultiCluster Management e Observability Cluster) | [Link do Github](/extras/eks-projeto-final/)

## Materiais Extras 

| Material                                          | Link                                                                                                                                              |
|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Conceitos Básicos Amazon EKS                      | [Link](https://aws.amazon.com/pt/eks/getting-started/)                                                                                            |
| VPC CIDR blocks                                   | [Link](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-cidr-blocks.html#vpc-sizing-ipv4)                                                     | 
| EKS Best Practices                                  | [Link](https://aws.github.io/aws-eks-best-practices/)                                                     | 
| Terraform - Kubernetes Provider                    | [Link](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs)          | 
| Terraform - Helm Provider                          | [Link](https://registry.terraform.io/providers/hashicorp/helm/latest/docs)            |
| Controlador de Recuperação de Aplicações da Amazon | [Link](https://aws.amazon.com/pt/application-recovery-controller/)                                                                                 | 
| Zonal autoshift in ARC                              | [Link](https://docs.aws.amazon.com/r53recovery/latest/dg/arc-zonal-autoshift.html)                                                               | 
| Learn about Amazon Application Recovery Controller’s (ARC) Zonal Shift in Amazon EKS | [Link](https://docs.aws.amazon.com/eks/latest/userguide/zone-shift.html)                                        | 
| Amazon AWS - EC2 Graviton                          | [Link](https://aws.amazon.com/pt/pm/ec2-graviton/)                                                                                                | 
| Amazon AWS - EC2 Bottlerocket | [Link](https://aws.amazon.com/pt/bottlerocket/?amazon-bottlerocket-whats-new.sort-by=item.additionalFields.postDateTime&amazon-bottlerocket-whats-new.sort-order=desc) |
| Github - Bottlerocket                              | [Link](https://github.com/bottlerocket-os/bottlerocket)                                                                                           |
| Amazon EC2 - Instance Types                        | [Link](https://aws.amazon.com/ec2/instance-types/)                                                                                                |
| EC2 Instance Comparator                            | [Link](https://instances.vantage.sh)                                                                                                              |
| Amazon EKS - NodeGroups amiTypes                   | [Link](https://docs.aws.amazon.com/eks/latest/APIReference/API_Nodegroup.html#AmazonEKS-Type-Nodegroup-amiType)                                   |
| Node Termination Handler                           | [Link](https://github.com/aws/aws-node-termination-handler)                                                                                       |
| EC2 Instance Types AWS                             | [Link](https://aws.amazon.com/pt/ec2/instance-types/)                                                                                             |
| Recommended Amazon Linux AMI                       | [Link](https://docs.aws.amazon.com/eks/latest/userguide/retrieve-ami-id.html)                                                                     |
| Recommended Bottlerocket AMI                       | [Link](https://docs.aws.amazon.com/eks/latest/userguide/retrieve-ami-id.html)                                                                     |
| Terraform Kubectl Provider                         | [Link](https://docs.aws.amazon.com/eks/latest/userguide/retrieve-ami-id-bottlerocket.html)                                                        |
| Predefined SSL security policies                   | [Link](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-security-policy-table.html)                                            |
| AWS Load Balancer Controller                       | [Link](https://kubernetes-sigs.github.io/aws-load-balancer-controller/)                                                                           |
| Ingress Nginx                                      | [Link](https://github.com/kubernetes/ingress-nginx/tree/main/charts/ingress-nginx)                                                                |
| Kubernetes Gateway API                             | [Link](https://gateway-api.sigs.k8s.io/guides/)                       |
| Learn how EKS Pod Identity grants pods access to AWS services | [Link](https://docs.aws.amazon.com/eks/latest/userguide/pod-identities.html) |
| Store an elastic file system with Amazon EFS  | [Link](https://docs.aws.amazon.com/eks/latest/userguide/efs-csi.html) |
| Store Kubernetes volumes with Amazon EBS | [Link](https://docs.aws.amazon.com/eks/latest/userguide/ebs-csi.html) |
| Learn how EKS Pod Identity grants pods access to AWS services | [Link](https://docs.aws.amazon.com/eks/latest/userguide/pod-identities.html) |
| Workshop: EFS CSI Driver | [Link](https://www.eksworkshop.com/docs/fundamentals/storage/efs/efs-csi-driver) |
| External Secrets | [Link](https://github.com/external-secrets/external-secrets) | 
| External Secrets | [Link](https://github.com/external-secrets/external-secrets) |
| Workshop - External Secrets Operator | [Link](https://www.eksworkshop.com/docs/security/secrets-management/secrets-manager/external-secrets) |
| Enable EKS Auto Mode on existing EKS clusters | [Link](https://docs.aws.amazon.com/eks/latest/userguide/migrate-auto.html) |
| Kube Prometheus Stack | [Link](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack) |
| Grafana Dashboards | [Link](https://grafana.com/grafana/dashboards/) |
| Prometheus Query Basics | [Link](https://prometheus.io/docs/prometheus/latest/querying/basics/) |
| Istio Service Mesh | [Link](https://istio.io/) |
| Istio Releases | [Link](https://github.com/istio/istio/releases) |
| Kiali - Console for Istio Service Mesh | [Link](https://kiali.io/) |
| Istio Helm Charts | [Link](https://github.com/istio/istio/tree/master/manifests/charts) |
| Istio Ingress Gateway | [Link](https://github.com/istio/istio/blob/master/manifests/charts/gateways/istio-ingress/values.yaml) |
| Keda Event Driven Autoscaling | [Link](https://keda.sh/) |
| Keda Scalers | [Link](https://keda.sh/docs/2.16/scalers/) |
| Keda - CPU | [Link](https://keda.sh/docs/2.16/scalers/cpu/) |
| Keda - Cron | [Link](https://keda.sh/docs/2.16/scalers/cron/) |
| Keda - Prometheus | [Link](https://keda.sh/docs/2.16/scalers/prometheus/) |
| Argo Rollouts | [Link](https://argoproj.github.io/rollouts/) |
| Argo Rollouts (docs) | [Link](https://argoproj.github.io/argo-rollouts/) |
| Argo Rollouts (Blue Green) | [Link](https://argoproj.github.io/argo-rollouts/features/bluegreen/) |
| Argo Rollouts (Canary) | [Link](https://argoproj.github.io/argo-rollouts/features/canary/) |
| Argo Rollouts (AnalysisTemplate) | [Link](https://argoproj.github.io/argo-rollouts/analysis/prometheus/) |

# EKS 

## VPC Networking

![networking-eks](https://github.com/user-attachments/assets/41b47ef5-6ea6-4d2a-a9ce-821ab982543c)