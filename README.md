# AWS CDK Migration Examples

This repository contains example configurations for migrating AWS CDK pipelines from AWS Code Suite to CircleCI.

## Overview

With AWS phasing out support for CodeCommit, this repository serves as a companion to our [AWS Code Suite Migration blog post](https://circleci.com/blog/aws-code-suite-migration). Here you'll find complete configuration examples demonstrating how to implement AWS CDK deployments in CircleCI.

## Contents

This repository includes:

- Basic CDK deployment configurations
- Multi-environment deployment examples (dev/staging/prod)
- Multi-account deployment strategies
- Monorepo configuration examples
- Configuration migration templates

## Benefits of CircleCI for CDK Deployments

Each example showcases CircleCI's key advantages for infrastructure as code deployments:

- Simplified authentication with OIDC
- Reusable components through orbs
- Efficient caching and workspace strategies
- Docker layer caching for faster builds
- Streamlined workflow definitions

## How to Use This Repository

1. Browse to the example that most closely matches your current AWS CDK setup
2. Review both the AWS Code Suite and equivalent CircleCI configurations
3. Use the provided configurations as templates for your own migration
4. Refer to comments within the files for migration tips and best practices

## Additional Resources

- [CircleCI Documentation](https://circleci.com/docs/)
- [AWS CDK Documentation](https://docs.aws.amazon.com/cdk/)
- [AWS Code Suite Migration Guide](https://circleci.com/blog/aws-code-suite-migration)

---

This repository is maintained by CircleCI. For questions or support, please contact us at support@circleci.com
