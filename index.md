### liuyujie-tx
helm-chart repostory of liuyujie-tx

### Quick Start
#### Skywalking
```
helm repo add liuyujie-tx https://liuyujie-tx.github.io/helm-charts/
helm install skywalking liuyujie-tx/skywalking
```

#### Arena
```
helm repo add liuyujie-tx https://liuyujie-tx.github.io/helm-charts/
helm install arena liuyujie-tx/arena
```

### Canal
canal定制依赖MQ和Mysql

#### Canal Server
```
helm repo add liuyujie-tx https://liuyujie-tx.github.io/helm-charts/
helm install canal-server liuyujie-tx/canal-server
```

#### Canal Adapter
```
helm repo add liuyujie-tx https://liuyujie-tx.github.io/helm-charts/
helm install canal-adapter liuyujie-tx/canal-adapter
```
