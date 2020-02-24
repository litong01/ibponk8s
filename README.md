## Deploy IBP onto Kubernetes

### Clone this repo and make the tool executable

```
git clone https://github.com/litong01/ibponk8s.git
cd ibponk8s && chmod +x ibptool.sh 
```

### Modify mysettings.sh file with your own settings

### Start up IBP on Kubernetes

```
./ibptool.sh up
```

### Remove IBP from Kubernetes
```
./ibptool.sh down
```

### You can change any parameter value by using command line options like this
```
./ibptool.sh up --email-address fake@ddd.com --entitlement-key keyvalue
```
