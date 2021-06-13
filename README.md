#  Sample HELM repo
sample helm repo to store the charts

**Add this repo to your instance to download and install the charts**

```
$ helm repo add --username <git username> --password <Git password> <Repo name can be anything> https://raw.githubusercontent.com/ramchandra-guthula/helm-repo/main

$ helm repo add --username ramchandra-guthula --password 'xxxxxx' sample-helm-repo  https://raw.githubusercontent.com/ramchandra-guthula/helm-repo/main

```
**Update your local index after adding the repo**
```
helm repo update
```
