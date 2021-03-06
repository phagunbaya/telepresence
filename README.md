# [Documentation - start here!](http://telepresence.io)

[![Build Status](https://travis-ci.org/datawire/telepresence.svg?branch=master)](https://travis-ci.org/datawire/telepresence)
[![Join the chat at https://gitter.im/datawire/telepresence](https://badges.gitter.im/datawire/telepresence.svg)](https://gitter.im/datawire/telepresence?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Demo

[![asciicast](https://asciinema.org/a/109183.png)](https://asciinema.org/a/109183)

## Telepresence: local development against a remote Kubernetes cluster

Have you ever wanted the quick development cycle of local code while still having your code run within a remote Kubernetes cluster?
Telepresence allows you to run your code locally while still:

1. Giving your code access to Services in a remote Kubernetes cluster.
2. Giving your code access to cloud resources like AWS RDS or Google PubSub.
3. Allowing Kubernetes to access your code as if it were in a normal pod within the cluster.

Telepresence is part of the [Blackbird Project](https://www.datawire.io/blackbird/), and licensed under the Apache 2.0 License.
