# Blockchain on Kubernetes

This project demonstrates how to architect a blockchain application using microservices and deploy it on Kubernetes.

## Microservices

- Admin API
- Core API
- Payment API
- Email and Notification Service
- Cron Tasks Service
- Webhooks API

## Prerequisites

- Node.js
- Docker
- Kubernetes
- Helm
- AWS CLI (for deployment to EKS)

## Local Development

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the services: `docker-compose up`

## Deployment

Deployment is handled via GitHub Actions. See `.github/workflows/ci-cd.yml` for details.

## Configuration

Each microservice has its own Helm chart in the `charts/` directory. Configuration values are stored in `values.yaml`, `values-dev.yaml`, and `values-stage.yaml`.

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
