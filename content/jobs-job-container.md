---
title: jobs.job.container definition
description: jobs.job.container definition reference.
ms.date: 01/24/2022
monikerRange: "= azure-pipelines || = azure-pipelines-2019.1 || = azure-pipelines-2020 || = azure-pipelines-2020.1"
---

# jobs.job.container definition


Container jobs allow you to run jobs on a container instead of the agent host.



:::moniker range="= azure-pipelines-2019.1"

Properties that use this definition: [pipeline.container](pipeline.md), [jobs.job.container](jobs-job.md)

:::moniker-end

:::moniker range="= azure-pipelines-2020"

Properties that use this definition: [pipeline.container](pipeline.md), [jobs.job.container](jobs-job.md), [jobs.deployment.container](jobs-deployment.md)

:::moniker-end

:::moniker range="= azure-pipelines-2020.1"

Properties that use this definition: [pipeline.container](pipeline.md), [jobs.job.container](jobs-job.md), [jobs.deployment.container](jobs-deployment.md)

:::moniker-end

:::moniker range="= azure-pipelines"

Properties that use this definition: [pipeline.container](pipeline.md), [jobs.job.container](jobs-job.md), [jobs.deployment.container](jobs-deployment.md)

:::moniker-end

## Overloads

:::moniker range="= azure-pipelines-2019.1" 

| Overload | Description |
|----------|-------------|
| [jobContainer: string](#jobcontainer-string) |  |
| [jobContainer: image](#jobcontainer-image) |  |

:::moniker-end

:::moniker range="= azure-pipelines-2020" 

| Overload | Description |
|----------|-------------|
| [jobContainer: string](#jobcontainer-string) |  |
| [jobContainer: alias](#jobcontainer-alias) |  |
| [jobContainer: image](#jobcontainer-image) |  |

:::moniker-end

:::moniker range="= azure-pipelines-2020.1" 

| Overload | Description |
|----------|-------------|
| [jobContainer: string](#jobcontainer-string) |  |
| [jobContainer: alias](#jobcontainer-alias) |  |
| [jobContainer: image](#jobcontainer-image) |  |

:::moniker-end

:::moniker range="= azure-pipelines" 

| Overload | Description |
|----------|-------------|
| [jobContainer: string](#jobcontainer-string) |  |
| [jobContainer: alias](#jobcontainer-alias) |  |
| [jobContainer: image](#jobcontainer-image) |  |

:::moniker-end

<!-- Remarks -->

:::moniker range="= azure-pipelines || = azure-pipelines-2019.1 || = azure-pipelines-2020 || = azure-pipelines-2020.1"

## jobContainer: string

:::moniker-end



:::moniker range="= azure-pipelines-2019.1"

<!-- :::api-definition signature="jobContainer{string}" version="azure-pipelines-2019.1"::: -->


```yaml
jobContainer: string # 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `jobContainer`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020"

<!-- :::api-definition signature="jobContainer{string}" version="azure-pipelines-2020"::: -->


```yaml
jobContainer: string # 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `jobContainer`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020.1"

<!-- :::api-definition signature="jobContainer{string}" version="azure-pipelines-2020.1"::: -->


```yaml
jobContainer: string # 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `jobContainer`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines"

<!-- :::api-definition signature="jobContainer{string}" version="azure-pipelines"::: -->


```yaml
jobContainer: string # 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `jobContainer`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end


<!-- Remarks -->


<!-- Examples -->

:::moniker range="= azure-pipelines || = azure-pipelines-2019.1 || = azure-pipelines-2020 || = azure-pipelines-2020.1"

## jobContainer: image

:::moniker-end



:::moniker range="= azure-pipelines-2019.1"

<!-- :::api-definition signature="jobContainer{image}" version="azure-pipelines-2019.1"::: -->


```yaml
container:
  image: string # Required. Container image tag. 
  endpoint: string # ID of the service endpoint connecting to a private container registry. 
  env:  # Variables to map into the container's environment
    string: string # Name/value pairs.
  options: string # Options to pass into container host. 
  ports: [ string ] # Ports to expose on the container. 
  volumes: [ string ] # Volumes to mount on the container. 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `endpoint`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->ID of the service endpoint connecting to a private container registry. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `env`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Variables to map into the container's environment. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `image`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required. Container image tag. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `options`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Options to pass into container host. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `ports`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Ports to expose on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `volumes`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020"

<!-- :::api-definition signature="jobContainer{image}" version="azure-pipelines-2020"::: -->


```yaml
container:
  image: string # Required. Container image tag. 
  endpoint: string # ID of the service endpoint connecting to a private container registry. 
  env:  # Variables to map into the container's environment
    string: string # Name/value pairs.
  mapDockerSocket: boolean # Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs.  (false,n,no,off,on,true,y,yes)
  options: string # Options to pass into container host. 
  ports: [ string ] # Ports to expose on the container. 
  volumes: [ string ] # Volumes to mount on the container. 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `endpoint`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->ID of the service endpoint connecting to a private container registry. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `env`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Variables to map into the container's environment. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `image`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required. Container image tag. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `mapDockerSocket`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
boolean
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `options`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Options to pass into container host. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `ports`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Ports to expose on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `volumes`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020.1"

<!-- :::api-definition signature="jobContainer{image}" version="azure-pipelines-2020.1"::: -->


```yaml
container:
  image: string # Required. Container image tag. 
  endpoint: string # ID of the service endpoint connecting to a private container registry. 
  env:  # Variables to map into the container's environment
    string: string # Name/value pairs.
  mapDockerSocket: boolean # Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs.  (false,n,no,off,on,true,y,yes)
  options: string # Options to pass into container host. 
  ports: [ string ] # Ports to expose on the container. 
  volumes: [ string ] # Volumes to mount on the container. 
  mountReadOnly:  # Volumes to mount read-only, the default is all false.
    work: boolean # Mount the work directory as readonly.  (false,n,no,off,on,true,y,yes)
    externals: boolean # Mount the externals directory as readonly.  (false,n,no,off,on,true,y,yes)
    tools: boolean # Mount the tools directory as readonly.  (false,n,no,off,on,true,y,yes)
    tasks: boolean # Mount the tasks directory as readonly.  (false,n,no,off,on,true,y,yes)
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `endpoint`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->ID of the service endpoint connecting to a private container registry. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `env`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Variables to map into the container's environment. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `image`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required. Container image tag. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `mapDockerSocket`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
boolean
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `options`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Options to pass into container host. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `ports`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Ports to expose on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `volumes`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `mountReadOnly`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string/boolean pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount read-only, the default is all false. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines"

<!-- :::api-definition signature="jobContainer{image}" version="azure-pipelines"::: -->


```yaml
container:
  image: string # Required. Container image tag. 
  endpoint: string # ID of the service endpoint connecting to a private container registry. 
  env:  # Variables to map into the container's environment
    string: string # Name/value pairs.
  mapDockerSocket: boolean # Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs.  (false,n,no,off,on,true,y,yes)
  options: string # Options to pass into container host. 
  ports: [ string ] # Ports to expose on the container. 
  volumes: [ string ] # Volumes to mount on the container. 
  mountReadOnly:  # Volumes to mount read-only, the default is all false.
    work: boolean # Mount the work directory as readonly.  (false,n,no,off,on,true,y,yes)
    externals: boolean # Mount the externals directory as readonly.  (false,n,no,off,on,true,y,yes)
    tools: boolean # Mount the tools directory as readonly.  (false,n,no,off,on,true,y,yes)
    tasks: boolean # Mount the tasks directory as readonly.  (false,n,no,off,on,true,y,yes)
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `endpoint`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->ID of the service endpoint connecting to a private container registry. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `env`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string name/value pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Variables to map into the container's environment. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `image`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Required. Container image tag. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `mapDockerSocket`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
boolean
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Set this flag to false to force the agent not to setup the /var/run/docker.sock volume on container jobs. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `options`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Options to pass into container host. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `ports`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Ports to expose on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `volumes`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string list
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount on the container. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___



<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `mountReadOnly`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string/boolean pairs
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->Volumes to mount read-only, the default is all false. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end


<!-- Remarks -->


<!-- Examples -->

:::moniker range="= azure-pipelines || = azure-pipelines-2020 || = azure-pipelines-2020.1"

## jobContainer: alias

:::moniker-end



:::moniker range="= azure-pipelines-2020"

<!-- :::api-definition signature="jobContainer{alias}" version="azure-pipelines-2020"::: -->


```yaml
container:
  alias: string # The alias of the container resource. 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `alias`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->The alias of the container resource. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines-2020.1"

<!-- :::api-definition signature="jobContainer{alias}" version="azure-pipelines-2020.1"::: -->


```yaml
container:
  alias: string # The alias of the container resource. 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `alias`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->The alias of the container resource. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end

:::moniker range="= azure-pipelines"

<!-- :::api-definition signature="jobContainer{alias}" version="azure-pipelines"::: -->


```yaml
container:
  alias: string # The alias of the container resource. 
```

### Properties


<!-- :::api-property::: -->
:::row:::
  :::column:::
   <!-- :::api-property-name::: -->
   `alias`
   <!-- :::api-property-name-end::: -->
  :::column-end:::
  :::column span="3":::
<!-- :::api-property-type::: --> 
string
<!-- :::api-property-type-end::: -->  
<!-- :::api-desc type="property"::: -->The alias of the container resource. 
 <!-- :::api-desc-end::: -->
  :::column-end:::
:::row-end:::
<!-- :::api-property-end::: -->
___





<!-- :::api-definition-end::: -->

:::moniker-end


<!-- Remarks -->


<!-- Examples -->

<!-- See also -->