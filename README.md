# Prow
[![Go Reference](https://pkg.go.dev/badge/sigs.k8s.io/prow.svg)](https://pkg.go.dev/sigs.k8s.io/prow)
[![Go Report Card](https://goreportcard.com/badge/sigs.k8s.io/prow)](https://goreportcard.com/report/sigs.k8s.io/prow)
[![LICENSE](https://img.shields.io/github/license/kubernetes-sigs/prow.svg)](https://github.com/kubernetes-sigs/prow/blob/main/LICENSE)
[![Slack Status](https://img.shields.io/badge/slack-join_chat-white.svg?logo=slack&style=social)](https://kubernetes.slack.com/archives/CDECRSC5U)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/kubernetes-sigs/prow)

![Prow Logo](./site/static/images/logo-horizontal.svg)

The source code and statically generated docs for Prow live here. Historically Prow was developed in [kubernetes/test-infra](https://github.com/kubernetes/test-infra) along with other things, but the source code was moved here on April 9, 2024.

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](http://kubernetes.io/community/).

You can reach the maintainers of this project at:

- [Slack](https://kubernetes.slack.com/messages/sig-testing)
- [Mailing List](https://groups.google.com/forum/#!forum/kubernetes-sig-testing)

## Deprecated

03 May 2022 - Usage of pod-utility images from locally built and pushed `quay.io/powercloud` private repo is deprecated.

The upstream pod-utility images from `us-docker.pkg.dev/k8s-infra-prow/images` will be used.

[Change1](https://github.com/ppc64le-cloud/test-infra/pull/309/files#diff-d840b3456d7d17beb3ded91cf0ca9d6fd065baedb31a0a634b5101df3f7925d4L77) - Started using google container registry upstream images


[Change2](https://github.com/ppc64le-cloud/test-infra/pull/487/files#diff-d840b3456d7d17beb3ded91cf0ca9d6fd065baedb31a0a634b5101df3f7925d4R83) - Moved from using Container Registry to Temporary Upstream Artifact Registry. (May change to registry.k8s.io in future. Ref: [issue](https://github.com/kubernetes-sigs/prow/issues/113)

[Change4]
 
Files from [here](https://github.com/ppc64le-cloud/test-infra/tree/master/images/pod-utilities) will not be used.

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).
