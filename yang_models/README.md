## YANG

```shell
$ pyang ietf-network-anomaly-symptom-cbl@2025-04-11.yang -f tree --tree-line-length 69 -p dependencies
$ pyang ietf-network-anomaly-service-topology@2025-04-11.yang -f tree --tree-line-length 69 -p dependencies
$ pyang ietf-relevant-state@2025-04-17.yang -f tree --tree-line-length 69 -p dependencies
```

Full tree
```shell
$ pyang ietf-relevant-state@2025-04-17.yang ietf-network-anomaly-symptom-cbl@2025-04-11.yang ietf-network-anomaly-service-topology@2025-04-11.yang  -f tree --tree-line-length 69 -p dependencies
```

Format for Datatracker
```shell
$ pyang ietf-relevant-state@2025-04-17.yang -f yang --yang-line-length=69 -p dependencies
$ pyang ietf-network-anomaly-symptom-cbl@2025-04-11.yang -f yang --yang-line-length=69 -p dependencies
$ pyang ietf-network-anomaly-service-topology@2025-04-11.yang -f yang --yang-line-length=69 -p dependencies
```