Repository with Helm starters.

### Installation
Clone this repository to your helm configuration directory.
```
     git clone https://github.com/sybrenbolandit/helm-starters.git ~/.helm/starters
```

### Creating a helm chart
A new helm chart can be created using the helm cli tool. 
```
    helm create -p <STARTER> <PROJECT_NAME>
```
For example: `helm create -p java-api person-api`
