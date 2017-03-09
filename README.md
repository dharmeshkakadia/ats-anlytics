# ats-anlytics


### Pre-requsite
* httpie
* jq

###how to know how many queries ran on cluster?

```
http --auth user:password  https://clustername.azurehdinsight.cn/ws/v1/timeline/TEZ_DAG_ID | jq '.entities | length'
```
