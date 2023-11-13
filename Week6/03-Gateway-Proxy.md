# Amazon API Gateway Proxy for AWS Services
One API Gateway integration type is the AWS integration type. This allows you to proxy other AWS services with API Gateway.

Each method you setup for a reason using an AWS integration type would expose one API or AWS service action. Because the AWS API will need the data in a specific format that your clients likely won’t be using, you must configure both the integration request and integration response and set up necessary data mappings from the method request to the integration request, and from the integration response to the method response. This will transform the request and response to adhere to the specifications needed for the AWS API.

Read more about API Gateway integration types here: https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-api-integration-types.html

# Amazon API Gateway HTTP APIs
HTTP APIs are designed for low-latency, cost-effective AWS Lambda proxy and HTTP proxy APIs. HTTP APIs support OIDC and OAuth 2.0 authorization, and come with built-in support for CORS and automatic deployments. Previous-generation REST APIs currently offer more features, and full control over API requests and responses.


Read about how to choose between REST and HTTP APIs here: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html

