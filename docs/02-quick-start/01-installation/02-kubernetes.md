---
sidebar_label: Kubernetes
---

# Try Ozone With Kubernetes

**TODO:** File a subtask under [HDDS-9856](https://issues.apache.org/jira/browse/HDDS-9856) and complete this page or section.

```shell
ozone sh -Ddfs.checksum.combine.mode=ASDF vol create /vol1
mvn -Prelease -DskipTests clean
```

  ```shell
  ozone sh -Ddfs.checksum.combine.mode=ASDF vol create /vol1
  # comment
  mvn -Prelease -DskipTests clean
  ```
