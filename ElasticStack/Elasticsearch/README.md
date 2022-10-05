# Elasticsearch

## Prerequisites
1. update variable **ES_HOME** in according to your context  
or  
set **ES_HOME** as environment variable and export it  

2. update variable **ES_LOG** in according to your context  
(replace <file:cluster log> by the cluster name + .log)

## Permissions

```bash
chmod +x elasticsearch
```

## Usage

### Start elasticsearch service
use parameter **start**

```bash
./elasticsearch  start
```

or

```bash
./elasticsearch
```

### Stop elasticsearch service
use parameter **stop**

```bash
./elasticsearch stop
```

### check the status of elasticsearch service
use parameter **status**

```bash
./elasticsearch status
```

### Display help
use parameter **help** or **-h**

```bash
./elasticsearch help
```

or

```bash
./elasticsearch -h
```
