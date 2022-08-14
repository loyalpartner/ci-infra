
sonarqube
```
sysctl -w vm.max_map_count=262144
```

gitlab
```
docker exec -it gitlab grep 'Password:' /etc/gitlab/initial_root_password
```
