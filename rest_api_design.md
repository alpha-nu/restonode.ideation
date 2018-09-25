# API Design

## Representations

The domain name of the api and the version will be:
```
http://api.restonode.com/v1/order-management
```
Based on the object model, we derive the following actions:
 
### view restaurants
```
GET /v1/order-management/restaurants
```
### rate restaurant 
```
POST /v1/order-management/restaurants/{id}/rate
```
### place an order
```
POST /v1/order-management/orders
```
### view meals of a restaurant
```
GET /v1/order-management/restaurants/{id}/meals
```
### view meal details
```
GET /v1/order-management/restaurants/{id}/meals/{id}
```
### create restaurant
```
POST /v1/order-management/restaurants
```
### create meal
```
POST /v1/order-management/restaurants/{id}/meals
```
