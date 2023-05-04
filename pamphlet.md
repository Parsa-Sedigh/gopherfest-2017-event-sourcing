Old server architectures(monoliths):

app -> DB  (this structure is called a bounded context)

Microservices are composed of **bounded contexts**.

## Considerations for micro services
- expand/contract style
- service discovery
- graceful service degradation
- back pressure
- circuit breakers
- 99th percentile latency
- back ends for front ends(BFFs)
- docker-compose

Technologies:
- consul
- etcd
- fabio
- kubernetes
- vault
- zookeeper
- scripts, scripts, scripts!

## My wish list
- I don't ever want to do another upgrade
- I only want to troubleshoot my app, not your service(etcd, ...)
- I don't want to pay a fortune for it
- I have a lot of juniors and I'd like way for them to be more productive
- I want the servie to scale gracefully(we don't want to think about scaling, we want someone else to deal with it)

