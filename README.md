# Deploying to AWS with GitHub Action

Repository template for workshop: [Deploying to AWS with GitHub Action](https://catalog.us-east-1.prod.workshops.aws/workshops/6804609d-2342-4c7b-a406-a017aa496b6b)

Follow the instruction on the workshop for steps by steps detail on how to use this template. This template includes several components as shown below.

## CloudFormation

* [./templates/bootstrap-minimal.yaml](./templates/bootstrap-minimal.yaml) to bootstrap your AWS account environment
* [./templates/cluster.yaml](./templates/cluster.yaml) to launch ECS cluster

## Sample App

* [./app/](./app/) directory contain a sample app taken from [ECS simple demo app](https://github.com/aws-samples/ecs-demo-php-simple-app)

## Workflow

* [./.github/workflows/](./.github/workflows/) directory contain several workflow files to assist you on the workshop.

## Final Architecture

![Architecture](/static/images/deploy-to-aws-with-github-action.png)
