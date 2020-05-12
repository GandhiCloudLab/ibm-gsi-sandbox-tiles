# Access Group and Access Policies Creation

The objective of the tile is to create the Access Group and Access Policies in IAM using terraform scripts.


## Access Groups

```
    CLOUDMANAGEMENT-ADMINS
    APPDEV-ADMINS
    APPDEV-ENVIRONMENT-ADMINS
    APPDEV-USERS
    INTEGRATION-ADMINS
    DATA-ADMINS
    AUTOMATION-ADMINS
```


## Access Policies

For all ADMIN groups 

```
-   Administrtor,Manager role on all IAM Services in all Regions in Resource Group - 40
-   All IAM Services in all Regions in Resource Group with Atrributes  - 10
-   Kubernetes service in all Regions - 45
-   Container Register in all Regions - 64
```

For all USERS groups

```
-   Viewer,Operator,Reader role on all IAM Services in all Regions in Resource Group - 32
-   All IAM Services in all Regions in Resource Group with Atrributes - 10
-   Kubernetes service in all Regions - 73
-   Kubernetes service with IKS instance - 73
-   Kubernetes service with OCP instance - 73
-   Container Registery service in all region - 41
-   Cloudant - 94
-   COS - 197
-   SysDig - 37
-   LogDNA - 69
-   AppID - 259
```
