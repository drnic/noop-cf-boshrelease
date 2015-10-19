Dummy Cloud Foundry BOSH release
================================

This BOSH release was created to be the smallest set of running dependencies for service brokers to advertise their routes, without requiring the entirity of Cloud Foundry to be deployed and running.

It includes

-	NATS - the message bus used by service brokers to advertise a public route
-	Gorouter - the routing mesh used by Cloud Foundry to route incoming HTTP requests to system & user apps
