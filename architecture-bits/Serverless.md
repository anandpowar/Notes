# Serverless
: implies you (as developers) do not monitor/manage server infra; the responsibility shifts to service provider
- Cloud does not equate to Serverless
- Serverless is a deployment model (not an architecture style)

## Server vs Serverless
- Servers use computing power even when ideal; scaling is controlled by developer/admin
- Serverless charges developers based on utilization; auto-scales

## Serverless approaches
- BaaS - Backend as a Service
  : Developers focus on frontend; backed available as a service
  examples: Auth0, Loggly, Amazon Elasticsearch Service

- FaaS - Functions as a Service
  : Stateless; Event-driven; Microservices are good fit
  examples: AWS Lambda, Firebase and Azure Functions 

## Trade-offs vs Opportunities 
- Cold start (undesired)
- Vendor lock-in (undesired)
- Low-cost (desired; provided you have loads of ideal-time)
