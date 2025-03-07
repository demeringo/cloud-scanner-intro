# Roadmap and future work

## Cover more services

A first objective is to increase the scope of the services.

- Object storage / S3
- FAAS / Serverless (like AWS lambda or Azure functions)
- Additional managed services (like DB as a service)
- Impacts of GPUs, which is key to assess AI/ML workload

For each new service, this will likely be a 2 step process:

1. Define a common model (identify key drivers of the impacts) and implement this model in Boavizta API.
2. Automate collection of related data in cloud scanner.

## Expand to other cloud providers

- Azure (work in progress)
- Scaleway (work in progress)
- OVH
- ...

## Provide recommendations

Estimating environmental impacts only makes sense if we can use it to avoid unnecessary impacts.

In the future cloud-scanner may provide insights on what is wasted and where to apply efforts of reduction.
