# ubuntu
```
sudo apt install redis-tools
```

```
redis-cli -h localhost -p 6379 -a password
```

or do `redis-cli` then pass
```
auth password
```

# windows 
check redis connectivity
```
telnet redis-hostname.redis.cache.windows.net 6380 
```

## connnect trough TLS port 

<https://techcommunity.microsoft.com/t5/azure-paas-blog/connect-to-azure-cache-for-redis-using-ssl-port-6380-from-linux/ba-p/1186109>
