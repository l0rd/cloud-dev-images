# Cloud Dev Images

A list of sample Dockerfile, based on different base images, that can be used to create a custom Cloud Development Environment in Eclipse Che and Red Hat OpenShift Dev Spaces.

| Base image | Dockerfile | Build Satus | VS Code Startup | Try it |
|------------|------------|-------------|-----------------|--------|
| alpine | [link](https://github.com/l0rd/cloud-dev-images/blob/main/alpine/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/alpine-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/alpine-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/alpine-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/alpine-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:alpine&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:alpine&che-editor=che-incubator/che-code/insiders) |
| busybox | [link](https://github.com/l0rd/cloud-dev-images/blob/main/busybox/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/busybox-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/busybox-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/busybox-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/busybox-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:busybox&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:busybox&che-editor=che-incubator/che-code/insiders) |
| fedora | [link](https://github.com/l0rd/cloud-dev-images/blob/main/fedora/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/fedora-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/fedora-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/fedora-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/fedora-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:fedora&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:fedora&che-editor=che-incubator/che-code/insiders) |
| golang | [link](https://github.com/l0rd/cloud-dev-images/blob/main/golang/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/golang-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/golang-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/golang-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/golang-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:golang&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:golang&che-editor=che-incubator/che-code/insiders) |
| openjdk | [link](https://github.com/l0rd/cloud-dev-images/blob/main/openjdk/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/openjdk-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/openjdk-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/openjdk-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/openjdk-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:openjdk&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:openjdk&che-editor=che-incubator/che-code/insiders) |
| ubi8 | [link](https://github.com/l0rd/cloud-dev-images/blob/main/ubi8/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi8-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi8-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi8-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi8-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubi8&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubi8&che-editor=che-incubator/che-code/insiders) |
| ubi9 | [link](https://github.com/l0rd/cloud-dev-images/blob/main/ubi9/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi9-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi9-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi9-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubi9-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubi9&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubi9&che-editor=che-incubator/che-code/insiders) |
| ubuntu | [link](https://github.com/l0rd/cloud-dev-images/blob/main/ubuntu/Dockerfile) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubuntu-build.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubuntu-build.yaml) | [![build](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubuntu-vscode-startup.yaml/badge.svg)](https://github.com/l0rd/cloud-dev-images/actions/workflows/ubuntu-vscode-startup.yaml) | [![dogfooding](https://img.shields.io/static/v1?label=dogfooding%20%20%20%20&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://che-dogfooding.apps.che-dev.x6e0.p1.openshiftapps.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubuntu&che-editor=che-incubator/che-code/insiders) [![devsandbox](https://img.shields.io/static/v1?label=rh%20dev%20sandbox&message=vscode&logo=eclipseche&color=FDB940&labelColor=525C86)](https://workspaces.openshift.com/#https://github.com/l0rd/cloud-dev-images?image=quay.io/mloriedo/cloud-dev-images:ubuntu&che-editor=che-incubator/che-code/insiders) |
