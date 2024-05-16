Order of Deployment for new account:

  1. infra.yaml
  2. ecr.yaml
  3. alb.yaml
  4. ecs.yaml

  Entries into ECR, ALB, ECS will need manual adjustment with these versions. ECR might need different repository information, ALB might need different listener port, and ECS might need different ports and Images.
  
