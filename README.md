# CURRENCY SERVICE
Spring boot microservice for simulating currency conversion.

Wonderful demonstration of the versatility of the Spring Boot.

Works by reaching out to the [forex-service provider](https://github.com/teamlead-agbaje/forex-service) to get conversation rates.

Once running, it connects to the eureka-naming-server, which acts as a load-balancer. This way, you don't have to keep hard-coding URIs and ports - eureka handles that. Fabolous stuff!
