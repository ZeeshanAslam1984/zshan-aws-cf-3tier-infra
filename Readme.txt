zshan-aws-cf-3tier-infra
├── networking/
│   └── vpc.yaml
├── security/
│   ├── security-groups.yaml
│   ├── nacls.yaml
│   └── waf.yaml
├── compute/
│   ├── ecs-cluster.yaml
│   ├── ecr.yaml
│   └── ec2.yaml
├── database/
│   └── rds.yaml
├── application/
│   ├── load-balancer.yaml
│   ├── cloudfront.yaml
│   └── ecs-service.yaml
├── config/
│   ├── ssm-params.yaml
│   └── secrets-manager.yaml
├── monitoring/
│   ├── cloudwatch.yaml
│   └── eventbridge.yaml
└── dns/
    └── route53.yaml