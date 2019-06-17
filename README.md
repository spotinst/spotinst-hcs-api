# spotinst-hcs-api

API for Spotinst [Health Check Service] (https://api.spotinst.com/elastigroup-for-aws/services-integrations/spotinst-custom-health-check-service-hcs-2/)


## UI

User friendly UI with redoc: [https://spotinst.github.io/spotinst-hcs-api/][ui-url]


[ui-url]: https://spotinst.github.io/spotinst-hcs-api/

## How Does It Work?

Spotinst backend will make the 'check' call to the HCS client every X seconds according to the health check configuration in order to get all the Elastigroup instances status. 
The client should respond with the http check of each instance so Spotinst backend can determine wether the instance should be treated as Healthy/Unhealtyh.
