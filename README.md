# microservices-config-server
Repository where to store configurations files for:
order-service,product-service,inventory-service

Whenever you push new values just throw the POST /actuator/refresh or POST /actuator/busrefresh for refreshing beans
tagged with @RefreshCope tag to refresh values .
