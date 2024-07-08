---
name: docker_mirror_action issue template
about: 用于执行 docker_mirror_action workflow 的 issue 模板
title: docker_mirror_action-请求执行任务
labels: ''
assignees: ''

---

[
"格式：你需要转换的原始镜像$自定义镜像名:自定义标签名",
"其中 $自定义镜像名:自定义标签名 是可选的",
"以下是三个正确示例",
"registry.k8s.io/kube-apiserver:v1.27.4",
"registry.k8s.io/kube-apiserver:v1.27.4$my-kube-apiserver",
"registry.k8s.io/kube-apiserver:v1.27.4$my-kube-apiserver:mytag"
]
