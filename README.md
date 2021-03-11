![GitHub version](https://img.shields.io/badge/version-v0.0.1-brightgreen.svg?logo=appveyor&longCache=true&style=flat)
![go report](https://goreportcard.com/badge/github.com/kubesphere/porterlb)

# PorterLB: Load Balancer Implementation for Bare Metal

![logo](doc/img/porter-logo.png)

PorterLB is an open-source load balancer implementation designed for bare-metal Kubernetes clusters.

## Why PorterLB

In cloud-based Kubernetes clusters, Services are usually exposed by using load balancers provided by cloud vendors. However, cloud-based load balancers are unavailable in bare-metal environments. PorterLB allows users to create LoadBalancer Services in bare-metal environments for external access, and provides the same user experience as cloud-based load balancers.

## Core Features

- BGP mode and Layer 2 mode
- ECMP routing and load balancing
- IP address pool management
- BGP configuration using CRDs
- Installation using Helm and KubeSphere

## Documentation

Without a bare-metal environment yet? Doesn't matter!

You can learn how to use PorterLB in a cloud-based Kubernetes cluster by following the [PorterLB Documentation](https://porterlb.io/docs/).

## Support, Discussion and Contributing

PorterLB is a sub-project of [KubeSphere](https://github.com/kubesphere/kubesphere).

* Join us at the [KubeSphere Slack Channel](https://kubesphere.slack.com/join/shared_invite/enQtNTE3MDIxNzUxNzQ0LTZkNTdkYWNiYTVkMTM5ZThhODY1MjAyZmVlYWEwZmQ3ODQ1NmM1MGVkNWEzZTRhNzk0MzM5MmY4NDc3ZWVhMjE#/) to get support or simply tell us that you are using PorterLB.
* You have code or documents for PorterLB? Contributions are always welcome! See [Building and Contributing](https://porterlb.io/docs/building-and-contributing/) to obtain guidance.

## Landscapes

<p align="center">
<br/><br/>
<img src="https://landscape.cncf.io/images/left-logo.svg" width="150"/>&nbsp;&nbsp;<img src="https://landscape.cncf.io/images/right-logo.svg" width="200"/>&nbsp;&nbsp;
<br/><br/>
PorterLB is a promising newcomer in Service proxy, which enriches the <a href="https://landscape.cncf.io/landscape=observability-and-analysis&license=apache-license-2-0">CNCF CLOUD NATIVE Landscape.
</a>
</p>


## License

PorterLB is licensed under the Apache License, Version 2.0. See [LICENSE](./LICENSE) for the full license text.