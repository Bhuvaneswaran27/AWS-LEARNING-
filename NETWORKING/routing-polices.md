# Route 53 Routing Policies

## 1. Simple Routing
Routes traffic to a single resource.

## 2. Weighted Routing
Distributes traffic across multiple resources based on assigned weights.

## 3. Latency-Based Routing
Routes users to the AWS Region with the lowest network latency.

## 4. Failover Routing
Redirects traffic to a secondary resource if the primary resource becomes unavailable.

## 5. Geolocation Routing
Routes traffic based on the user's geographic location.

## 6. Geoproximity Routing
Routes traffic based on user location and AWS resource location (requires Route 53 Traffic Flow).

## 7. Multi-Value Answer Routing
Returns multiple healthy resource records and improves availability.

## Health Checks
Used with Failover and Multi-Value routing to monitor resource health.
