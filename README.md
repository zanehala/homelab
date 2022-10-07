<div align="center">

# Zane's Homelab

</div>

## Overview

This is a heavily modified fork of [Khue's incredible homelab](https://github.com/khuedoan/homelab), which I highly suggest you check out.
One of the biggest features that drew me to his project was the minimal bootstrapping needed to go from totally blank bare metal
to a fully functioning cluster. 

### Hardware

- 4 × Dell Optiplex 7050 MFF:
  - CPU: A mix of `Intel Core i5-6600T @ 2.70GHz, Intel Core i5-7600T @ 2.80GHz, and one Intel Core i5-7600 (non T model) @ 3.50GHz, `
  - RAM: `16GB`
  - SSD: `128GB - 500GB`
- TP-Link `TL-SG108` switch:
  - Ports: `8` 
  - Speed: `1000Mbps`

### Features

### Tech stack

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://simpleicons.org/icons/ansible.svg"></td>
    <td><a href="https://www.ansible.com">Ansible</a></td>
    <td>Automate bare metal provisioning and configuration</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/argo/icon/color/argo-icon-color.svg"></td>
    <td><a href="https://argoproj.github.io/cd">ArgoCD</a></td>
    <td>GitOps tool built to deploy applications to Kubernetes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://github.com/jetstack/cert-manager/raw/master/logo/logo.png"></td>
    <td><a href="https://cert-manager.io">cert-manager</a></td>
    <td>Cloud native certificate management</td>
  </tr>
  <tr>
    <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
    <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
    <td>DNS and Tunnel</td>
  </tr>
  <tr>
    <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
    <td><a href="https://www.docker.com">Docker</a></td>
    <td>Ephermeral PXE server and convenient tools container</td>
  </tr>
  <tr>
    <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Gitea_Logo.svg"></td>
    <td><a href="https://gitea.com">Gitea</a></td>
    <td>Self-hosted Git service</td>
  </tr>
  <tr>
    <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
    <td><a href="https://grafana.com">Grafana</a></td>
    <td>Operational dashboards</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.svg"></td>
    <td><a href="https://helm.sh">Helm</a></td>
    <td>The package manager for Kubernetes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.svg"></td>
    <td><a href="https://k3s.io">K3s</a></td>
    <td>Lightweight distribution of Kubernetes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/kubernetes/icon/color/kubernetes-icon-color.svg"></td>
    <td><a href="https://kubernetes.io">Kubernetes</a></td>
    <td>Container-orchestration system, the backbone of this project</td>
  </tr>
  <tr>
    <td><img width="32" src="https://github.com/grafana/loki/blob/main/docs/sources/logo.png?raw=true"></td>
    <td><a href="https://grafana.com/oss/loki">Loki</a></td>
    <td>Log aggregation system</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/longhorn/icon/color/longhorn-icon-color.svg"></td>
    <td><a href="https://longhorn.io">Longhorn</a></td>
    <td>Cloud native distributed block storage for Kubernetes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://avatars.githubusercontent.com/u/60239468?s=200&v=4"></td>
    <td><a href="https://metallb.org">MetalLB</a></td>
    <td>Bare metal load-balancer for Kubernetes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4"></td>
    <td><a href="https://www.nginx.com">NGINX</a></td>
    <td>Kubernetes Ingress Controller</td>
  </tr>
  <tr>
    <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/prometheus/icon/color/prometheus-icon-color.svg"></td>
    <td><a href="https://prometheus.io">Prometheus</a></td>
    <td>Systems monitoring and alerting toolkit</td>
  </tr>
  <tr>
    <td><img width="32" src="https://avatars.githubusercontent.com/u/75713131?s=200&v=4"></td>
    <td><a href="https://rockylinux.org">Rocky Linux</a></td>
    <td>Base OS for Kubernetes nodes</td>
  </tr>
  <tr>
    <td><img width="32" src="https://raw.githubusercontent.com/drone/brand/master/logos/vector/drone-logo-vector-white.svg"></td>
    <td><a href="https://www.drone.io/">Drone</a></td>
    <td>CI and build system</td>
  </tr>
  <tr>
    <td><img width="32" src="https://trow.io/trow.png"></td>
    <td><a href="https://trow.io">Trow</a></td>
    <td>Private container registry</td>
  </tr>
  <tr>
    <td><img width="32" src="https://simpleicons.org/icons/vault.svg"></td>
    <td><a href="https://www.vaultproject.io">Vault</a></td>
    <td>Secrets and encryption management system</td>
  </tr>
</table>
