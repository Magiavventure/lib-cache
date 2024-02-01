# Magiavventure - Lib cache
![GitHub Release](https://img.shields.io/github/v/release/Magiavventure/lib-cache)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Magiavventure/lib-cache/build.yml)

This library takes care of managing the cache with redis

## Configuration

The properties exposed to configure this project are:

```properties
spring.data.redis.host="string"                     # Host for redis connection
spring.data.redis.database=integer                  # Database for redis default 0
spring.data.redis.port="string"                     # Port for redis connection
spring.data.redis.username="string"                 # Username for redis connection
spring.data.redis.password="string"                 # Password for redis connection
spring.data.redis.timeout=integer"                  # Define timeout for redis
spring.cache.redis.cache-names="string"             # Define cache names (the key of cache)
spring.cache.redis.time-to-live="string"            # Define time to live for defined cache names
```