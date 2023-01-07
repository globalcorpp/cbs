k create deploy redis --image=redis
k expose deploy redis --port=6379
k port-forward service/redis 6379:6379
