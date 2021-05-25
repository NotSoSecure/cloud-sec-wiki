---
title: Kubernetes
sidebar: mydoc_sidebar
permalink: kubernetes.html
folder: mydoc
---

{% include links.html %}


## Blog and Research

* [Threat matrix for Kubernetes](https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/)
* [Secure containerized environments with updated threat matrix for Kubernetes](https://www.microsoft.com/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/)
* [Simplify Kubernetes Resource Access Control using RBAC Impersonation](https://www.cncf.io/blog/2020/09/17/simplify-kubernetes-resource-access-control-using-rbac-impersonation/)
* [Kubernetes RBAC Security Pitfalls](https://www.impidio.com/blog/kubernetes-rbac-security-pitfalls)
* [Attacking Kubernetes Clusters Through Your Network Plumbing: Part 1](https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-1)
* [Attacking Kubernetes Clusters Through Your Network Plumbing: Part 2](https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-2)
* [Applied Defense On Docker And Kubernetes](https://www.youtube.com/watch?v=auC712hFJes)
* [Bad Pods: Kubernetes Pod Privilege Escalation](https://labs.bishopfox.com/tech-blog/bad-pods-kubernetes-pod-privilege-escalation)
* [Getting into a bind with Kubernetes](https://raesene.github.io/blog/2021/01/16/Getting-Into-A-Bind-with-Kubernetes/)
* [Kubernetes Honey Token](https://darkbit.io/blog/k8s-honey-token)
* [Kubernetes Threat Model](https://cloudsecdocs.com/container_security/offensive/pentest/process/)
* [Kubernetes Compliance as Code ](https://cloudsecdocs.com/devops/tooling/compliance_as_code/#kubernetes)
* [Overview of dnsmasq Vulnerabilities: The Dangers of DNS Cache Poisoning](https://unit42.paloaltonetworks.com/overview-of-dnsmasq-vulnerabilities-the-dangers-of-dns-cache-poisoning/)
* [Dostainer - Kubernetes Resource Exhaustion PoC Container](https://github.com/uchi-mata/dostainer#dostainer---kubernetes-resource-exhaustion-poc-container)
* [ECS Fargate threat modeling](https://sysdig.com/blog/ecs-fargate-threat-modeling/)
* [Using Kubelet Client to Attack the Kubernetes Cluster](https://www.cyberark.com/resources/threat-research-blog/using-kubelet-client-to-attack-the-kubernetes-cluster)
* [10 Kubernetes Security Context settings you should understand ](https://snyk.io/blog/10-kubernetes-security-context-settings-you-should-understand/)
* [How to monitor multi-cloud Kubernetes with Prometheus and Grafana](https://inlets.dev/blog/2020/12/15/multi-cluster-monitoring.html)
* [Defend the Core: Kubernetes Security at Every Layer](https://thenewstack.io/defend-the-core-kubernetes-security-at-every-layer/)
* [Kubernetes Multi tenancy with Amazon EKS: Best practices and considerations](https://www.clickittech.com/saas/kubernetes-multi-tenancy/)
* [Generating Kubernetes Network Policies Automatically By Sniffing Network Traffic](https://itnext.io/generating-kubernetes-network-policies-by-sniffing-network-traffic-6d5135fe77db)
* [Enforcing Policy as Code using OPA and Gatekeeper in Kubernetes](https://elastisys.com/enforcing-policy-as-code-using-opa-and-gatekeeper-in-kubernetes/)

## Offensive tools

- [Kubestriker](https://github.com/vchinnipilli/kubestriker) - Kubestriker is a platform-agnostic tool designed to tackle Kuberenetes cluster security issues due to misconfigurations and will help strengthen the overall IT infrastructure of any organisation.
- [kubesploit](https://github.com/cyberark/kubesploit) - Kubesploit is a cross-platform post-exploitation HTTP/2 Command & Control server and agent dedicated for containerized environments

## Defensive Tools

* [aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator) - A tool to use AWS IAM credentials to authenticate to a Kubernetes cluster
* [cert-manager](https://github.com/jetstack/cert-manager) - Automatically provision and manage TLS certificates in Kubernetes
* [guard](https://github.com/appscode/guard) - Kubernetes Authentication WebHook Server 
* [kube2iam](https://github.com/jtblin/kube2iam) - kube2iam provides different AWS IAM roles for pods running on Kubernetes
* [kube-lego](https://github.com/jetstack/kube-lego) - Automatically request certificates for Kubernetes Ingress resources from Let's Encrypt

## Security Tools

* [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark
* [kube-hunter](https://github.com/aquasecurity/kube-hunter) - Kube-hunter hunts for security weaknesses in Kubernetes clusters. The tool was developed to increase awareness and visibility for security issues in Kubernetes environments. 
* [KubiScan](https://github.com/cyberark/KubiScan) - A tool for scanning Kubernetes cluster for risky permissions in Kubernetes's Role-based access control (RBAC) authorization model.
* [kubeaudit](https://github.com/Shopify/kubeaudit) - kubeaudit helps you audit your Kubernetes clusters against common security controls
