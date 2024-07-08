# docker_mirror_action

- 这是一个docker镜像代理action
  - 防止某些docker拉取不了，利用github action拉取并提交到附件，手动导入docker镜像

---
### 食用方法


提交Issue并按如下示例编辑Issue，提交即可触发action

``` bash
["registry.k8s.io/kube-controller-manager:v1.27.4","registry.k8s.io/kube-proxy:v1.27.4","registry.k8s.io/kube-scheduler:v1.27.4","registry.k8s.io/conformance:v1.27.4"]
```