Idea 5: Home Maintenance Request System


User Scenario 1: Homeowner submits a maintenance request, and the system categorizes the request and assigns it to the appropriate service provider.

Microservices: Homeowner, Request, ServiceProvider



User Scenario 2: Service provider receives the request and can accept or decline based on their availability.

Microservices: ServiceProvider, Notification, Request



User Scenario 3: Homeowner pays for the service, and if the service is unsatisfactory, the system allows for a partial refund.

Microservices: Homeowner, Payment, Request



External Service: Use a payment gateway API for processing payments.

Choreography: The Request microservice orchestrates the ServiceProvider and Notification services.
