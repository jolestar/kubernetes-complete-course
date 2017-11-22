<style type="text/css">
.slide {
	background: #fff !important;
}
</style>
<!-- $theme: gaia -->
<!-- $size: 16:9 -->
<!-- footer: @jolestar -->


# Kubernetes 完全教程
## Kubernetes 的扩展开发概述

### 王渊命 @jolestar

![bg](images/bg.png) 

---
# Agenda

1. Kubernetes 的扩展点概览
1. Kubernetes 的源码概览
1. Kubernetes 的 CloudProvider
1. Kubernetes 的 CNI 插件
1. Kubernetes 的 Volume 插件
1. Kubernetes 的 CustomResourceDefinitions

---
# Kubernetes 的扩展点概览

1. Admission Control
	- Initializers: [kubernetes-initializer-tutorial](https://github.com/kelseyhightower/kubernetes-initializer-tutorial)
	- GenericAdmissionWebhook ImagePolicyWebhook
1. [Device Plugins(1.8)](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/resource-management/device-plugin.md)
1. CloudProvider
1. CNI 插件
1. Volume 插件
1. CustomResourceDefinitions

---
# Kubernetes 的源码概览
1. Kubernetes 源码目录结构
1. Kubernetes 构建脚本
1. Kubernetes 的源码生成机制
	- https://github.com/kubernetes/gengo
	- https://github.com/kubernetes/code-generator 

---
# Kubernetes 的 CloudProvider

1. CloudProvider 的作用
2. [CloudProvider 案例解读](https://github.com/yunify/qingcloud-cloud-controller-manager)

---
# Kubernetes 的 CNI 插件

1. CNI 的[规范](https://github.com/containernetworking/cni/blob/spec-v0.3.1/SPEC.md)
2. CNI 的运行原理-通过 [CNI script](https://github.com/containernetworking/cni/tree/master/scripts) 分析

---
# Kubernetes 的 Volume 插件

1. Volume Provisioner 接口 
2. Flex Volume 接口
3. [Volume Plugin 案例解读](https://github.com/yunify/qingcloud-volume-provisioner)

---
# CustomResourceDefinitions

1. CRD 应用场景
1. CRD [规范以及机制](https://kubernetes.io/docs/concepts/api-extension/custom-resources/)
1. CRD 案例讲解
	- https://github.com/openshift-evangelists/crd-code-generation

---
# 总结

- 对 Kubernetes 的 扩展开发有一个整体的了解

---
# 作业

1. 自己编译打包一下 Kubernetes，做一个小小的修改，并通过 minikube 部署。
1. 思考一个扩展 Kubernetes 的点子，然后看看是否已经有人开发，没有的话自己尝试开发一下。


---
### 关于我

个人博客: [http://jolestar.com](http://jolestar.com)
课程 Github：[https://github.com/jolestar/kubernetes-complete-course](https://github.com/jolestar/kubernetes-complete-course)

课程 QQ 群: 451252952

![about](http://jolestar.com/images/weichat/qrcode_jolestar_blog2.png)

---

<img style="width:100%;height=100%;margin:0;padding:0;" src="images/about-us.png"/>

