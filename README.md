# spring-graphql
With GraphQL, clients can specify exactly what data they need, reducing over-fetching and under-fetching. This is especially useful for mobile devices or environments with limited bandwidth.

# Actuator
http://localhost:9191\actuator

# using postman graphql hit
http://localhost:9191/graphql

# curl
curl -X POST \
-H "Content-Type: application/json" \
-d '{"query":"{  getProducts { name category price } }"}' \
http://localhost:9191/graphql