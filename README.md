# Application Insights manual instrumentation workshop

This repo contains code for manual instrumentation solution. It is a part of the sample code for all the exercises in the [cloud native learning path for .NET](https://learn.microsoft.com/training/paths/create-microservices-with-dotnet/).

1. Navigate to dotnet-observability\finished-files\docker-compose.yml and update APPLICATIONINSIGHTS_CONNECTION_STRING with your value
2. Run docker compose up command in dotnet-observability\finished-files directory
3. In your browser, open http://localhost:32000/ and create some traffic
4. Open your application insights instance, verify that data is flowing