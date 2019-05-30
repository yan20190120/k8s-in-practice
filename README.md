# Introduction

# k8s-in-practice

## Summary
1. [01-1.Kubernetes 设计原则](concept/design.md)
1. [02-1.Kubernetes 对象介绍](concept/object.md)
3. [03-1.kubectl](concept/kubectl.md)
1. [04.pod状态与生命周期管理](concept/pod-state-and-lifecycle.md)
    1. [04-1.pod-view](concept/pod-overview.md)
    1. [04-2.pause-container](concept/pause-container.md)
    1. [04-3.pod-lifecycel](concept/pod-lifecycle.md)
    1. [04-4.pod-probe](concept/pod-probe.md)
    1. [04-5.pod-hook](concept/pod-hook.md)
    1. [04-6.init-container](concept/init-containers.md)
    1. [04-7.pod-preset](concept/pod-preset.md)

1. [05.pod计算资源管理](resource-quotas/resource-manager.md)
    1. [05-1.pod-resource](resource-quotas/pod-resource.md)
    1. [05-2.pod-qos](resource-quotas/pod-qos.md)
    1. [05-3.pod-limit-range-mem](resource-quotas/pod-limit-range-mem.md)
    1. [05-4.pod-limit-range-cpu](resource-quotas/pod-limit-range-cpu.md)
    1. [05-5.pod-cpu-mem-quota](resource-quotas/pod-cpu-mem-quota.md)
    1. [05-6.pod-count-quota](resource-quotas/pod-count-quota.md)
    2. [05-7.pod-extentd-resource](resource-quotas/pod-extentd-resources.md)

1. [06.workload](workload/workload.md)
    1. [06-1.replicacontroller](workload/replicacontroller.md)
    1. [06-2.replicaset](workload/replicaset.md)
    1. [06-2.daemonset](workload/daemonset.md)

1. [07.service](service/service.md)
    1. [07-1.introduction](service/introduction.md)
    1. [07-2.service-type](service/service-type.md)
    1. [07-3.ingress](service/ingress.md)
    1. [07-4.svc-and-readiness-probe](service/svc-and-readiness-probe.md)
    1. [07-5.headless](service/headless.md)

1. [08.deployment](deployment/readme.md)
    1. [08-1.deployment-background](deployment/deployment-rc.md)
    1. [08-2.deployment](deployment/deployment.md)

1. [09.volume](volume/volume.md)
    1. [09-1.emptydir](volume/emptydir.md)
    1. [09-2.hostpath](volume/hostpath.md)
    1. [09-3.nfs](volume/nfs.md)
    1. [09-4.dynamic](volume/pv-and-pvc.md)
    1. [09-5.ceph-rbd](volume/ceph-rbd.md)
    1. [09-6.cephfs](volume/cephfs.md)

1. [10.StatefulSet](statefulset/readme.md)
    1. [10-1.sts-overview](statefulset/sts-overview.md)
    1. [10-2.sts-practice](statefulset/sts-practice.md)
    1. [10-3.sts-upgrade](statefulset/sts-update.md)

1. [11.Scheduler](scheduler/readme.md)
    1. [11-1.node-affinity](scheduler/node-affinity.md)
    1. [11-2.pod-affinity](scheduler/pod-affinity.md)
    1. [11-3.pod-anti-affinity](scheduler/pod-anti-affinity.md)
    1. [11-4.taint-toleration](scheduler/taint-toleration.md)

1. [12.security](security/readme.md)
    1. [12-1.security-context](security/security-context.md)
    1. [12-2.rbac](security/rbac.md)
    1. [12-3.rbac-clientgo](security/rbac-clientgo.md)
    1. [12-4.admission](security/admission.md)
    1. [12-5.sysctl](security/sysctl.md)

1. [13.applications-config](application-config/readme.md)
    1. [13-1.command-line-arguments](application-config/command-line-arguments.md)
    1. [13-2.environment](application-config/environment.md)
    1. [13-3.ConfigMap](application-config/configmap.md)
    1. [13-4.Secret](application-config/secret.md)
    1. [13-5.downwardAPI](application-config/downward-api.md)

1. [14.ops](ops/readme.md)
    1. [14-1.high-availability](ops/high-availability.md)
    1. [14-2.etcd](ops/etcd.md)
    1. [14-3.metrics](ops/metrics.md)

1. [Tasks](tasks/tasks.md)
    1. [hostalias](tasks/hostalias.md)
    1. [k8s-app-development](tasks/client-go.md)
    1. [replay-example](tasks/replay-example.md)
    1. [replay-template](tasks/replay-template.md)
    1. [k8s-custem-development](tasks/k8s-compile.md)
    1. [gitlab](tasks/gitlab.md)
    1. [jenkins](tasks/jenkins.md)
    1. [ceph-deploy](tasks/ceph-deploy.md)
    1. [rook](tasks/rook.md)
    1. [kubectl常用姿势](tasks/kubectl.md)

## **Slogan**
#### ***Benefit from open source and contribute to the community***

## **Contributors !!!**
[@MrYueQ](https://github.com/MrYueQ)  
[@yangruiyou85](https://github.com/yangruiyou85)
