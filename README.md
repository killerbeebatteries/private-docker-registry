# private-docker-registry

## Instructions

```
htpasswd -Bc registry.password adminuser
docker-compose up
```

```
docker login localhost:5000
```

## References

Thanks to [Earthly](https://earthly.dev/blog/private-docker-registry/)
