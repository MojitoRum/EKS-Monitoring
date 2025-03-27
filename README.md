# EKS-Monitoring
EKS-Monitoring

EKS에서 prometheus와 Grafanana 배포하기 Cluster 구성 부터

0. 사전 설정 (CLI, Kubectl, 자격증명 설정, eksctl, helm)
1. EKS Cluster 배포 (yaml)
2. AWS IAM policy 설정 (alb Controller, serviceaccount policy 연결 rbac)
3. ns 구성
4. ebs-csi-driver (Serviceaccount ebs csi rbac)
5. helm 통해 배포
