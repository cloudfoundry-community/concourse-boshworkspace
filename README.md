concourse-boshworkspace
=======================

The fastest way to deploy [Concourse](http://concourse.ci).

Preparation
-----------

To get started you will need a running bosh-lite. Get yours by following the instructions [here](https://github.com/cloudfoundry/bosh-lite#install-bosh-lite)

Next step is setting up this repository

```
git clone https://github.com/cloudfoundry-community/concourse-boshworkspace.git
cd concourse-boshworkspace
bundle install
```
Deploy
------

This section includes instructions for configuration and deployment of Concourse.

### Deploy Concourse to bosh-lite

```
bosh deployment concourse-warden
bosh prepare deployment
bosh deploy
```
