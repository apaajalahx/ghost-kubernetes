

run mysql
```
kubectl apply -f config/mysql-config.yml
kubectl apply -f volumes/mysql-pv-claim.yml
kubectl apply -f mysql.yml
```
run ghost
```
kubectl apply -f config/ghost-config.yml
kubectl apply -f volumes/ghost-pv-claim.yml
kubectl apply 0f ghost.yml
```